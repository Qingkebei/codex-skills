# Codex Skills

Qingkebei 的个人 Codex 技能集合。每个技能保存在 `skills/` 下的独立目录中，分别维护版本标签。

## 技能

| 技能 | 功能 | 初始版本 |
|---|---|---|
| [seven-step-paper-notes](skills/seven-step-paper-notes/SKILL.md) | 七步论文批判性阅读与 Obsidian Markdown 笔记生成 | `seven-step-paper-notes/v0.1.0` |

## 使用

将所需技能的完整文件夹安装到本机 Codex 的技能目录，再显式调用：

```text
$seven-step-paper-notes 使用七步法分析这篇论文，并生成 Obsidian 笔记。
```

提供论文全文或可访问的全文来源，并可指定笔记保存目录。具体行为见对应 `SKILL.md`。

## 版本管理

- `main` 保存当前开发版本，每次修改通过 Git commit 记录。
- 稳定版本使用 `<skill-name>/v<版本号>` 标签；各技能可独立编号。
- `seven-step-paper-notes/v0.1.0` 保存首次发布的原始版本，尚未加入后续使用反馈中的改进。
- GitHub 仓库与本机已安装技能需显式同步；推送仓库不会自动更新本机安装。

## 来源

七步阅读框架参考 Jacques Cornwell 的 [Nature 文章](https://www.nature.com/articles/d41586-026-01209-0)。Obsidian 笔记流程的设计参考了 [DeepPaperNote](https://github.com/917Dhj/DeepPaperNote)、[obsidian-skills](https://github.com/kepano/obsidian-skills) 和 [Obsidian Literature Workflow](https://github.com/brycewang-stanford/Auto-Empirical-Research-Skills/tree/main/skills/33-Galaxy-Dawn-claude-scholar/skills/obsidian-literature-workflow)。

本仓库暂未指定开源许可证；公开可见不等同于授予任意使用或再分发许可。
