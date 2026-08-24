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

## 作例 · X より

> [小小東（@xiaoxiaodong01）](https://x.com/xiaoxiaodong01/status/2091521812878459186) · 2026年8月23日<br>
> GPT2 × 手描き × 即興 × 美学プロンプト × VOL.053

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091521812878459186"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 053 作例 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091521812878459186"><img src="./assets/examples/sample-02.jpg" alt="XXD Panel 053 作例 2"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091521812878459186"><img src="./assets/examples/sample-03.jpg" alt="XXD Panel 053 作例 3"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091521812878459186"><img src="./assets/examples/sample-04.jpg" alt="XXD Panel 053 作例 4"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2091521812878459186">元の投稿と完全なプロンプトを見る →</a></p>

これらの作例は 053 の美的意図を示すものであり、作例の被写体、構図、配色、コピー、旧キャンバス比率が生成時の参照や現在の既定値になることはありません。

## 組み合わせ可能な4つの出力

`1`、`1+3`、`1,2,4`、`全部` で一つまたは複数を選べます。`全部` は元画像ごとに7点の独立PNGを出力します。モード選択後、生成前に完成画像全体の画角を必ず確認します：元プロンプトの `3:4`、明示的な元画像比率、一般的な比率、またはカスタム比率／正確なピクセルです。元画像寸法を暗黙には適用しません。

| モード | 画角ルール | 成果物 |
| --- | --- | --- |
| `top-bottom` | ユーザー確認済みの完成画角 | 完成キャンバスを一度に生成：上に高忠実度の元画像、下に 053 デザイン、約50/50 |
| `left-right` | ユーザー確認済みの完成画角 | 完成キャンバスを一度に生成：左に高忠実度の元画像、右に 053 デザイン、約50/50 |
| `design-only` | ユーザー確認済みの完成画角 | 053 デザインが全画面を満たし、元画像は表示しない |
| `wallpaper-pack` | 端末ごとに確認 | スマートフォン、iPad、デスクトップ、子ども用ウォッチの個別PNG |

二連モードは元画像を高忠実度の編集／参照入力として使い、完全なスタイルプロンプト一式で完成画面を直接生成します。写真、デザイン、色、光、文字、意味を一体化するためです。決定論的な合成は、完成画面の再試行後も失敗した場合、原画像のピクセル完全保持を明示された場合、生成経路が指定画角に対応しない場合、または無劣化の最終ピクセル調整が必要な場合だけ使います。

壁紙は連動または独立を選べます。連動はiPad基準作を一つ承認し、他の端末を元画像＋同じ基準作から個別に再構成します。独立は各端末が元画像だけを参照します。どちらも他端末の成果を切り抜かず、派生を連鎖しません。

## 文案と言語

生成前に自動文案、正確な指定文案、文字なしを確定します。言語は指示文ではなく対象読者に従い、完成稿は一字一句保持します。

本プロジェクトの文案規則：主体、動作、環境、音、時間、記憶、偶然の細部に強く結びつく一語、短句、記号、極短い題名だけを抽出し、輪郭、視線、動線、未完の縁に沿う小さなアクセント、休止、反響として置きます。

## 完成キャンバス優先とラスター境界

画像モデルが完成画面全体の美的再構成を担当し、二連レイアウトも完成キャンバス一枚の直接生成を既定とします。`scripts/compose_panel.py` は条件付きの復旧、無劣化ピクセル調整、読み取り専用監査にだけ残し、毎回の事前計画や美的評価には使いません。

納品物はすべてPNGラスターで、呼び出しごとに `~/Desktop/xxd/` に新規タスクを作ります。設定済み画像経路は匿名化された状態だけを返し、提供元、接続先、認証情報、ヘッダー、プロンプト、応答、アカウント情報を公開しません。SVG、HTML、Canvas、図解、プログラム描画は最終作品の代替になりません。

## 画像モデルの優先順位

GPT Image 2 を既定の第一候補とします。高忠実度の参照画像、生成前の完成キャンバス確認、二連モードの完成画面一括生成、条件を満たした場合だけのスクリプト合成という既存の流れは変わりません。

現在のツールまたは設定済み経路から実際に利用でき、元画像の忠実度、完成画角、対象言語の文字、連動壁紙の複数参照を満たせる場合は、Seedance 5.0 Pro、Nano Banana Pro（Gemini Image Pro）、Nano Banana 2（Gemini Image Flash）、その他の互換ビットマップモデルも利用できます。代替モデルが変更できるのは生成経路だけで、モード、画角、文案、言語、壁紙関係、完成キャンバス優先の方針は変更できません。

適切な経路がない場合は、画像生成ツールを有効にするか API Key を提供するようユーザーに案内します。ユーザーが提供した認証情報は現在のタスクで利用できますが、返信やログに再表示・記録・開示しません。明示的な依頼がない限り、長期保存やプロバイダー、アカウント、課金、グローバル経路の設定変更も行いません。

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
