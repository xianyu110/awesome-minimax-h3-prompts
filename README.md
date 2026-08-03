# Awesome MiniMax H3 Prompts

[![Gallery](https://img.shields.io/badge/Browse%20224%20prompts%20with%20video-F5FF60?labelColor=111)](https://tryminimax.asia/minimax-h3-prompts)
[![One API](https://img.shields.io/badge/One%20API-85%2B%20models-3158E8)](https://tryminimax.asia/models)
[![Pricing](https://img.shields.io/badge/Images%20from%20%240.01%20%C2%B7%20Video%20from%20%240.044%2Fs-1f9e5f)](https://tryminimax.asia/pricing)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)

Curated **MiniMax H3** (Hailuo 3.0) video prompts — every one shown next to the clip it
actually produced, with credit and a link to the creator's original post.

**[中文说明](./README.zh-CN.md)** · **[Browse all 222 prompts](./prompts/GALLERY.md)** ·
**[Watch them with sound](https://tryminimax.asia/minimax-h3-prompts)**

---

## What MiniMax H3 does

Released 31 July 2026. Native **2560×1440 at 24fps**, 4–15 second clips, with **audio
generated in the same pass** — ambience, foley and dialogue landing on the frame you
specify, not a soundtrack added afterwards.

**Omni Reference** takes up to **9 reference images + 3 video clips + 3 audio clips** in a
single request. One creator in this library drove an entire playable-looking game sequence
from 8 images — 6 characters, 1 arena, 1 UI — and H3 held every identity, the interface and
the action logic coherent across the whole clip.

It also follows very long prompts. The longest in this library is **6,602 characters**: a
per-second shot breakdown, exact on-screen text, anatomy locks, focal lengths and a
frame-accurate audio cue sheet. Plus first/last-frame control, motion transfer and
generative editing.

---

---

## Two kinds of prompt, kept clearly apart

| | Count | What it is |
|---|---|---|
| **Author-written** | 150 | Published by the creator. Credited, linked to the original post. Full text lives in our [gallery](https://tryminimax.asia/minimax-h3-prompts) — we index it here rather than copy it, because we do not own it. |
| **Reconstructed** | 72 | For clips whose creator never published a prompt, we sample 8 frames, hand them to a vision model, and write the prompt that would most plausibly reproduce the clip. **MIT, full text in this repo.** |

A reconstruction describes the *output*. It cannot recover negative constraints, exact
dialogue or reference-image workflows — it is a writing reference, not the creator's
prompt, and every one is labelled `reconstructed`.

**Where we found them.** 135 entries we collected ourselves from X. The other 87 we found
through [awesome-minimax-h3-prompts](https://github.com/BeatAPI/awesome-minimax-h3-prompts),
whose maintainers indexed them first; each of those carries a `via` credit on its Source
line. The prompts belong to the creators either way — a collection is a second piece of
work on top of theirs, and both get named. Every video in this repo we re-collected from
the original post ourselves, so nothing here leans on anyone else's CDN.

**Languages.** Prompts are stored in the language their author wrote them in — 198 English,
13 Chinese, 11 Japanese. We do not translate them: a translated prompt does not generate
the same clip.

Creators: if you would like an entry removed, open an issue.

---

## Featured prompts

The twelve longest author-written prompts in the library. **[See all 222 →](./prompts/GALLERY.md)**

### 1. Concrete-Plaza Kickflip Drop

<a href="https://tryminimax.asia/minimax-h3-prompts#prompt-cmsboram6001z04kzkda7f0i4"><img src="https://raw.githubusercontent.com/xianyu110/awesome-minimax-h3-prompts/main/assets/previews/cmsboram6001z04kzkda7f0i4.webp" alt="Concrete-Plaza Kickflip Drop" width="700" /></a>

<strong>Prompt</strong> — プロンプト SCENE CONTEXT Late afternoon, empty two-level concrete plaza. A young woman skateboarder rolls along the raised upper deck to its edge and launches off the TOP of a 10-step stair set with a kick…

[**Read the full prompt →**](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsboram6001z04kzkda7f0i4) (7004 chars, author's own)

[![Play video](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsboram6001z04kzkda7f0i4)

**Source:** [@eijo_AIart](https://x.com/eijo_AIart/status/2082684613475082714) · 15s · 16:9 · Camera Motion · via [awesome-minimax-h3-prompts](https://github.com/BeatAPI/awesome-minimax-h3-prompts)

---
### 2. Y2K K-Pop Candy Typography Music Video

<a href="https://tryminimax.asia/minimax-h3-prompts#prompt-cmsbor5eu001q04kz1zhzjtoi"><img src="https://raw.githubusercontent.com/xianyu110/awesome-minimax-h3-prompts/main/assets/previews/cmsbor5eu001q04kz1zhzjtoi.webp" alt="Y2K K-Pop Candy Typography Music Video" width="700" /></a>

<strong>Prompt</strong> — Soft cute Y2K crush K-pop girl group rap MV. High fashion performance film mixed with inflated 3D candy typography graphic system. Three female idols wearing pink, blue and purple luxury Y2K stage out…

[**Read the full prompt →**](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsbor5eu001q04kz1zhzjtoi) (6989 chars, author's own)

[![Play video](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsbor5eu001q04kz1zhzjtoi)

**Source:** [@LeoCreaIA](https://x.com/LeoCreaIA/status/2083240416166748313) · 15s · 16:9 · VFX & Transitions · via [awesome-minimax-h3-prompts](https://github.com/BeatAPI/awesome-minimax-h3-prompts)

---
### 3. Cyberpunk Ice-Blue Character Awakening

<a href="https://tryminimax.asia/minimax-h3-prompts#prompt-cmsboqaem000j04kz9ysbqup1"><img src="https://raw.githubusercontent.com/xianyu110/awesome-minimax-h3-prompts/main/assets/previews/cmsboqaem000j04kz9ysbqup1.webp" alt="Cyberpunk Ice-Blue Character Awakening" width="700" /></a>

<strong>Prompt</strong> — Use the uploaded image as the exact source image and first frame. Preserve the original character design, composition, face, pale skin, glowing icy blue eyes, braided black hair, cybernetic head impla…

[**Read the full prompt →**](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsboqaem000j04kz9ysbqup1) (6975 chars, author's own)

[![Play video](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsboqaem000j04kz9ysbqup1)

**Source:** [@ainextastro](https://x.com/ainextastro/status/2082830892209221921) · 15s · 16:9 · Character & Performance · via [awesome-minimax-h3-prompts](https://github.com/BeatAPI/awesome-minimax-h3-prompts)

---
### 4. Infinite Cycle of the Blade

<a href="https://tryminimax.asia/minimax-h3-prompts#prompt-cmsb2bmyp00010akoxbpa7b9m"><img src="https://raw.githubusercontent.com/xianyu110/awesome-minimax-h3-prompts/main/assets/previews/cmsb2bmyp00010akoxbpa7b9m.webp" alt="Infinite Cycle of the Blade" width="700" /></a>

<strong>Prompt</strong> — @image1 15s | 16:9 | 1440p | 24fps | SEAMLESS LOOP [LOCK] Render exactly as @image1. Do not alter hair, bangs, eye color, coat silhouette, sash, hilt ornament, or blade proportion. [LOOP] A perfect cy…

[**Read the full prompt →**](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsb2bmyp00010akoxbpa7b9m) (6602 chars, author's own)

[![Play video](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsb2bmyp00010akoxbpa7b9m)

**Source:** [@Cia0_exe](https://x.com/Cia0_exe/status/2082774526098874724) · 15s · 16:9 · Animation & Anime

---
### 5. Desert Buggy Combat Chase

<a href="https://tryminimax.asia/minimax-h3-prompts#prompt-cmsboq2ab000904kzun2m0c72"><img src="https://raw.githubusercontent.com/xianyu110/awesome-minimax-h3-prompts/main/assets/previews/cmsboq2ab000904kzun2m0c72.webp" alt="Desert Buggy Combat Chase" width="700" /></a>

<strong>Prompt</strong> — Create a 15-second, 16:9 photoreal cinematic action sequence with native stereo audio. Treat the five images as coordinated multimodal references for identity, vehicle design, environment, performance…

[**Read the full prompt →**](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsboq2ab000904kzun2m0c72) (6412 chars, author's own)

[![Play video](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsboq2ab000904kzun2m0c72)

**Source:** [@beginnersblog1](https://x.com/beginnersblog1/status/2083039412506743096) · 15s · 21:9 · Cinematic · via [awesome-minimax-h3-prompts](https://github.com/BeatAPI/awesome-minimax-h3-prompts)

---
### 6. Mona Lisa Character Selection Screen

<a href="https://tryminimax.asia/minimax-h3-prompts#prompt-cmsb20d0h000004l9pu7c8r0i"><img src="https://raw.githubusercontent.com/xianyu110/awesome-minimax-h3-prompts/main/assets/previews/cmsb20d0h000004l9pu7c8r0i.webp" alt="Mona Lisa Character Selection Screen" width="700" /></a>

<strong>Prompt</strong> — Use @Image 1 for the character and the menu interface style. Use @Image 2 for the game world and the in-game HUD style. Use @Image 3 as the source for every item thumbnail shown inside the panels — it…

[**Read the full prompt →**](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsb20d0h000004l9pu7c8r0i) (6301 chars, author's own)

[![Play video](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsb20d0h000004l9pu7c8r0i)

**Source:** [@ivanka_humeniuk](https://x.com/ivanka_humeniuk/status/2083555429758464203) · 15s · 16:9 · VFX & Transitions

---
### 7. Desert Standoff — 15s single take

<a href="https://tryminimax.asia/minimax-h3-prompts#prompt-cmsabne9r000204la2ozvzj4z"><img src="https://raw.githubusercontent.com/xianyu110/awesome-minimax-h3-prompts/main/assets/previews/cmsabne9r000204la2ozvzj4z.webp" alt="Desert Standoff — 15s single take" width="700" /></a>

<strong>Prompt</strong> — SCENE CONTEXT A middle-aged man stands in the middle of a dirt road in open desert and holds a pistol level at the person filming him. He gives an instruction, is answered by name, and warns them not …

[**Read the full prompt →**](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsabne9r000204la2ozvzj4z) (6078 chars, author's own)

[![Play video](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsabne9r000204la2ozvzj4z)

**Source:** [@maxescu](https://x.com/maxescu/status/2082563241062875568) · 15s · 16:9 · Dialogue & Sound

---
### 8. Seamless-loop cinematic warrior blade reconstruction

<a href="https://tryminimax.asia/minimax-h3-prompts#prompt-cmsboq6wq000e04kz9dl0yo7y"><img src="https://raw.githubusercontent.com/xianyu110/awesome-minimax-h3-prompts/main/assets/previews/cmsboq6wq000e04kz9dl0yo7y.webp" alt="Seamless-loop cinematic warrior blade reconstruction" width="700" /></a>

<strong>Prompt</strong> — @Image1 15s | 16:9 | 1440p | 24fps | PERFECT SEAMLESS LOOP [REFERENCE LOCK] Render exactly as @image1. Preserve the character exactly as shown. Do not redesign, reinterpret, or modify any aspect of he…

[**Read the full prompt →**](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsboq6wq000e04kz9dl0yo7y) (5826 chars, author's own)

[![Play video](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsboq6wq000e04kz9dl0yo7y)

**Source:** [@ogbenniasamuel2](https://x.com/ogbenniasamuel2/status/2082934406910513162) · 15s · 16:9 · VFX & Transitions · via [awesome-minimax-h3-prompts](https://github.com/BeatAPI/awesome-minimax-h3-prompts)

---
### 9. KALDR cold perfume commercial multi-reference

<a href="https://tryminimax.asia/minimax-h3-prompts#prompt-cmsboqtzf001b04kzcll6fe7k"><img src="https://raw.githubusercontent.com/xianyu110/awesome-minimax-h3-prompts/main/assets/previews/cmsboqtzf001b04kzcll6fe7k.webp" alt="KALDR cold perfume commercial multi-reference" width="700" /></a>

<strong>Prompt</strong> — REFERENCE USAGE: Image 1 — the KALDR bottle. Preserve the smoked charcoal glass, bevelled edges, pale blue liquid, brushed gunmetal cap and the etched silver KALDR mark exactly. Image 2 — the closing …

[**Read the full prompt →**](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsboqtzf001b04kzcll6fe7k) (5465 chars, author's own)

[![Play video](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsboqtzf001b04kzcll6fe7k)

**Source:** [@abulu8](https://x.com/abulu8/status/2082919486399943073) · 15s · 21:9 · Product & Ads · via [awesome-minimax-h3-prompts](https://github.com/BeatAPI/awesome-minimax-h3-prompts)

---
### 10. Fantasy MMORPG Gameplay Reveal

<a href="https://tryminimax.asia/minimax-h3-prompts#prompt-cmsb4xgx4000d04l10xty7iwb"><img src="https://raw.githubusercontent.com/xianyu110/awesome-minimax-h3-prompts/main/assets/previews/cmsb4xgx4000d04l10xty7iwb.webp" alt="Fantasy MMORPG Gameplay Reveal" width="700" /></a>

<strong>Prompt</strong> — [FORMAT] Exactly 15 seconds, horizontal 16:9, photorealistic AAA fantasy MMORPG gameplay reveal with native synchronized game audio and music. [OMNI REFERENCES] [Image1] = Kael Ardyn, the exact playab…

[**Read the full prompt →**](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsb4xgx4000d04l10xty7iwb) (4443 chars, author's own)

[![Play video](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsb4xgx4000d04l10xty7iwb)

**Source:** [@PromptSin](https://x.com/PromptSin/status/2083085328710238400) · 15s · 16:9 · Reference & Consistency

---
### 11. Sitcom Game Show Choice

<a href="https://tryminimax.asia/minimax-h3-prompts#prompt-cmsb47v5o000304l1j6q1veqt"><img src="https://raw.githubusercontent.com/xianyu110/awesome-minimax-h3-prompts/main/assets/previews/cmsb47v5o000304l1j6q1veqt.webp" alt="Sitcom Game Show Choice" width="700" /></a>

<strong>Prompt</strong> — [FORMAT] Exactly 15 seconds, horizontal 16:9, photorealistic multi-camera television sitcom with native synchronized dialogue, audience reactions, SFX and music. [OMNI REFERENCES — [Image1] [Image2] […

[**Read the full prompt →**](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsb47v5o000304l1j6q1veqt) (4399 chars, author's own)

[![Play video](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsb47v5o000304l1j6q1veqt)

**Source:** [@PromptSin](https://x.com/PromptSin/status/2083130683183255894) · 15s · 16:9 · Character & Performance

---
### 12. Divine Ascension Web Interface

<a href="https://tryminimax.asia/minimax-h3-prompts#prompt-cmsb2guus00000ajfae9hxtax"><img src="https://raw.githubusercontent.com/xianyu110/awesome-minimax-h3-prompts/main/assets/previews/cmsb2guus00000ajfae9hxtax.webp" alt="Divine Ascension Web Interface" width="700" /></a>

<strong>Prompt</strong> — 15秒 | 16:9 | 1440p | 24fps | 无缝循环 | 网页首屏动画 [人物锁定 · @image1] 完全按照该参考图呈现，不进行任何重新设计。金色卷发、闭合的双眼、仰起的面容与安详神情；象牙色垂坠长袍；左右两枚金色玫瑰花章肩甲，含中心宝石与放射浮雕；金丝胸饰、十字垂饰、多层珠链；水晶巨剑，含金色巴洛克护手与剑柄头、缠绕剑柄，双臂高举过头横持，金色火柱自上贯入；白色大理石圆台；下…

[**Read the full prompt →**](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsb2guus00000ajfae9hxtax) (4269 chars, author's own)

[![Play video](https://img.shields.io/badge/PLAY_VIDEO-F5FF60?style=for-the-badge&labelColor=111)](https://tryminimax.asia/minimax-h3-prompts#prompt-cmsb2guus00000ajfae9hxtax)

**Source:** [@Cia0_exe](https://x.com/Cia0_exe/status/2083090068378616089) · 15s · 16:9 · Reference & Consistency

---
---

> **Liked these?** Run the same prompts yourself —
> **[MiniMax H3 is live at $0.145/s](https://tryminimax.asia/models/minimax-h3)**, alongside
> [GPT Image 2, Nano Banana Pro, Seedance 2.0, Kling V3 and 85+ more](https://tryminimax.asia/models)
> on one API key at **[tryminimax.asia](https://tryminimax.asia)**. $1 free to start.

---

## Repository layout

| Path | What is in it |
|---|---|
| [`prompts/GALLERY.md`](./prompts/GALLERY.md) | All 222 entries with thumbnail, prompt and source — the full version of the featured section above |
| [`prompts/GALLERY.zh-CN.md`](./prompts/GALLERY.zh-CN.md) | Same gallery in Chinese |
| [`prompts/<category>/`](./prompts) | The 72 reconstructed prompts as individual `.md` files, grouped by use case — grep-friendly, MIT |

---

## How to write a MiniMax H3 prompt

Distilled from reading every prompt in this library. The shift from image prompting is that
you now direct **time**, **camera** and **sound**, not just the frame.

1. **One action per prompt.** Clips are 4–15s. One clear beat beats three crammed ones.
2. **Spell out the camera move.** Dolly in, pull back, tracking, handheld drift, drone
   descent. Leave it out and you get a locked-off tripod.
3. **Write the sound.** H3 generates synced native audio — name the ambience, the action
   sound, even a line of dialogue.
4. **Set light and palette first.** One lighting/colour sentence decides the whole look.
5. **Give it timing.** Slow motion, real time, timelapse — and when the beat lands.
6. **References carry identity, the prompt carries action.** Up to 9 reference images hold
   the face, wardrobe or product; the prompt says what happens.
7. **Break it into timecoded shots.** The strongest prompts here read like a shot list:
   `0-4s — …`, `4-8s — …`.
8. **State what you do not want.** Almost every high-quality prompt ends with negative
   constraints: no extra limbs, no on-screen text, no camera shake.

---

## Contributing

Found a good H3 clip? Open an issue with the post link. If the creator published the prompt
we index it with credit; if not, we can reconstruct it and label it as such.

## Licence

[MIT](./LICENSE) — covers the reconstructed prompts and everything else we wrote. It does
**not** cover author-written prompts, which belong to their creators and are linked, not
relicensed.
