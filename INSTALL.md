# 安装说明

## 本地项目安装

如果你想把这个 Skill 装到某个项目里，可以放到项目的技能目录下：

```bash
mkdir -p .claude/skills
git clone https://github.com/YOUR_NAME/parenting-growth-expert-skill .claude/skills/parenting-growth-expert-skill
```

## 全局安装

如果你希望它全局可用：

```bash
git clone https://github.com/YOUR_NAME/parenting-growth-expert-skill ~/.claude/skills/parenting-growth-expert-skill
```

如果你的环境直接使用 `~/.codex/skills`：

```bash
git clone https://github.com/YOUR_NAME/parenting-growth-expert-skill ~/.codex/skills/parenting-growth-expert-skill
```

## 最小必需文件

真正必须的只有：

```text
SKILL.md
```

其余文件用于帮助理解、审阅、分发和后续维护。

## 安装后

如果你的客户端不支持热加载，请重启客户端。
