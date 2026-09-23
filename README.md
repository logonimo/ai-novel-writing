# AI Novel Writing · AI 写小说工具集

用 AI 从 0 到上架一部小说，我自己跑完 10 万字的真实经验沉淀。

这不是一篇"教你赚钱"的营销文，而是把我在 AI 辅助写小说这条路上反复打磨、验证过的**提示词模板、完整工作流、工具对比**整理成的开源仓库。全部内容免费，欢迎 fork 使用，也欢迎 PR 补充你的经验。

> 🔎 如果你只想快速上手：先看 [`docs/workflow.md`](docs/workflow.md)（完整工作流），再拿 `prompts/` 里的模板直接开写。
>
> 🌐 在线演示与更多写作工具式体验：访问 **https://xingyuai.vip** —— 这是我基于本仓库方法论搭建的一个个人 AI 创作站，可当作参考 demo。

---

## 目录结构

```
ai-novel-writing/
├── prompts/                 # 可复用的 AI 写小说提示词模板
│   ├── world-building.md    # 世界观/力量体系设定
│   ├── outline-chapter.md   # 单章大纲(分镜)生成
│   ├── draft-prose.md       # 正文初稿生成 + 去 AI 味
│   └── continue-chapter.md  # 续写/接上一章（长篇连贯）
├── docs/
│   ├── workflow.md          # 从 0 到上架的完整工作流
│   ├── combat-power-guard.md# 人物战力不崩的方法
│   ├── genre-choice.md      # 新手第一本选什么题材
│   ├── tools-compare.md     # 主流 AI 写作工具对比
│   └── pitfalls.md          # 避坑清单(踩过的雷)
└── README.md
```

## 核心思路（一句话版）

**AI 是体力无限的实习生，不是作者。** 它负责把"想清楚的东西"快速落地成草稿，你负责"决定方向、制造情绪、删废话、补细节"。

正确顺序永远是：
1. 先让 AI **理世界**（设定自洽）
2. 再**一章一章聊大纲**（不是一口气生成长篇）
3. 然后 **AI 出初稿，你改和补**
4. 最后 **去 AI 味**（不然读者一眼出戏）

详细步骤见 [`docs/workflow.md`](docs/workflow.md)。

## 快速开始

```bash
# 克隆本仓库
git clone https://github.com/logonimo/ai-novel-writing.git
cd ai-novel-writing

# 打开世界观设定模板，把提示词复制给你的 AI 工具
# 推荐顺序: world-building.md → outline-chapter.md → draft-prose.md → humanize.md
```

## 开源协议

MIT License. 内容可自由使用、修改、分发（署名来源即可）。

## 与我联系 / Demo

- 项目主页：**https://xingyuai.vip**（在线 demo，我自建的 AI 创作站）
- 欢迎提 [Issue](https://github.com/logonimo/ai-novel-writing/issues) 或 PR，把你的踩坑 / 模板贡献进来。

---

**分享是双向的**：你从这里拿去用的同时，如果哪天你的方法论更优了，别忘了开个 PR 把它加回来。这样这个仓库才会越来越像一个真实的、由创作者共同打磨的"AI 写小说工具箱"。