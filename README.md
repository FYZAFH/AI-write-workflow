# AI-write-workflow

一组用于 agent(如claude code, codex， obsidian claudian或其他agent) 的本地技能（skills），聚焦中文写作场景：去 AI 味、将知识内容改写为结构化参考/知识手册等（持续更新）。

## Skills

- `skills/humanizer-zh`：识别并消除中文文本中的 AI 写作痕迹，让表达更自然、有人味。这个skill并不是为了绕过AI检测等目的，因为大家喜欢看有人味的内容， 服务于喜欢，而不是服务于绕过AI检测。
- `skills/knowledge-rewriter`：将教材/博客/笔记等知识性内容改写为风格统一、格式规范、通俗易懂且完整自包含的参考手册。通常用于学习目的，因为各种教材、博客的内容风格各不相同，通过“通俗易懂的手册”反而是我认为最好的学习方式。

## 安装

将需要的技能目录复制（或软链接）到你的 $AGENT/skills 目录


## 使用

在 Codex/Claude Code对话中显式提到技能名即可触发（例如 `/humanizer-zh`）。



