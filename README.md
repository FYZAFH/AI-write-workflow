# AI-write-workflow

一组用于 Codex CLI 的本地技能（skills），聚焦中文写作场景：去 AI 味、将知识内容改写为结构化参考手册等。

## Skills

- `skills/humanizer-zh`：识别并消除中文文本中的 AI 写作痕迹，让表达更自然、有人味。
- `skills/knowledge-rewriter`：将教材/博客/笔记等知识性内容改写为风格统一、格式规范、通俗易懂且完整的 Markdown 参考手册。

## 安装

将需要的技能目录复制（或软链接）到你的 Codex skills 目录（通常为 `$CODEX_HOME/skills`），结构形如：

```text
$CODEX_HOME/skills/
  humanizer-zh/SKILL.md
  knowledge-rewriter/SKILL.md
```

## 使用

在 Codex 对话中显式提到技能名即可触发（例如 `$humanizer-zh` 或 `humanizer-zh`）。

- `humanizer-zh`：把需要“去 AI 味”的中文文本贴上来，并说明语境（论文/博客/自媒体/公文等）。
- `knowledge-rewriter`：把要改写的原始材料贴上来，并说明读者水平与目标风格（如“像官方参考手册”）。

