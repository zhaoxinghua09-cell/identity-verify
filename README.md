# identity-verify

[![License](https://img.shields.io/badge/License-LICENSE.md-yellow.svg)](LICENSE.md)
[![Agent Ready](https://img.shields.io/badge/AI--friendly-llms.txt-blue.svg)](llms.txt)
[![Docs](https://img.shields.io/badge/docs-AGENTS.md-2ea44f.svg)](AGENTS.md)
[![Security](https://img.shields.io/badge/security-policy-orange.svg)](SECURITY.md)
[![Citable](https://img.shields.io/badge/cite-CITATION.cff-8a2be2.svg)](CITATION.cff)

> [![License](https://img.shields.io/badge/License-LICENSE.md-yellow.svg)](LICENSE.md)

## 概览 · Overview

确认当前会话的登录入口身份，用于回答「你是哪个入口」「是不是同一个 AI 的另一个账号」「标记别搞错」这类问题

---

## 原始说明（未改动）

# identity-verify

[![License](https://img.shields.io/badge/License-LICENSE.md-yellow.svg)](LICENSE.md)
[![Agent Ready](https://img.shields.io/badge/AI--friendly-llms.txt-blue.svg)](llms.txt)
[![Docs](https://img.shields.io/badge/docs-AGENTS.md-2ea44f.svg)](AGENTS.md)
[![Security](https://img.shields.io/badge/security-policy-orange.svg)](SECURITY.md)
[![Citable](https://img.shields.io/badge/cite-CITATION.cff-8a2be2.svg)](CITATION.cff)

> - **权利状态**：本仓库以 **MIT 许可** 许可发布，可依该许可证条款自由使用、修改与再分发。

## 🚀 快速开始 / Quick Start

```bash
git clone https://github.com/zhaoxinghua09-cell/identity-verify.git
cd identity-verify
```

克隆后按仓库内 `README`/`SKILL.md`/`docs/` 的说明使用；命令与目录结构见下方「仓库内容」。

---

## 原始说明（未改动）

# identity-verify
## 许可说明 · License Notice

- **权利状态**：本仓库以 **MIT 许可** 许可发布，可依该许可证条款自由使用、修改与再分发。
- **引用建议**：引用时请标注仓库名与原文链接 `https://github.com/zhaoxinghua09-cell/identity-verify`
  与权利人「赵兴华 / Steven Zhao·China」。
- **品牌状态限定**：MedXpert、SynomosAI、LGD 等为相关项目标识，
  **均未申请实体注册、未申请商标注册**；出现仅作来源标识，
  不构成对法人实体或商标权的任何主张。
- **完整条款**：见仓库根目录 [LICENSE](LICENSE.md)。
- **联系**：zhaoxinghua06@126.com ｜ ORCID 0009-0001-0512-1237

---


> 确认当前会话的登录入口身份，用于回答「你是哪个入口」「是不是同一个 AI 的另一个账号」「标记别搞错」这类问题

SynomosAI 四支柱体系：**身份（Identity）· 溯源（Traceability）· 治理（Governance）· 共生（Symbiosis）**——当 AI 进入商业，可信是唯一的硬通货。

## 仓库内容

本仓库为 `identity-verify` 技能的发布包：核心文件 `SKILL.md` 遵循 Agent Skills 规范（YAML frontmatter），可直接放入主流 AI Agent 的技能目录使用。

- **分类**：身份核验
- **版本**：1.0.0
- **署名**：诺卫(Phylax)@SynomosAI
- **许可**：MIT（详见仓库 LICENSE）

## 使用方式

1. 克隆本仓库，或将技能目录放入 Agent 技能目录（如 `~/.workbuddy/skills/`）；
2. 按 `SKILL.md` 的描述与触发词调用对应能力；
3. 详细方法与模板见 `SKILL.md` 正文。

---

## 免责声明

本仓库内容为**理论站位与工具化探索**，不代表任何已获认证、已商业化交付或已服务特定客户的声明；文中涉及的外部标准、认证与条款信息为公开资料转述，正式引用前请**独立核实**。API、授权码与形象大使等为路线图（roadmap）事项，尚未上线。

## 仓库内容

```
├── LICENSE.md
├── README.md
├── SKILL.md
├── manifest.json
```

## 仓库内容

```
├── AGENTS.md
├── CITATION.cff
├── CONTRIBUTING.md
├── LICENSE.md
├── README.en.md
├── README.md
├── SECURITY.md
├── SKILL.md
├── llms-full.txt
├── llms.txt
├── manifest.json
```

## 检索元数据 · Metadata

```json
{
 "repository": "zhaoxinghua09-cell/identity-verify",
 "topics": [
  "agent",
  "agent-skills",
  "ai-agents",
  "ai-governance",
  "audit",
  "claude-code",
  "cli",
  "compliance",
  "content-publishing",
  "documentation",
  "lgd",
  "lifecycle-governance",
  "offline-first",
  "open-source",
  "prompt-engineering",
  "python",
  "self-hosted",
  "skill-library",
  "synomosai",
  "workbuddy"
 ],
 "license": "MIT",
 "default_branch": "main",
 "size_kb": 7
}
```

## 文档族 · Documentation set

| 文件 | 用途 |
|---|---|
| `README.md` | 权威说明（本文件） |
| `README.en.md` | 英文摘要 |
| `AGENTS.md` | 给 AI Agent 的使用指引与硬约束 |
| `llms.txt` | AI 检索索引 |
| `llms-full.txt` | 完整摄入（含原始 README 全文） |
| `SECURITY.md` | 安全策略 |
| `CONTRIBUTING.md` | 贡献指引 |
| `CITATION.cff` | 引用信息 |

## 引用 · Citation

仓库提供 `CITATION.cff`，可按其中格式引用。权利主体与许可以下方「许可说明」及仓库根目录许可文件为准。
