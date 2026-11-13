# AI for Classic Architects · letsrendering

For architects who keep practicing classical architecture, and for the tiny teams working beside them. This skill is shared as a practical companion for turning spatial ideas into clearer, reviewable renderings. Cheers.

献给坚持做古典建筑的建筑师伙伴们，也献给与你们并肩工作的超小型团队。希望这份技能能帮大家把空间想法推演清楚、画出来、再认真审看。Cheers。

## What it does / 能做什么

`letsrendering` guides architectural, landscape, and interior image work. For space design tasks it follows:

**Evidence and conditions → use and movement → layout → camera → section and perspective guide → reference roles → generation → review and local revision.**

**资料与条件 → 使用行为 → 内部布局 → 相机点 → 剖面与透视底稿 → 参考分工 → 生成 → 审图与局部修订。**

It does not require a full model for every small edit. When a reliable layout already exists, the assistant reuses it and revisits only what the requested change affects.

## Invoke / 调用

Use `letsrendering` or `letsrender` in a request where this skill is installed. They are skill-level recognition conventions, not product-registered commands. Asking for discussion or a prompt alone does not authorize image generation.

可以说“letsrendering，先写提示词，不出图”，也可以说“letsrender，沿用这张图的机位，只调整材料”。有明确出图授权且没有关键未决项时，助手可直接推进。

## Install / 安装

Copy this whole repository into a supported skills folder such as `~/.codex/skills/guided-environment-rendering/`. Keep `SKILL.md`, `agents/` and `references/` together. Refresh skill discovery or start a new session as required by your client.

## Read the skill

- [SKILL.md](SKILL.md): entry point and task routing.
- [Spatial reasoning](references/spatial_reasoning.md): use, layout, camera, section and perspective guide.
- [Alignment guide](references/alignment_guide.md): clarify the few decisions that matter.
- [Review guide](references/review_and_edit.md): compare output with geometry and the chosen parent image.

v04 · 2026-11-13 · [Changelog](CHANGELOG.md)

This public package contains the reusable skill and general instructions. It does not include project drawings, customer material, reference photos or personal installation records.

