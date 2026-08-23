<p align="center"><img src="./assets/banner.svg" alt="XXD Panel 053 project banner" width="1200"></p>

<div align="center">

# 🦁 XXD Panel 053

### 관찰한 선을 가장 알맞은 순간에 멈추기

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Modes](https://img.shields.io/badge/Modes-4-EF805E?style=flat-square)](#)
[![Output](https://img.shields.io/badge/Output-PNG-4AA1AE?style=flat-square)](#)

<a href="README.md">简体中文</a> 관찰 펜선 · 투명 담채 · 음악적 리듬 · 거의 흰 종이 · 능동적 여백

원본을 정체성을 살리는 최소한의 선과 투명한 색 메모로 편집합니다. 가장 중요한 윤곽이나 동작을 시각적 모티프로 삼아 반복, 변주, 강세, 쉼, 그리고 정확한 멈춤으로 구성합니다.

## 이 Skill이 필요한 이유

이 스타일은 원본에 의존하며 내용을 바꿔 끼우는 장식 프리셋이 아닙니다. 다음 변환 인과를 따릅니다:

```text
lock identity, proportion, posture, direction, and relation → preserve three cues → select lines worth remembering → establish one visual motif → repeat, vary, accent, pause, and stop → add two to four source-derived washes → let near-white paper act as silence → let copy become a light echo
```

무관한 사진으로 바꿔도 모티프, 식별 단서, 선의 리듬, 색 메모, 여백과 문구가 실질적으로 달라지지 않는다면 이 Panel의 결과가 아닙니다.

## 시각적 원칙

- 실루엣, 비례, 자세, 동작, 방향, 구조, 관계에서 원본 고유 단서를 세 가지 이상 보존합니다.
- 가늘고 느슨하며 불균일한 펜선을 쓰고 탐색선, 수정, 갑작스러운 강약, 미완성 가장자리를 허용하되 핵심 비례는 정확히 유지합니다.
- 하나의 윤곽이나 동작을 반복, 변주, 강세, 쉼의 모티프로 만들고 넓은 공백을 능동적 휴지로 사용합니다.
- 원본에서 얻은 두세 가지 또는 네 가지 색만 투명한 국소 담채로 쓰고 거의 흰 종이색을 원본 온도에 맞춥니다.
- “자연스러운 연결”은 고정 중간선 주변의 시각적 연속성일 뿐, 정확한 50/50 이중 패널 기하를 바꾸지 않습니다.

전체 미적 제약과 금지 항목은 Skill과 생성 프롬프트에 있습니다. 원문 미학을 보존하지만 역사적인 3:4 화면을 숨은 기본값으로 만들지 않습니다. [SKILL.md](SKILL.md) · [production prompt](references/xxd-panel-053-prompt.en.md)

## 예시

예시는 아직 제공되지 않았습니다. 예약 위치는 [assets/examples](assets/examples/README.md)에 기록되어 있습니다. 향후 예시는 미적 의도만 보여 주며 생성 참고, 고정 주제, 구성, 색상, 문구 또는 기본 화면이 되지 않습니다.

## 조합 가능한 네 가지 출력

`1`, `1+3`, `1,2,4`, `전체`로 하나 또는 여러 모드를 선택할 수 있습니다. `전체`는 원본 한 장당 일반 결과 3개와 배경화면 4개, 총 PNG 7개를 만듭니다.

| 모드 | 미지정 크기 | 결과물 |
| --- | --- | --- |
| `top-bottom` | 원본 적응형 `W×2H` | 위에 전체 원본, 아래에 변환 디자인, 정확한 50/50 |
| `left-right` | 원본 적응형 `2W×H` | 왼쪽에 전체 원본, 오른쪽에 변환 디자인, 정확한 50/50 |
| `design-only` | 원본 적응형 `W×H` | 변환 디자인만 표시하고 원본 사진은 보이지 않음 |
| `wallpaper-pack` | 기기별 지정 | 휴대전화, iPad, 데스크톱, 어린이용 스마트워치 PNG 개별 출력 |

배경화면은 연결형 또는 독립형입니다. 연결형은 기준 작품 하나를 승인한 뒤 모든 기기가 원본과 같은 기준 작품을 참조하며 크롭하거나 파생 결과를 연쇄 참조하지 않습니다. 독립형은 각 기기가 원본만 참조합니다.

## 문구와 언어

생성 전에 자동 문구, 정확한 사용자 문구, 무문자 중 하나를 확정합니다. 언어는 명령문이 아니라 대상 독자를 따르며 완성 문구는 그대로 유지합니다.

이 프로젝트의 문구 규칙: 주체, 동작, 환경, 소리, 시간, 기억 또는 우연한 디테일에 강하게 묶인 한 단어, 짧은 구절, 기호 또는 극히 짧은 제목만 추출하고 윤곽, 시선, 동선, 미완성 가장자리를 따라 작은 강세, 쉼 또는 메아리로 배치합니다.

## 기하, 래스터, 신뢰

일반 모드는 지정이 없으면 원본에 맞추고, 이중 패널은 정확히 50/50이며 결과물은 PNG 래스터입니다. 호출마다 `~/Desktop/xxd/`에 새 작업을 만들고 비공개 생성 경로 정보를 노출하지 않습니다.

설정된 이미지 브리지는 비식별 상태만 반환하며 제공자, 엔드포인트, 인증 정보, 헤더, 프롬프트, 응답 또는 계정 정보를 노출하지 않습니다. SVG, HTML, Canvas, 도표와 프로그램 그림은 최종 래스터 작품을 대신할 수 없습니다.

## 시작하기

```bash
git clone https://github.com/nevertoday/xxd-panel-053.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-053" ~/.codex/skills/xxd-panel-053
```

Claude Code 사용자는 같은 폴더를 다음 위치에 연결할 수 있습니다: `~/.claude/skills/xxd-panel-053`. 설치 후 에이전트 세션을 다시 시작하세요.

```text
$xxd-panel-053
Use this photograph, ask me for the modes and copy setting, then generate fresh raster outputs.
```

전체 사양: [Skill 워크플로](SKILL.md) · [원본 스타일 자료](references/053-source.md) · [영문 생성 프롬프트](references/xxd-panel-053-prompt.en.md) · [중문 생성 프롬프트](references/xxd-panel-053-prompt.zh-CN.md)

## XXD 소개

XXD는 Xiaoxiaodong 브랜드 이름의 약자입니다. 제작 및 유지관리: [@xiaoxiaodong01](https://x.com/xiaoxiaodong01).

## 지원과 멤버십

### 심층 상담 · 시간당 CNY 299

Skills 사용과 워크플로에 관한 일대일 심층 상담입니다. WeChat으로 Xiaoxiaodong에게 문의하세요. [WeChat](https://xiaoxiaodong.pages.dev/assets/wechat-qr.png)

### Xiaoxiaodong Skills 사용자 교류 그룹 · CNY 99

한 번의 결제로 Skills 사용자 교류 그룹에 참여합니다. 시간제 일대일 상담은 별도입니다.

### Knowledge Planet＋회원 프롬프트 라이브러리 · 연 CNY 699

Knowledge Planet과 회원 프롬프트 라이브러리는 하나의 연간 멤버십입니다. 어느 한쪽에서 가입한 뒤 WeChat으로 연락하면 다른 쪽도 열립니다.

[Knowledge Planet](https://wx.zsxq.com/group/15554814142882) · [Member Prompt Library](https://vip.xiaoxiaodong.ai/)

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>

<div align="center"><strong>사진을 끝까지 그리지 말고 가장 알맞은 순간에 멈춥니다.</strong></div>

---

<div align="center">

## ☕ 오픈 소스 프로젝트 후원

중국어판 이외에는 Buy Me a Coffee를 이용할 수 있습니다. 후원은 선택 사항이며 오픈 소스 접근 권한을 바꾸지 않습니다.


<p align="center"><a href="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true"><img src="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true" alt="Buy Me a Coffee" width="180"></a></p>

</div>
</div>
