# Awesome MiniMax H3 Prompts

[![画廊](https://img.shields.io/badge/224%20条提示词%20·%20带视频-F5FF60?labelColor=111)](https://tryminimax.asia/zh/minimax-h3-prompts)
[![统一 API](https://img.shields.io/badge/一个%20API-85%2B%20模型-3158E8)](https://tryminimax.asia/zh/models)
[![价格](https://img.shields.io/badge/图片%20%240.01%20起%20%C2%B7%20视频%20%240.044%2F秒起-1f9e5f)](https://tryminimax.asia/zh/pricing)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)

**MiniMax H3**（海螺 3.0）提示词库。每条提示词都配着它真正生成出来的那段视频，
署名作者，链回原帖。

**[English](./README.md)** · **[看全部 222 条](./prompts/GALLERY.zh-CN.md)** ·
**[到画廊里带声音看](https://tryminimax.asia/zh/minimax-h3-prompts)**

---

## MiniMax H3 强在哪

2026 年 7 月 31 日发布。原生 **2560×1440 / 24fps**，4–15 秒，**音频和画面同一次生成** ——
环境声、动作音、台词都落在你指定的那一帧上，不是事后配的背景音乐。

**Omni Reference** 一次请求能吃 **9 张参考图 + 3 段参考视频 + 3 段参考音频**。库里有位作者
用 8 张图（6 个角色 + 1 张场景 + 1 张 UI）驱动出一整段看着像真能玩的游戏画面，H3 把每个角色的
身份、界面元素和动作逻辑在整段里都守住了。

它也吃得下超长提示词。库里最长的一条 **6602 字符**：逐秒分镜、屏幕上一字不差的文字、
人体结构锁定、镜头焦段，外加一张精确到帧的音效表。此外还有首尾帧控制、动作迁移、生成式编辑。

---

---

## 两类提示词，分得很清楚

| | 数量 | 是什么 |
|---|---|---|
| **作者原文** | 150 | 作者自己公开的。署名、链回原帖。全文放在我们的[画廊](https://tryminimax.asia/zh/minimax-h3-prompts)里，这个仓库只做索引 —— 因为它不归我们所有。 |
| **AI 反推** | 72 | 作者没公开提示词的片子，我们抽 8 帧交给视觉模型，写出最可能复现这段画面的提示词。**MIT，全文就在这个仓库里。** |

反推描述的是**成片**，恢复不了负面约束、准确台词和参考图工作流 —— 它是写法参考，不是作者的原稿，
每一条都标了 `AI 反推`。

**从哪找到的。** 135 条是我们自己在 X 上采的；另外 87 条是通过
[awesome-minimax-h3-prompts](https://github.com/BeatAPI/awesome-minimax-h3-prompts)
找到的，他们先把这些整理了出来，这些条目的来源行上都带一个 `经` 的署名。
不论哪种，提示词都归作者本人 —— 整理是叠在作者劳动之上的第二份劳动，两边都点名。
所有视频都是我们自己从原帖重新采的，不占用别人的 CDN。

**语言。** 提示词按作者写它时用的语言原样保存：英文 198 条、中文 13 条、日文 11 条。
我们不做翻译 —— 翻译过的提示词跑出来不是同一段片子。

作者们：想撤下某一条，开个 issue 就行。

---

## 精选

作者原文里最长的 12 条。**[看全部 222 条 →](./prompts/GALLERY.zh-CN.md)**

### 1. 混凝土广场的滑板落地

<a href="https://tryminimax.asia/minimax-h3-prompts#prompt-cmsboram6001z04kzkda7f0i4"><img src="https://raw.githubusercontent.com/xianyu110/awesome-minimax-h3-prompts/main/assets/previews/cmsboram6001z04kzkda7f0i4.webp" alt="混凝土广场的滑板落地" width="700" /></a>

<strong>提示词</strong> — プロンプト SCENE CONTEXT Late afternoon, empty two-level concrete plaza. A young woman skateboarder rolls along the raised upper deck to its edge and launches off the TOP of a 10-step stair set with a kick…

[**读完整提示词 →**](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsboram6001z04kzkda7f0i4) （7004 字符，作者原文）

[![播放视频](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsboram6001z04kzkda7f0i4)

**来源:** [@eijo_AIart](https://x.com/eijo_AIart/status/2082684613475082714) · 15s · 16:9 · 运镜 · 经 [awesome-minimax-h3-prompts](https://github.com/BeatAPI/awesome-minimax-h3-prompts)

---
### 2. Y2K K-Pop 糖果字体 MV

<a href="https://tryminimax.asia/minimax-h3-prompts#prompt-cmsbor5eu001q04kz1zhzjtoi"><img src="https://raw.githubusercontent.com/xianyu110/awesome-minimax-h3-prompts/main/assets/previews/cmsbor5eu001q04kz1zhzjtoi.webp" alt="Y2K K-Pop 糖果字体 MV" width="700" /></a>

<strong>提示词</strong> — Soft cute Y2K crush K-pop girl group rap MV. High fashion performance film mixed with inflated 3D candy typography graphic system. Three female idols wearing pink, blue and purple luxury Y2K stage out…

[**读完整提示词 →**](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsbor5eu001q04kz1zhzjtoi) （6989 字符，作者原文）

[![播放视频](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsbor5eu001q04kz1zhzjtoi)

**来源:** [@LeoCreaIA](https://x.com/LeoCreaIA/status/2083240416166748313) · 15s · 16:9 · 特效与转场 · 经 [awesome-minimax-h3-prompts](https://github.com/BeatAPI/awesome-minimax-h3-prompts)

---
### 3. 赛博朋克冰蓝角色觉醒

<a href="https://tryminimax.asia/minimax-h3-prompts#prompt-cmsboqaem000j04kz9ysbqup1"><img src="https://raw.githubusercontent.com/xianyu110/awesome-minimax-h3-prompts/main/assets/previews/cmsboqaem000j04kz9ysbqup1.webp" alt="赛博朋克冰蓝角色觉醒" width="700" /></a>

<strong>提示词</strong> — Use the uploaded image as the exact source image and first frame. Preserve the original character design, composition, face, pale skin, glowing icy blue eyes, braided black hair, cybernetic head impla…

[**读完整提示词 →**](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsboqaem000j04kz9ysbqup1) （6975 字符，作者原文）

[![播放视频](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsboqaem000j04kz9ysbqup1)

**来源:** [@ainextastro](https://x.com/ainextastro/status/2082830892209221921) · 15s · 16:9 · 人物表演 · 经 [awesome-minimax-h3-prompts](https://github.com/BeatAPI/awesome-minimax-h3-prompts)

---
### 4. 断刃重铸的无限循环

<a href="https://tryminimax.asia/minimax-h3-prompts#prompt-cmsb2bmyp00010akoxbpa7b9m"><img src="https://raw.githubusercontent.com/xianyu110/awesome-minimax-h3-prompts/main/assets/previews/cmsb2bmyp00010akoxbpa7b9m.webp" alt="断刃重铸的无限循环" width="700" /></a>

<strong>提示词</strong> — @image1 15s | 16:9 | 1440p | 24fps | SEAMLESS LOOP [LOCK] Render exactly as @image1. Do not alter hair, bangs, eye color, coat silhouette, sash, hilt ornament, or blade proportion. [LOOP] A perfect cy…

[**读完整提示词 →**](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsb2bmyp00010akoxbpa7b9m) （6602 字符，作者原文）

[![播放视频](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsb2bmyp00010akoxbpa7b9m)

**来源:** [@Cia0_exe](https://x.com/Cia0_exe/status/2082774526098874724) · 15s · 16:9 · 动画与二次元

---
### 5. 沙漠越野车追击战

<a href="https://tryminimax.asia/minimax-h3-prompts#prompt-cmsboq2ab000904kzun2m0c72"><img src="https://raw.githubusercontent.com/xianyu110/awesome-minimax-h3-prompts/main/assets/previews/cmsboq2ab000904kzun2m0c72.webp" alt="沙漠越野车追击战" width="700" /></a>

<strong>提示词</strong> — Create a 15-second, 16:9 photoreal cinematic action sequence with native stereo audio. Treat the five images as coordinated multimodal references for identity, vehicle design, environment, performance…

[**读完整提示词 →**](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsboq2ab000904kzun2m0c72) （6412 字符，作者原文）

[![播放视频](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsboq2ab000904kzun2m0c72)

**来源:** [@beginnersblog1](https://x.com/beginnersblog1/status/2083039412506743096) · 15s · 21:9 · 电影感 · 经 [awesome-minimax-h3-prompts](https://github.com/BeatAPI/awesome-minimax-h3-prompts)

---
### 6. 蒙娜丽莎游戏选角与换装

<a href="https://tryminimax.asia/minimax-h3-prompts#prompt-cmsb20d0h000004l9pu7c8r0i"><img src="https://raw.githubusercontent.com/xianyu110/awesome-minimax-h3-prompts/main/assets/previews/cmsb20d0h000004l9pu7c8r0i.webp" alt="蒙娜丽莎游戏选角与换装" width="700" /></a>

<strong>提示词</strong> — Use @Image 1 for the character and the menu interface style. Use @Image 2 for the game world and the in-game HUD style. Use @Image 3 as the source for every item thumbnail shown inside the panels — it…

[**读完整提示词 →**](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsb20d0h000004l9pu7c8r0i) （6301 字符，作者原文）

[![播放视频](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsb20d0h000004l9pu7c8r0i)

**来源:** [@ivanka_humeniuk](https://x.com/ivanka_humeniuk/status/2083555429758464203) · 15s · 16:9 · 特效与转场

---
### 7. 沙漠对峙 · 15 秒一镜到底

<a href="https://tryminimax.asia/minimax-h3-prompts#prompt-cmsabne9r000204la2ozvzj4z"><img src="https://raw.githubusercontent.com/xianyu110/awesome-minimax-h3-prompts/main/assets/previews/cmsabne9r000204la2ozvzj4z.webp" alt="沙漠对峙 · 15 秒一镜到底" width="700" /></a>

<strong>提示词</strong> — SCENE CONTEXT A middle-aged man stands in the middle of a dirt road in open desert and holds a pistol level at the person filming him. He gives an instruction, is answered by name, and warns them not …

[**读完整提示词 →**](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsabne9r000204la2ozvzj4z) （6078 字符，作者原文）

[![播放视频](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsabne9r000204la2ozvzj4z)

**来源:** [@maxescu](https://x.com/maxescu/status/2082563241062875568) · 15s · 16:9 · 对白与音效

---
### 8. 无缝循环：刀刃重组

<a href="https://tryminimax.asia/minimax-h3-prompts#prompt-cmsboq6wq000e04kz9dl0yo7y"><img src="https://raw.githubusercontent.com/xianyu110/awesome-minimax-h3-prompts/main/assets/previews/cmsboq6wq000e04kz9dl0yo7y.webp" alt="无缝循环：刀刃重组" width="700" /></a>

<strong>提示词</strong> — @Image1 15s | 16:9 | 1440p | 24fps | PERFECT SEAMLESS LOOP [REFERENCE LOCK] Render exactly as @image1. Preserve the character exactly as shown. Do not redesign, reinterpret, or modify any aspect of he…

[**读完整提示词 →**](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsboq6wq000e04kz9dl0yo7y) （5826 字符，作者原文）

[![播放视频](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsboq6wq000e04kz9dl0yo7y)

**来源:** [@ogbenniasamuel2](https://x.com/ogbenniasamuel2/status/2082934406910513162) · 15s · 16:9 · 特效与转场 · 经 [awesome-minimax-h3-prompts](https://github.com/BeatAPI/awesome-minimax-h3-prompts)

---
### 9. KALDR 冷感香水多参考图广告

<a href="https://tryminimax.asia/minimax-h3-prompts#prompt-cmsboqtzf001b04kzcll6fe7k"><img src="https://raw.githubusercontent.com/xianyu110/awesome-minimax-h3-prompts/main/assets/previews/cmsboqtzf001b04kzcll6fe7k.webp" alt="KALDR 冷感香水多参考图广告" width="700" /></a>

<strong>提示词</strong> — REFERENCE USAGE: Image 1 — the KALDR bottle. Preserve the smoked charcoal glass, bevelled edges, pale blue liquid, brushed gunmetal cap and the etched silver KALDR mark exactly. Image 2 — the closing …

[**读完整提示词 →**](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsboqtzf001b04kzcll6fe7k) （5465 字符，作者原文）

[![播放视频](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsboqtzf001b04kzcll6fe7k)

**来源:** [@abulu8](https://x.com/abulu8/status/2082919486399943073) · 15s · 21:9 · 产品与广告 · 经 [awesome-minimax-h3-prompts](https://github.com/BeatAPI/awesome-minimax-h3-prompts)

---
### 10. 魔幻游戏实机演示

<a href="https://tryminimax.asia/minimax-h3-prompts#prompt-cmsb4xgx4000d04l10xty7iwb"><img src="https://raw.githubusercontent.com/xianyu110/awesome-minimax-h3-prompts/main/assets/previews/cmsb4xgx4000d04l10xty7iwb.webp" alt="魔幻游戏实机演示" width="700" /></a>

<strong>提示词</strong> — [FORMAT] Exactly 15 seconds, horizontal 16:9, photorealistic AAA fantasy MMORPG gameplay reveal with native synchronized game audio and music. [OMNI REFERENCES] [Image1] = Kael Ardyn, the exact playab…

[**读完整提示词 →**](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsb4xgx4000d04l10xty7iwb) （4443 字符，作者原文）

[![播放视频](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsb4xgx4000d04l10xty7iwb)

**来源:** [@PromptSin](https://x.com/PromptSin/status/2083085328710238400) · 15s · 16:9 · 参考图与一致性

---
### 11. 情景喜剧游戏秀选择

<a href="https://tryminimax.asia/minimax-h3-prompts#prompt-cmsb47v5o000304l1j6q1veqt"><img src="https://raw.githubusercontent.com/xianyu110/awesome-minimax-h3-prompts/main/assets/previews/cmsb47v5o000304l1j6q1veqt.webp" alt="情景喜剧游戏秀选择" width="700" /></a>

<strong>提示词</strong> — [FORMAT] Exactly 15 seconds, horizontal 16:9, photorealistic multi-camera television sitcom with native synchronized dialogue, audience reactions, SFX and music. [OMNI REFERENCES — [Image1] [Image2] […

[**读完整提示词 →**](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsb47v5o000304l1j6q1veqt) （4399 字符，作者原文）

[![播放视频](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsb47v5o000304l1j6q1veqt)

**来源:** [@PromptSin](https://x.com/PromptSin/status/2083130683183255894) · 15s · 16:9 · 人物表演

---
### 12. 神圣升华网页动效

<a href="https://tryminimax.asia/minimax-h3-prompts#prompt-cmsb2guus00000ajfae9hxtax"><img src="https://raw.githubusercontent.com/xianyu110/awesome-minimax-h3-prompts/main/assets/previews/cmsb2guus00000ajfae9hxtax.webp" alt="神圣升华网页动效" width="700" /></a>

<strong>提示词</strong> — 15秒 | 16:9 | 1440p | 24fps | 无缝循环 | 网页首屏动画 [人物锁定 · @image1] 完全按照该参考图呈现，不进行任何重新设计。金色卷发、闭合的双眼、仰起的面容与安详神情；象牙色垂坠长袍；左右两枚金色玫瑰花章肩甲，含中心宝石与放射浮雕；金丝胸饰、十字垂饰、多层珠链；水晶巨剑，含金色巴洛克护手与剑柄头、缠绕剑柄，双臂高举过头横持，金色火柱自上贯入；白色大理石圆台；下…

[**读完整提示词 →**](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsb2guus00000ajfae9hxtax) （4269 字符，作者原文）

[![播放视频](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsb2guus00000ajfae9hxtax)

**来源:** [@Cia0_exe](https://x.com/Cia0_exe/status/2083090068378616089) · 15s · 16:9 · 参考图与一致性

---
---

> **喜欢这些片子？** 同样的提示词你可以自己跑 ——
> **[MiniMax H3 已上线，$0.145/秒](https://tryminimax.asia/zh/models/minimax-h3)**，
> 和 [GPT Image 2、Nano Banana Pro、Seedance 2.0、Kling V3 等 85+ 个模型](https://tryminimax.asia/zh/models)
> 共用一个 key，都在 **[tryminimax.asia](https://tryminimax.asia)**。注册送 $1。

---

## 仓库结构

| 路径 | 内容 |
|---|---|
| [`prompts/GALLERY.zh-CN.md`](./prompts/GALLERY.zh-CN.md) | 全部 222 条：缩略图 + 提示词 + 来源，也就是上面精选段的完整版 |
| [`prompts/GALLERY.md`](./prompts/GALLERY.md) | 同一份画廊的英文版 |
| [`prompts/<分类>/`](./prompts) | 72 条 AI 反推提示词的单文件版本，按用途分目录，方便 grep，MIT |

---

## MiniMax H3 提示词怎么写

下面这几条是把库里每条提示词读完之后总结的。和写图像提示词最大的区别是：你现在要指挥的是
**时间**、**镜头**和**声音**，不只是一张画面。

1. **一条提示词只讲一个动作。** 片长 4–15 秒，一个动作讲清楚，胜过塞三个。
2. **把运镜写出来。** 推、拉、跟、手持轻晃、无人机下降。不写就是一个死机位。
3. **把声音写出来。** H3 生成同步原生音频 —— 环境声、动作音，甚至一句台词，都点名。
4. **先定光和色。** 一句关于光线和色调的话，决定整段片子的观感。
5. **给它节奏。** 慢动作、正常速度、延时；以及那个"重拍"落在第几秒。
6. **参考图管身份，提示词管动作。** 最多 9 张参考图锁住脸、服装或产品；提示词负责说发生了什么。
7. **拆成带时间码的分镜。** 库里最强的那几条读起来就是一张分镜表：`0-4s — …`、`4-8s — …`。
8. **写清楚你不要什么。** 几乎所有高质量提示词的末尾都有负面约束：不要多手多脚、不要屏幕文字、不要镜头抖动。

---

## 参与

看到不错的 H3 片子？开个 issue 贴原帖链接。作者公开了提示词，我们就署名收录；
没公开的，我们可以反推并明确标注。

## 许可

[MIT](./LICENSE) —— 覆盖 AI 反推的提示词和我们自己写的所有内容，
**不覆盖**作者原文提示词：那些归作者本人所有，我们只做链接，不做再授权。
