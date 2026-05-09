# 星辉天使 / Xinghui Angel

## 中文介绍

星辉天使是一个 Codex 桌面宠物，形象来自“金翼觉醒天使战士”的视觉方向。它保留了巨大的金色羽翼、白金色尖锐铠甲、青蓝水晶冠饰、蓝色宝石和蓝色长剑，并把这些复杂特征压缩成适合桌面宠物使用的小型动画 spritesheet。

它的气质偏向神圣、锋利、战斗型，但在动画中保持了 chibi 化的比例和清晰轮廓，让每个动作在小尺寸下仍然容易识别。

## English Introduction

Xinghui Angel is a Codex desktop pet based on a golden-winged awakened angel warrior design. It keeps the dramatic silhouette of huge golden wings, sharp white-and-gold armor, cyan crystal accents, blue gems, and a blue sword, then compresses those details into a compact animated spritesheet.

The pet feels sacred, sharp, and battle-ready while keeping chibi proportions and readable silhouettes for small desktop-pet animation.

![Xinghui Angel contact sheet](assets/contact-sheet.png)

## Visual Identity / 视觉特征

- Huge golden feather wings curving around the body
- Cyan crystal crown crest above the helmet
- White-and-gold angular armor with blue gem accents
- Cyan-blue sword held close to the body
- Compact chibi sprite proportions for desktop-pet readability

中文要点：

- 巨大的金色羽翼包围身体
- 头顶有青蓝水晶冠饰
- 白金色角状头盔和铠甲，带蓝色宝石点缀
- 蓝色长剑贴近身体，方便动作帧保持可读
- 小型 chibi 比例，适合 Codex 桌面宠物显示

## Animation States / 动作状态

The finished spritesheet includes these Codex pet rows. / 最终 spritesheet 包含以下 Codex 宠物动作行：

| State / 状态 | Frames / 帧数 | Notes / 说明 |
| --- | ---: | --- |
| idle / 待机 | 6 | Calm breathing and small idle motion / 平静呼吸和轻微待机动作 |
| running-right / 向右移动 | 8 | Right-facing movement row / 向右移动动作 |
| running-left / 向左移动 | 8 | Generated separately instead of mirrored / 单独生成，没有直接镜像 |
| waving / 挥手 | 4 | Arm or hand wave without detached marks / 只用手部姿势表达挥手，没有额外符号 |
| jumping / 跳跃 | 5 | Vertical body motion without floor effects / 只用身体高度变化表现跳跃 |
| failed / 失败 | 8 | Failure reaction without red X marks or detached symbols / 失败反应，没有红叉或漂浮符号 |
| waiting / 等待 | 6 | Calm waiting loop / 平静等待循环 |
| running / 进行中 | 6 | Active in-progress loop, not literal foot-running / 表示任务进行中，不是横向奔跑 |
| review / 审查 | 6 | Focused review pose without extra UI props / 专注审查动作，不添加 UI 道具 |

## Assets / 资源

- [Contact sheet](assets/contact-sheet.png)
- [PNG spritesheet](assets/spritesheet.png)
- [WebP spritesheet](assets/spritesheet.webp)
- [Validation report](assets/validation.json)

## Validation / 验证结果

The final atlas was validated as. / 最终图集验证结果：

- Format: WebP / RGBA
- Size: 1536 x 1872
- Cell size: 192 x 208
- Errors: none
- Warnings: none

MP4 previews were skipped because the local environment did not have the video encoder available, but the spritesheet and QA contact sheet were generated successfully.

由于本地环境缺少视频编码工具，本次跳过了 MP4 预览，但 spritesheet 和 QA 动作总览图已经成功生成。

## Inspiration / 灵感来源

This pet was created from a user-selected awakened angel warrior image and adapted into a Codex-compatible animated pet. The GitHub collection keeps the pet assets and documentation together so future pets can be added using the same structure.

这个宠物由用户选择的觉醒天使战士形象改造成 Codex 可用动画宠物。这个仓库会把宠物资源和说明文档放在一起，方便之后继续添加更多宠物。
