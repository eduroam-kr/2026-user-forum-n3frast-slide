# 테마 만들 때 참고할 팔레트 출처

나중에 테마를 더 만들 때 쓰려고 모아 둔 메모입니다.
**✅ 확인함** = 라이선스를 GitHub API 나 공식 문서에서 직접 확인했고, 색 값도
공식 배포본에서 뽑아 봤다는 뜻입니다. **❓ 미확인** 은 "있다고 알려진 것"이므로
쓰기 전에 아래 「값 뽑는 법」으로 직접 확인하세요. 기억에 의존해 하드코딩하지 말 것.

---

## 이미 쓴 것

| 테마 | 출처 | 라이선스 | |
|---|---|---|---|
| `carbon` | IBM Carbon Design System | Apache-2.0 | ✅ 확인함 |
| `solarized` | Solarized (Ethan Schoonover) | MIT | ✅ 확인함 |
| `nord` | Nord (Arctic Ice Studio) | MIT | ✅ 확인함 |
| `metropolis` | LaTeX Beamer Metropolis (matze/mtheme) | **CC BY-SA 4.0** | ✅ 확인함 ⚠ copyleft |
| `slate` `cobalt` `pine` | 직접 조정 | — | 출처 의무 없음 |

---

## 쓸 만한 것 — 디자인 시스템

발표 화면에 가장 안전한 쪽입니다. 애초에 **큰 화면·먼 거리**를 전제로 만들어졌고
중간 톤이 적습니다.

