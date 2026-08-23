<p align="center"><img src="./assets/banner.svg" alt="XXD Panel 053 project banner" width="1200"></p>

<div align="center">

# 🦁 XXD Panel 053

### 让被观察的线条在最恰当的位置停下

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Modes](https://img.shields.io/badge/Modes-4-EF805E?style=flat-square)](#)
[![Output](https://img.shields.io/badge/Output-PNG-4AA1AE?style=flat-square)](#)

<strong>简体中文</strong> 观察线稿 · 透明淡彩 · 音乐性节奏 · 近白纸面 · 大胆留白

将源照片删减为仍能维持身份的少量线条与透明色彩笔记；最重要的轮廓或动作成为视觉动机，在重复、变奏、重音、停顿与留白中适时停下。

## 为什么需要这套 Skill

这套风格依赖每一张源图，不是可替换内容的装饰预设。它遵循这条重构链：

```text
锁定身份、比例、姿态、方向与叙事关系 → 保留三个线索 → 选择值得记忆的线 → 建立一个视觉动机 → 重复、变奏、重音、停顿并停笔 → 局部加入两至四种源图淡彩 → 让近白纸面成为休止 → 让文案成为轻微回声
```

如果换成无关照片后，视觉动机、识别线索、线条节奏、色彩笔记、留白与文案不发生实质变化，结果就不属于这套 Panel。

## 视觉契约

- 至少保留三个源图专属的剪影、比例、姿态、动作、方向、结构或关系线索。
- 使用纤细、松动、不均匀的钢笔线，允许寻找线、修正、突然加重与未完成边缘；关键比例必须准确。
- 以一个轮廓或动作为视觉动机，组织重复、变奏、重音与停顿，让大片空白成为主动休止。
- 只用两至四种源图色作透明局部点染；纸色接近白色，并按源图冷暖轻微调整。
- “自然衔接”是固定中线附近的视觉过渡语言，不改变双联严格 50/50 的几何分割。

完整审美约束与拒绝项写在 Skill 和生产提示词中；它们保留原始提示词的审美动机，但不会把历史 3:4 画布变成隐藏默认值。 [SKILL.md](SKILL.md) · [production prompt](references/xxd-panel-053-prompt.en.md)

## 样张 · 来自 X

> [小小东（@xiaoxiaodong01）](https://x.com/xiaoxiaodong01/status/2091521812878459186) · 2026 年 8 月 23 日<br>
> GPT2 × 手绘 × 即兴 × 美学提示词 × VOL.053

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091521812878459186"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 053 样张 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091521812878459186"><img src="./assets/examples/sample-02.jpg" alt="XXD Panel 053 样张 2"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091521812878459186"><img src="./assets/examples/sample-03.jpg" alt="XXD Panel 053 样张 3"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091521812878459186"><img src="./assets/examples/sample-04.jpg" alt="XXD Panel 053 样张 4"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2091521812878459186">查看原推文与完整提示词 →</a></p>

这些样张用于展示 053 的美学动机，不会把样张中的主体、构图、配色、文案或旧画幅变成生成参考或当前默认值。

## 四种可组合输出模式

可以用 `1`、`1+3`、`1、2、4` 或 `全部` 选择一个或多个模式；`全部` 每张源图输出 7 张 PNG：三种普通模式各一张，外加四张壁纸。

| 模式 | 未指定尺寸 | 成果物 |
| --- | --- | --- |
| `top-bottom` | 源图自适应 `W×2H` | 上方完整源图＋下方变化设计，严格 50/50 |
| `left-right` | 源图自适应 `2W×H` | 左侧完整源图＋右侧变化设计，严格 50/50 |
| `design-only` | 源图自适应 `W×H` | 只显示变化设计，不出现原照片 |
| `wallpaper-pack` | 设备分别标注尺寸 | 手机、iPad、电脑、儿童手表四张独立 PNG |

壁纸可选连贯或独立。连贯套装先批准一张定调图，所有设备都共同参考原图与这同一锚点，绝不裁切或串联衍生图；独立套装每张只参考原图。

## 文案与语言

正式生成前确认自动文案、准确自定义文案或无文字；语言跟随目标受众而不是命令语言，用户给出的准确文案逐字保留。

本项目的文案规则：只提炼一个与主体、动作、环境、声音、时间、记忆或偶然细节强绑定的词、短句、符号或极短标题；让文字沿轮廓、视线、动作方向或未完成边缘成为轻微重音、停顿或回声。

## 几何、位图与可信边界

普通模式未指定尺寸时按源图自适应；双联严格 50/50，全部交付为 PNG 位图。每次调用都在 `~/Desktop/xxd/` 下创建新任务，绝不泄露私密生成路线信息。

已配置的位图桥只输出脱敏状态，绝不暴露服务方、端点、凭据、请求头、提示词、响应或账户信息。SVG、HTML、Canvas、图表和程序绘图都不能代替最终位图作品。

## 开始使用

```bash
git clone https://github.com/nevertoday/xxd-panel-053.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-053" ~/.codex/skills/xxd-panel-053
```

Claude Code 用户可把同一文件夹链接到 `~/.claude/skills/xxd-panel-053`. 安装后请重启 Agent 会话。

```text
$xxd-panel-053
Use this photograph, ask me for the modes and copy setting, then generate fresh raster outputs.
```

完整规格: [Skill 工作流](SKILL.md) · [原始风格档案](references/053-source.md) · [英文生产提示词](references/xxd-panel-053-prompt.en.md) · [中文生产提示词](references/xxd-panel-053-prompt.zh-CN.md)

## 关于 XXD

XXD 是小小东品牌名的缩写，本项目由小小东创建并维护： [@xiaoxiaodong01](https://x.com/xiaoxiaodong01).

## 支持与会员

### 深度咨询 · 299 元／小时

一对一深入咨询 Skills 的使用与工作流，通过微信联系小小东预约。 [WeChat](https://xiaoxiaodong.pages.dev/assets/wechat-qr.png)

### 小小东 Skills 用户交流群 · 99 元

一次付费加入 Skills 用户交流群，用于工作流分享和用户间讨论；不包含按小时计费的一对一咨询。

### 知识星球＋成员提示词库 · 699 元／年

知识星球和成员提示词库是一份会员费用：从任一入口开通后，通过微信联系小小东获取另一边的权益。

[Knowledge Planet](https://wx.zsxq.com/group/15554814142882) · [Member Prompt Library](https://vip.xiaoxiaodong.ai/)

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>

<div align="center"><strong>不是把照片画完，而是在最恰当的位置停下。</strong></div>

---

<div align="center">

## ☕ 支持这个开源项目

算力赞助请使用小小东自己的微信或支付宝赞赏码；赞助完全自愿，不改变开源项目的访问权限。


<table><tr>
<td align="center"><a href="https://colors.xiaoxiaodong.ai/docs/images/wechat-reward-qr.png"><img src="https://colors.xiaoxiaodong.ai/docs/images/wechat-reward-qr.png" alt="XXD WeChat reward" width="180"></a><br><strong>WeChat</strong></td>
<td align="center"><a href="https://colors.xiaoxiaodong.ai/docs/images/alipay-reward-qr.png"><img src="https://colors.xiaoxiaodong.ai/docs/images/alipay-reward-qr.png" alt="XXD Alipay reward" width="180"></a><br><strong>Alipay</strong></td>
</tr></table>

</div>
</div>
