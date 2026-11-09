# 通用 Agent Skills 导出包

本目录两个 skill 可拷贝到任意支持 `SKILL.md` 的 Agent（Cursor / Claude Code / 同类工具）。

## 内容

| 目录 | 用途 |
|------|------|
| `closed-loop-rd/` | Plan→Design→Build→Test 闭环、版本化文档、Hooks、外部 Skill 准入 |
| `sharpen-four-questions/` | 改题前四问：专家增量、原始素材、方法工具、独立证明，再写更深题目 |

## 安装

1. 把对应目录复制到项目的 skills 路径（如 `.cursor/skills/<name>/` 或工具文档指定位置）。
2. 确保目录内有 `SKILL.md`。
3. 在对话中用技能名或 `@` 引用启用。

## 建议联用顺序

先跑「深化改题四问」收紧题目 → 再跑「闭环研发四阶段」落地。