| 출처 | 라이선스 | 성격 | |
|---|---|---|---|
| [IBM Carbon](https://carbondesignsystem.com/elements/color/overview/) | Apache-2.0 | 기관·엔터프라이즈. 각지고 대비 높음 | ✅ |
| [Tailwind CSS](https://tailwindcss.com/docs/colors) | MIT | 11단계 램프가 잘 조율돼 있어 토큰 세트 만들기 편함 | ❓ v4 에서 OKLCH 로 바뀌며 hex 가 조금 움직였음 — **반드시 확인** |
| [GitHub Primer](https://primer.style/foundations/color) | MIT | 차분한 중립 + 상태색 | ❓ |
| [Material Design](https://m3.material.io/styles/color) | Apache-2.0 | 색 단계가 가장 촘촘 | ❓ |
| [USWDS](https://designsystem.digital.gov/design-tokens/color/overview/) | 공유저작물(미 연방) | 공공기관 발표에 결이 맞음. 접근성 등급이 토큰에 박혀 있음 | ❓ |

## 쓸 만한 것 — 에디터·터미널 테마

| 출처 | 라이선스 | |
|---|---|---|
| [Solarized](https://github.com/altercation/solarized) | MIT | ✅ Light/Dark 한 쌍 |
| [Nord](https://github.com/nordtheme/nord) | MIT | ✅ |
| [Catppuccin](https://github.com/catppuccin/catppuccin) | MIT | ❓ Latte(밝음)/Frappé/Macchiato/Mocha(어두움) 4벌 |
| [Gruvbox](https://github.com/morhetz/gruvbox) | MIT | ❓ 따뜻한 복고. Light 도 있음 |
| [Dracula](https://github.com/dracula/dracula-theme) | MIT | ❓ 어두움 전용 |
| [Tokyo Night](https://github.com/enkia/tokyo-night-vscode-theme) | MIT | ❓ |
| [Atom One](https://github.com/atom/atom) (One Light/Dark) | MIT | ❓ |
| [VS Code 기본](https://github.com/microsoft/vscode) Dark+/Light+ | MIT | ❓ `extensions/theme-defaults/themes/` |
| [iTerm2-Color-Schemes](https://github.com/mbadolato/iTerm2-Color-Schemes) | MIT | ❓ 400여 개 **수집물** — 개별 스킴 출처는 제각각이니 쓰려는 것만 따로 확인 |

> ⚠ **에디터·터미널 테마는 투사하면 자주 무너집니다.**
> 작은 글자를 가까이서, 어두운 방에서 보는 조건에 맞춘 색입니다. 3 m 떨어진
> 스크린에 조명 켜고 쏘면 대비가 모자라고 채도 높은 구문색이 떱니다.
> 그나마 버티는 것: **Solarized Light · Gruvbox Light · Catppuccin Latte · Nord(어두움)**.
> 반대로 **Beamer 테마는 처음부터 투사를 전제**로 만들어졌습니다 — 그래서
> `metropolis` 를 넣었습니다.

## 쓸 만한 것 — LaTeX Beamer

발표용으로는 가장 결이 맞는 쪽입니다.

| 출처 | 라이선스 | |
|---|---|---|
| [Metropolis](https://github.com/matze/mtheme) | **CC BY-SA 4.0** | ✅ 고쳐서 재배포하면 동일 라이선스 의무. 파일 하나로 격리해 둠 |
| Beamer 내장 색테마 (`beaver` `crane` `dolphin` `seahorse` `whale` `spruce` …) | LPPL | ❓ TeX Live 안의 `beamercolortheme*.sty` |
| [Overleaf 발표 템플릿 모음](https://www.overleaf.com/latex/templates/tagged/presentation) | 템플릿마다 다름 | ❓ **개별 확인 필수** |

> `cobalt` / `pine` 은 Overleaf 템플릿에서 **값을 가져오지 않았습니다.**
> "파란 제목에 주황 점"이라는 **배분만** 보고 색은 직접 잡았습니다 —
> 그래서 출처 표기 의무가 없습니다. 아이디어는 저작권 대상이 아닙니다.

## 과학 figure 용 (차트·도식에)

슬라이드 UI 색이 아니라 **데이터 색**이 필요할 때.

| 출처 | 라이선스 | |
|---|---|---|
| [ColorBrewer](https://colorbrewer2.org/) | Apache-2.0 | ❓ 지도학에서 출발. 순차/발산/범주형이 나뉘어 있고 색각 안전 표시가 있음 |
| Okabe–Ito 8색 | 사실상 공개 | ❓ ⚠ **출처마다 값이 다릅니다** — 원문 페이지는 `#FF8C00` 계열, R/matplotlib 에서 통용되는 판은 `#E69F00` 계열. 어느 쪽을 쓸지 정하고 출처를 적으세요 |

## 안 쓰는 게 낫다고 본 것

| | 이유 |
|---|---|
| 나무위키 | 사설 사이트의 **브랜드 외형**입니다. 공개된 팔레트가 아니라 가져올 근거가 없습니다 |
| [openNAMU](https://github.com/openNAMU/openNAMU) | BSD-3-Clause 로 자유롭지만 **위키 엔진**이지 디자인 시스템이 아닙니다. 문서화된 색 토큰이 없습니다 |
| oh-my-zsh | MIT 지만 **프롬프트 레이아웃** 프레임워크입니다. 색은 터미널이 정하므로 팔레트 자체가 없습니다 |
| Monokai | 원본의 라이선스가 불분명하고 Monokai Pro 는 상용입니다 |

---

## 값 뽑는 법

기억으로 hex 를 적지 말고 공식 배포본에서 뽑으세요. 실제로 쓴 명령입니다.

```sh
# 라이선스 — GitHub API 가 SPDX 로 알려줍니다
curl -s https://api.github.com/repos/nordtheme/nord \
  | python3 -c 'import json,sys;print(json.load(sys.stdin)["license"]["spdx_id"])'

# npm 으로 배포되는 디자인 시스템 (Carbon · Primer · Tailwind …)
curl -sL https://cdn.jsdelivr.net/npm/@carbon/colors/lib/index.js \
  | grep -oE 'const (gray|blue|green|red|orange)[0-9]+ = "#[0-9a-f]{6}"'

# 패키지 최신 버전
curl -s https://data.jsdelivr.com/v1/packages/npm/@carbon/colors \
  | python3 -c 'import json,sys;print(json.load(sys.stdin)["tags"]["latest"])'

# LaTeX 테마는 .dtx 안에 \definecolor 로 들어 있습니다
curl -sL https://raw.githubusercontent.com/matze/mtheme/master/source/beamercolorthememetropolis.dtx \
  | grep definecolor
```

---

## 새 테마 만들기

`themes/slate.css` 를 복사해서 값만 바꾸면 됩니다. 채워야 할 토큰:

```
글꼴  --serif --sans --mono --body-font --head-font
바탕  --bg --surface --tint --tint-soft --chip --code-bg --track
글자  --ink --ink-soft --ink-faint
선    --rule --rule-soft --rule-strong
강조  --accent --accent-ink [--accent-2]
간지  --divider-bg --divider-ink --divider-soft --divider-dim --divider-rule
```

- **의미색(`--ok-*` `--warn-*` `--danger-*` `--info-*`)은 건드리지 마세요.**
  `deck.css` 에 고정돼 있습니다. 뜻이 테마를 따라 움직이면 안 됩니다.
  어두운 테마만 대비 때문에 덮습니다(`nord.css` 참고).
- `--accent-2` 는 안 주면 `--accent` 와 같아집니다. 주면 **글머리표·간지
  악센트 바·키커**가 그 색이 됩니다. 작고 굵은 자리 전용 — 본문 글자색으로 쓰지 말 것.
- 파일 머리에 `/*! deck-theme name: … source: … license: … */` 를 남기세요.
  나중에 출처를 다시 찾느라 시간 쓰지 않게.
- 어두운 테마는 `html.paper .reveal .deck-paper` 의 그림자가 안 보이므로
  테두리로 바꾸세요(`nord.css` 참고).

### 확인

```sh
python3 -m http.server 8000      # 또는 그냥 index.html 을 브라우저로
```

간지(흰 글씨) · 카드 · alert 5종 · 코드블록 · 표 · chapnav 활성 알약 —
이 여섯 곳만 보면 대개 걸러집니다.
