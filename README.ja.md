<p align="center"><img src="./assets/banner.svg" alt="XXD Panel 053 project banner" width="1200"></p>

<div align="center">

# 🦁 XXD Panel 053

### 観察した線を、最もふさわしい瞬間で止める

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Modes](https://img.shields.io/badge/Modes-4-EF805E?style=flat-square)](#)
[![Output](https://img.shields.io/badge/Output-PNG-4AA1AE?style=flat-square)](#)

<a href="README.md">简体中文</a> 観察ペン線 · 透明な淡彩 · 音楽的リズム · ほぼ白い紙 · 能動的な余白

元写真を、識別性を保つ最小限の線と透明な色彩メモへ編集します。最重要の輪郭や動作を視覚的モチーフとし、反復、変奏、アクセント、休止、そして的確な停止で構成します。

## この Skill が必要な理由

このスタイルは元写真に依存し、内容を差し替えられる装飾プリセットではありません。変換は次の因果鎖に従います：

```text
lock identity, proportion, posture, direction, and relation → preserve three cues → select lines worth remembering → establish one visual motif → repeat, vary, accent, pause, and stop → add two to four source-derived washes → let near-white paper act as silence → let copy become a light echo
```

無関係な写真に替えてもモチーフ、識別手掛かり、線のリズム、色彩メモ、余白、文案が実質的に変わらないなら、本 Panel の成果ではありません。

## ビジュアル契約

- シルエット、比率、姿勢、動作、方向、構造、関係から元写真固有の手掛かりを三つ以上保つ。
- 細く緩い不均一なペン線を使い、探り線、修正、急な強弱、未完の縁を許しつつ、重要な比率は正確にする。
- 一つの輪郭や動作を反復、変奏、アクセント、休止の視覚モチーフにし、大きな空白を能動的な休符にする。
- 元写真由来の二〜四色だけを透明な局部淡彩に使い、ほぼ白い紙色を元写真の色温度に合わせる。
- 「自然なつながり」は固定中線付近の視覚的連続性であり、二連の厳密な50/50幾何を変えない。

完全な美的制約と拒否項目は Skill と生成プロンプトにあります。原文の美的動機を守りつつ、歴史的な3:4画布を隠れた既定値にはしません。 [SKILL.md](SKILL.md) · [production prompt](references/xxd-panel-053-prompt.en.md)

## 作例

作例はまだ提供されていません。予約場所は [assets/examples](assets/examples/README.md) に記載しています。今後の作例は美的意図だけを示し、生成参照、固定された被写体、構図、配色、文案、既定画布にはなりません。

## 組み合わせ可能な4つの出力

`1`、`1+3`、`1,2,4`、`全部` で一つまたは複数を選べます。`全部` は元写真1枚につき通常3点と壁紙4点、計7点のPNGを出力します。

| モード | 未指定時の寸法 | 成果物 |
| --- | --- | --- |
| `top-bottom` | 元画像適応 `W×2H` | 上に完全な元写真、下に変換デザイン、厳密な50/50 |
| `left-right` | 元画像適応 `2W×H` | 左に完全な元写真、右に変換デザイン、厳密な50/50 |
| `design-only` | 元画像適応 `W×H` | 変換デザインのみ。元写真は表示しない |
| `wallpaper-pack` | 端末別に指定 | スマートフォン、iPad、デスクトップ、子ども用ウォッチの個別PNG |

壁紙は連動または独立を選べます。連動は一つの基準作を承認し、全端末が元写真と同じ基準作を参照します。切り抜きも派生連鎖もしません。独立は各端末が元写真だけを参照します。

## 文案と言語

生成前に自動文案、正確な指定文案、文字なしを確定します。言語は指示文ではなく対象読者に従い、完成稿は一字一句保持します。

本プロジェクトの文案規則：主体、動作、環境、音、時間、記憶、偶然の細部に強く結びつく一語、短句、記号、極短い題名だけを抽出し、輪郭、視線、動線、未完の縁に沿う小さなアクセント、休止、反響として置きます。

## 幾何、ラスター、信頼

通常モードは指定がなければ元画像に適応し、二連は厳密な50/50、成果物はPNGラスターです。毎回 `~/Desktop/xxd/` に新規タスクを作り、非公開の生成経路情報を開示しません。

設定済みの画像ブリッジは匿名化された状態だけを返し、提供元、接続先、認証情報、ヘッダー、プロンプト、応答、アカウント情報を開示しません。SVG、HTML、Canvas、図解、プログラム描画は最終ラスター作品の代替になりません。

## 使い始める

```bash
git clone https://github.com/nevertoday/xxd-panel-053.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-053" ~/.codex/skills/xxd-panel-053
```

Claude Code では同じフォルダを次へリンクできます： `~/.claude/skills/xxd-panel-053`. インストール後に Agent セッションを再起動してください。

```text
$xxd-panel-053
Use this photograph, ask me for the modes and copy setting, then generate fresh raster outputs.
```

完全仕様: [Skill ワークフロー](SKILL.md) · [原始スタイル資料](references/053-source.md) · [英語生成プロンプト](references/xxd-panel-053-prompt.en.md) · [中国語生成プロンプト](references/xxd-panel-053-prompt.zh-CN.md)

## XXD について

XXD は Xiaoxiaodong のブランド名略称です。作成・管理： [@xiaoxiaodong01](https://x.com/xiaoxiaodong01).

## サポートとメンバーシップ

### 個別コンサルティング · 299元／時間

Skills の使用とワークフローに関する一対一の相談です。WeChat で Xiaoxiaodong にご連絡ください。 [WeChat](https://xiaoxiaodong.pages.dev/assets/wechat-qr.png)

### Xiaoxiaodong Skills ユーザー交流グループ · 99元

一回の支払いで Skills ユーザー交流グループに参加できます。時間制の個別相談は別料金です。

### Knowledge Planet＋会員プロンプトライブラリ · 699元／年

Knowledge Planet と会員プロンプトライブラリは一つの年会です。どちらかで加入後、WeChat で連絡するともう一方も開通できます。

[Knowledge Planet](https://wx.zsxq.com/group/15554814142882) · [Member Prompt Library](https://vip.xiaoxiaodong.ai/)

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>

<div align="center"><strong>写真を描き切らず、最もふさわしい瞬間で止める。</strong></div>

---

<div align="center">

## ☕ オープンソースを支援

中国語圏以外では Buy Me a Coffee を利用できます。支援は任意で、オープンソースへのアクセスを変えません。


<p align="center"><a href="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true"><img src="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true" alt="Buy Me a Coffee" width="180"></a></p>

</div>
</div>
