<p align="center"><img src="./assets/banner.svg" alt="XXD Panel 053 project banner" width="1200"></p>

<div align="center">

# 🦁 XXD Panel 053

### Let the observed line stop at exactly the right moment

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Modes](https://img.shields.io/badge/Modes-4-EF805E?style=flat-square)](#)
[![Output](https://img.shields.io/badge/Output-PNG-4AA1AE?style=flat-square)](#)

<a href="README.md">简体中文</a> OBSERVATIONAL PEN · TRANSPARENT WASH · MUSICAL RHYTHM · NEAR-WHITE PAPER · ACTIVE WHITESPACE

Reduce the source to the few lines and transparent colour notes that keep its identity alive. The strongest contour or action becomes a visual motif, organised through repetition, variation, accent, pause, and a decisive stop.

## Why this Skill exists

The style is source-dependent, not a decorative preset. Its operative transformation is:

```text
lock identity, proportion, posture, direction, and relation → preserve three cues → select lines worth remembering → establish one visual motif → repeat, vary, accent, pause, and stop → add two to four source-derived washes → let near-white paper act as silence → let copy become a light echo
```

If an unrelated photograph could replace the source without materially changing the motif, recognition cues, line rhythm, colour notes, whitespace, and copy, the result does not belong to this Panel.

## The visual contract

- Preserve at least three source-specific cues across silhouette, proportion, posture, action, direction, structure, or relation.
- Use fine, loose, uneven pen lines with searching marks, corrections, sudden weight, and unfinished edges while keeping key proportions accurate.
- Turn one contour or action into a visual motif of repetition, variation, accent, and pause; let large blank areas function as active rests.
- Use only two to four source colours as transparent local washes; tune the near-white paper subtly to source temperature.
- “Natural transition” is visual continuity around the fixed midpoint, never a change to exact 50/50 paired geometry.

Aesthetic constraints and rejection rules live only in the [original source brief](references/053-source.md); the Skill and runtime adapter handle delivery variables only. [Skill workflow](SKILL.md) · [English runtime adapter](references/xxd-panel-053-prompt.en.md)

## Samples · From X

> [Xiaoxiaodong (@xiaoxiaodong01)](https://x.com/xiaoxiaodong01/status/2091521812878459186) · 23 August 2026<br>
> GPT2 × hand drawing × improvisation × aesthetic prompt × VOL.053

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091521812878459186"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 053 sample 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091521812878459186"><img src="./assets/examples/sample-02.jpg" alt="XXD Panel 053 sample 2"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091521812878459186"><img src="./assets/examples/sample-03.jpg" alt="XXD Panel 053 sample 3"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091521812878459186"><img src="./assets/examples/sample-04.jpg" alt="XXD Panel 053 sample 4"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2091521812878459186">View the original post and full prompt →</a></p>

These samples demonstrate the 053 aesthetic motive. Their subjects, composition, palette, copy, and earlier canvas ratio never become generation references or current defaults.

## The original brief is authoritative

`references/053-source.md` is this project's sole creative and aesthetic authority. The Skill no longer summarizes or expands it, and it does not impose a shared palette, colour plan, aesthetic motive, title, or microcopy package. GPT Image 2 follows that brief's own rules for colour, material, composition, whitespace, wording, and typography.

Mode and size completely replace the legacy 3:4 top-bottom delivery container without rewriting the transformation aesthetic. Each asset sends GPT Image 2 one selected mode's final contract instead of asking it to interpret four alternatives inside a generic template.

## Four combinable output modes

Select one or more of `top-bottom`, `left-right`, `design-only`, and `wallpaper-pack`. When several are selected, each is generated independently with its own prompt.

- `top-bottom`: one complete canvas with the reality view above and transformed design below.
- `left-right`: one complete canvas whose left-right structure runs from top edge to bottom edge, source left and design right. Typography stays inside that structure rather than creating a shared third footer; widths may be asymmetric.
- `design-only`: the source is a non-visible reference for identity, structure, colour logic, and facts; every visible element follows this Panel's transformation language.
- `wallpaper-pack`: each device receives an independently composed full-canvas transformed wallpaper, with no source-photo region.

There is no seam, midpoint-percentage, or pixel-coordinate test. Deterministic assembly is used only when the user explicitly requests exact panel geometry or pixel-identical source preservation.

Ordinary sizes are also multi-select: auto-fit, source aspect, 1:1, 3:4, 4:3, 4:5, 5:4, 2:3, 3:2, 9:16, 16:9, 21:9, 5:7, 7:5, or custom ratios/exact pixels. There is no silent default. Every distinct aspect is independently recomposed from the same verbatim source brief.

Wallpaper packs may be linked or independent. A linked pack creates one anchor image, then recomposes each remaining device from the original source plus that anchor; it never crops one image into four sizes.

Each invocation creates one task directory and writes every final PNG directly into it, with no source, mode, size, or device subfolders. Filenames carry those dimensions instead, for example `source-01-left-right-3x2-2160x1440.png` and `source-01-wallpaper-linked-phone-1440x3200.png`.

## Text modes

Before generation, resolve one of three choices:

1. **Model generates text from the original prompt**: the user supplies only the language or locale; GPT Image 2 follows the source brief's wording, amount, tone, and typography logic. Every word arises from the current image's content, atmosphere, or implied meaning, and anything presented as factual or documentary information must be grounded in supplied, visible, or verified facts.
2. **Use my exact text**: pass it verbatim, without rewriting, translating, or adding a title; typography still follows the source brief.
3. **No text**: prohibit visible text and pseudo-text.

The outer Skill no longer pre-writes titles, microcopy, or copy packages. Output language is resolved separately from the interface language and is never guessed from a person, scene, or filename.

## Complete-canvas first, raster-only delivery

The image model owns the aesthetics of the entire finished composition; paired layouts also default to one complete-canvas generation. `scripts/compose_panel.py` remains only for condition-based recovery, lossless pixel calibration, and read-only audit. It is not run pre-emptively and does not judge aesthetic success.

Every deliverable is a raster PNG and every invocation creates a fresh task under `~/Desktop/xxd/`. The configured image route exposes sanitised status only—never providers, endpoints, credentials, headers, prompts, responses, or account details. SVG, HTML, Canvas, diagrams, and programmatic drawing are not substitutes for the final artwork.

## Capability-adaptive questions and inline parameters

The same Skill adapts to the host's real interaction capabilities and never presents decorative symbols as clickable controls:

- **When Claude Code exposes `AskUserQuestion + multiSelect: true`**: modes and sizes use genuine checkboxes; text mode and wallpaper relationship use single-select. Common sizes are grouped into square, portrait, and landscape checkbox questions, selections accumulate across groups, and custom sizes use free input.
- **When Codex exposes only `request_user_input`**: use it only for mutually exclusive fields such as text mode and wallpaper relationship. Do not misrepresent modes or sizes as single-choice; collect them through clear combination input.
- **With no interactive question tool**: use two typed rounds—modes first, then sizes plus text. Never draw fake `- [ ]` boxes or ask the user to switch to Plan mode merely to obtain a form.

The second round initially shows only Smart recommendation, Source aspect, Common ratios, and Custom. Expand the full library only when requested: square `1:1`; portrait `3:4, 4:5, 2:3, 9:16, 5:7`; landscape `4:3, 5:4, 3:2, 16:9, 21:9, 7:5`. Any ratios may be combined, and exact pixels are always accepted.

All settings can also be passed inline:

```text
/xxd-panel-053 photo.jpg --mode top-bottom,design-only --size auto,3:4,9:16 --text prompt --locale ja-JP
```

Supported parameters are `--mode`, repeatable or comma-separated `--size`, `--text prompt|exact|none`, `--locale`, `--copy`, `--wallpaper linked|independent`, `--wallpaper-size`, and `--out`. Complete parameters skip preflight; partial parameters trigger only missing questions.

## Image-model priority

GPT Image 2 is the default first choice. It keeps this project's established workflow: high-fidelity source reference, explicit whole-canvas selection before generation, one complete-canvas generation for paired modes, and scripted composition only as a conditional fallback.

Seedance 5.0 Pro, Nano Banana Pro (Gemini Image Pro), Nano Banana 2 (Gemini Image Flash), or another compatible bitmap model may also be used when it is actually available through the current tools or configured routes and can satisfy source fidelity, whole-canvas ratio, target-language text, and linked-wallpaper multi-reference requirements. An alternative changes only the generation route; it must not change modes, canvas, copy, locale, wallpaper relationship, or the complete-canvas-first strategy.

If no suitable route is available, the Skill asks the user to enable an image-generation tool or provide an API key. User-provided credentials may be used for the current task without being echoed, displayed, logged, or exposed. They are not persisted, and provider, account, billing, or global route configuration is not modified, unless the user explicitly requests that configuration change.

## Get started

```bash
git clone https://github.com/nevertoday/xxd-panel-053.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-053" ~/.codex/skills/xxd-panel-053
```

Claude Code users may link the same folder under `~/.claude/skills/xxd-panel-053`. Restart the agent session after installation.

```text
$xxd-panel-053
Use this photograph, ask me for the modes and copy setting, then generate fresh raster outputs.
```

Full specifications: [Skill workflow](SKILL.md) · [source archive](references/053-source.md) · [English runtime adapter](references/xxd-panel-053-prompt.en.md) · [Chinese runtime adapter](references/xxd-panel-053-prompt.zh-CN.md)

## About XXD

XXD is Xiaoxiaodong's abbreviated brand name. Created and maintained by [@xiaoxiaodong01](https://x.com/xiaoxiaodong01).

## Support and membership

### In-depth consultation · CNY 299/hour

One-to-one in-depth consultation for using Skills. Contact Xiaoxiaodong through WeChat. [WeChat](https://xiaoxiaodong.pages.dev/assets/wechat-qr.png)

### Xiaoxiaodong Skills User Community · CNY 99

A one-time fee joins the Skills user community for workflow sharing and peer discussion; hourly consultation is separate.

### Knowledge Planet + Member Prompt Library · CNY 699/year

One annual payment opens both Knowledge Planet and the member prompt library. Join either side, then contact Xiaoxiaodong on WeChat for the other access.

[Knowledge Planet](https://wx.zsxq.com/group/15554814142882) · [Member Prompt Library](https://vip.xiaoxiaodong.ai/)

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>

<div align="center"><strong>Do not finish the photograph; stop at the exact right moment.</strong></div>

---

<div align="center">

## Support this open-source project

Chinese-language support may use Xiaoxiaodong's own WeChat or Alipay reward codes; other editions use Buy Me a Coffee. Support is optional and never changes access to the open-source project.


<p align="center"><a href="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true"><img src="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true" alt="Buy Me a Coffee" width="180"></a></p>

</div>
</div>
