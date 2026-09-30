# 沉淀（chat-distill）

把一段对话中的已确认结论、踩坑、机制和待验证事项整理为可复用的 SOP，并写入按北京时间命名的 Markdown 沉淀文件。

## 使用

将本仓库克隆为 Claude Code 的 `chat-distill` Skill：

```bash
git clone https://github.com/dvonascjona/chat-distill.git ~/.claude/skills/chat-distill
```

在对话中输入 `#沉淀` 处理整段对话，或输入“只沉淀某个主题”限定范围。完整规则见 [SKILL.md](SKILL.md)。

## 使用前提

这是作者正在使用的原版 Skill，包含作者环境的固定路径 `/opt/1panel/apps/Claude_work/沉淀/` 和 `HANDOFF.md`，并要求将项目踩坑同步到相应 `WORKFLOW.md`。在其他机器使用前，请先按自己的目录结构调整这些路径和联动规则。原始 Skill 文件未因公开发布而修改。
