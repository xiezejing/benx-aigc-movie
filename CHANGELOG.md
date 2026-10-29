# 变更日志

本文件记录 `benx-aigc-movie` Skill 的创作与迭代过程。格式参考 [Keep a Changelog](https://keepachangelog.com/zh-CN/1.1.0/)，版本号遵循 [语义化版本](https://semver.org/lang/zh-CN/)。

版本号含义：
- **MAJOR** —— 规则结构或核心定位不兼容变更。
- **MINOR** —— 新增模板、流程、参考资料等能力。
- **PATCH** —— 措辞、错别字、路径修正与内容补全。

源流标记沿用 `SKILL.md`：【教程提炼】/【本 Skill 扩展】/【用户原创 · benx】。新增模块必须在条目中标注来源归属。

## [Unreleased]

### 计划中
- （暂无）

## [0.9.0] - 2026-10-29

### 新增
- `prompts/character-look-reference.md`：通用 AIGC 角色定妆照模板，覆盖人物、动物、生物、机器人与道具；由用户原创《主提示词｜电影级写实人物定妆》提炼，并做跨主体扩展【用户原创 · benx；AI 协助整理与扩展】。
- `prompts/character-visual-asset-sheet.md`：参考定妆图生成角色多视角视觉资产（默认横版 3:2，左侧三幅身体：正面／角色自身左侧／背面，右侧两幅头部：正面／角色自身左侧）【用户原创 · benx；AI 协助整理与扩展】。

### 更新
- `SKILL.md`：调用路径与模板索引补充两条角色资产入口；源流标记新增【用户原创 · benx】与【用户原创 · benx：多视角视觉资产】两段说明。
- `prompts/P01-P06-visual-story.md`：P03 增加「定妆照专项补充」交叉引用；P04 增加「五视图专项补充」，明确五视图需求优先使用资产表模板而非四宫格。
- `references/task-router.md`：新增两行路由（单张定妆／外观定型、定妆图转五视图资产表）。

### 备注
- 本次内容与已安装副本（`~/.config/magpie/library/skills/benx-aigc-movie`）对齐，工作区此前落后于安装副本。

## [0.8.0] - 2026-10-28

### 新增
- `LICENSE`：MIT 许可证。

## [0.7.2] - 2026-10-28

### 新增
- `workflows/zero-to-film.md`：从零到成片的零基础流程（创意 → 美术 → 剧本 → 调度 → CLIP → 生成 → 剪辑 → 复盘）。

## [0.7.1] - 2026-10-28

### 新增
- `workflows/diagnose.md`：生成结果不理想时的诊断与最小改动修复流程。

## [0.7.0] - 2026-10-28

### 新增
- `workflows/asset-first.md`：已有剧本或图片时的资产盘点与缺口检查流程。

## [0.6.2] - 2026-10-28

### 新增
- `references/visual-critique.md`：视觉鉴赏框架，用于看图／看片时判断画面问题。

## [0.6.1] - 2026-10-28

### 新增
- `references/task-router.md`：按需求类型路由到 P01–P12 的任务索引。

## [0.6.0] - 2026-10-28

### 新增
- `references/beginner-coach.md`：新手术语教学与专业表达转换规则。

## [0.5.0] - 2026-10-28

### 新增
- `prompts/P11-P12-continuity-review.md`：P11 连续性核对、P12 质量诊断与定向修复。

## [0.4.0] - 2026-10-28

### 新增
- `prompts/P07-P10-shots-clip.md`：P07 单镜调度七问、P08 调度整理检查、P09 调度转 CLIP、P10 最终 CLIP 视频提示词。

## [0.3.0] - 2026-10-28

### 新增
- `prompts/P01-P06-visual-story.md`：P01 美术风格探索、P02 场景参考图、P03 角色设定、P04 角色四宫格、P05 关键道具三视图、P06 剧本与情绪弧线。

## [0.2.0] - 2026-10-27

### 新增
- `SKILL.md`：主规则、工作原则、每轮操作协议与按需加载入口。
- `examples/novice-example.md`：完整小白引导案例。

## [0.1.0] - 2026-10-27

### 新增
- 仓库初始化：Skill 目录结构与基础说明。

