</> Markdown

# Frontend Resume Project

프론트엔드 개발자로 성장하기 위해 제작한 **이력서형 포트폴리오 웹페이지**입니다.
HTML과 CSS를 활용해 디자인 시안을 실제 웹 화면으로 구현하고, 반응형 레이아웃과 hover 효과를 적용했습니다.

## 배포 링크
https://dhwmgl12-ux.github.io/my-first-github/resume2026/

이 프로젝트는 단순히 이력서를 웹으로 옮기는 것이 아니라,
**디자인 시안을 HTML/CSS로 구현하는 과정**을 직접 경험하기 위해 제작했습니다.

중점적으로 학습한 내용은 다음과 같습니다.
-Figma 시안 기반 퍼블리싱
-HTML 구조 설계
-CSS Grid와 Flexbox 레이아웃
-반응형 웹 구현
-hover 인터랙션
-GitHub Pages 배포

## 제작 과정

처음부터 바로 코드를 작성하지 않고, 먼저 디자인 시안을 만든 뒤 HTML/CSS로 구현했습니다.

```Text
Canva / AI 서비스 / Fiqma First Draft 활용
↓
초기 이력서형 포트폴리오 시안 제작
↓
Canva에서 PDF 다운로드
↓
Fiqma 플러그인으로 PDF를 Layer 변환
↓
Fiqma에서 디자인 및 콘텐츠 상세 수정
↓
HTML 구조 작성
↓
CSS로 레이아웃, 색상, 반응형, hover 효과 구현```

이 과정을 통해 단순히 화면을 따라 만드는 것이 아니라,
디자인 요소를 실제 HTML 구조와 CSS속성으로 어떻게 옮길지 고민했습니다.

디자인 방향성

전체 디자인은 깔끔함, 신뢰감, 가독성을 중심으로 구성했습니다.

왼쪽에는 네이비 컬러의 사이드바를 배치해 프로필, 연락처, 기술 스택, 포트폴리오 정보를 정리했습니다.
오른쪽에는 흰색 본문 영역을 두어 자기소개, 프로젝트 경험, 개발 방향을 순서대로 읽을 수 있도록 구성했습니다.

1.grid로 전체 구조 구성
</> CSS
.resume {
display: grid;
grid-template-columns: 300px 1fr;
}

왼쪽 사이드바와 오른쪽 본문을 2단 구조로 나누었습니다.

2.Flexbox로 세부 정렬
아이콘, 로고, 텍스트를 한 줄에 맞추거나 원형 아이콘 안에 SVG를 중앙 배치할 때 Flexbox를 사용했습니다.

3.반응형 레이아웃
PC에서는 2단 구조로 보이고, 모바일에서는 세로 1단 구조로 변경되도록 미디어쿼리를 적용했습니다.

PC : [sider-bar] [main-content]

Mobile:
[sidebar]
[main-content]

4.hover 효과
CSS만으로 섹션과 스킬 태그에 가벼운 hover 애니메이션을 적용했습니다.
과한 움직임보다 이력서에 어울리는 차분한 인터랙션을 목표로 했습니다.

개발하면서 배운 점

이번 프로젝트를 진행하면서 HTML 구조와 CSS 레이아웃을 단순히 따라 쓰는 것이 아니라,
왜? 이 태그와 속성을 사용하는지 이해하는 것.이 중요하다는 점을 배웠습니다.

특히 다음 부분을 많이 고민했습니다.
-section,aside,div의 역할 구분
-Grid와 Flexbox를 각각 어디에 써야 하는지,
-모바일에서 레이아웃이 깨질 때 원인을 확인하는 방법
-GitHub Pages 반영 지연과 CSS 캐시 문제 확인

사용 기술
-HTML(뼈대)
-CSS(grid,flex,media query, hover animation)
-GitHub(터미널을 활용한 git add . , git commit -m "" , git push origin HEAD or main / 원격저장소 배포)
-Fiqma
-Canva

앞으로 개선할 점
사용한 기술을 내것으로 만드는것? >전문성?

현재는 HTML과 CSS 중심으로 구현했습니다.
JavaScript를 학습한 뒤에는 다음 기능을 추가해보고 싶습니다.

-섹션 접기/펼치기
-다크모드 전환
-프로젝트 카드 필터
-스크롤 애니메이션

느낀 점
이번 프로젝트를 통해 디자인 시안을 실제 웹 화면으로 구현하는 흐름을 경험했습니다.
앞으로도 결과물만 만드는 것이 아니라,
구조와 구현 방식을 이해하고 설명할 수 있는 프론트엔드 개발자가 되는 것을 목표로 학습을 이어가고자 합니다.


# Frontend Resume Project

> 프론트엔드 개발자로 성장하기 위해 제작한 **이력서형 포트폴리오 웹페이지**입니다.  
> 디자인 시안을 바탕으로 HTML/CSS 구조를 직접 작성하고, 반응형 레이아웃과 hover 효과를 적용했습니다.

---

## 배포 링크

🔗 https://dhwmgl12-ux.github.io/my-first-github/resume2026/

---

## 프로젝트 개요

| 구분 | 내용 |
|---|---|
| 프로젝트 유형 | 이력서형 포트폴리오 웹페이지 |
| 주요 목표 | 디자인 시안을 HTML/CSS로 구현 |
| 사용 기술 | HTML, CSS, Grid, Flexbox, Media Query |
| 배포 방식 | GitHub Pages |
| 디자인 도구 | Canva, Figma, Photoshop / Illustrator |

---

## 제작 과정

Canva와 AI 서비스를 활용해 초기 디자인 시안을 만들고,  
PDF를 Figma로 불러와 Layer로 변환한 뒤 디자인을 수정했습니다.

이후 Figma에서 정리한 디자인 값을 기준으로 HTML/CSS 퍼블리싱을 진행했습니다.

```text
Canva / AI 서비스 / Figma First Draft
↓
초기 디자인 시안 제작
↓
Canva PDF 다운로드
↓
Figma 플러그인으로 Layer 변환
↓
Figma에서 디자인 및 콘텐츠 수정
↓
HTML / CSS 구현
↓
GitHub Pages 배포
디자인 방향

전체 디자인은 깔끔함, 신뢰감, 가독성을 중심으로 구성했습니다.

왼쪽에는 네이비 컬러의 사이드바를 배치했습니다.
사이드바에는 프로필, 연락처, 기술 스택, 포트폴리오 정보를 정리했습니다.
오른쪽 본문에는 자기소개, 프로젝트 경험, 개발 방향을 순서대로 배치했습니다.
모바일에서도 자연스럽게 읽히도록 반응형 구조를 적용했습니다.
화면 구조
resume
├─ sidebar
│  ├─ profile
│  ├─ contact
│  ├─ skills
│  └─ portfolio
│
└─ main-content
   ├─ intro
   ├─ summary
   ├─ projects & experience
   └─ direction
구현 포인트
1. CSS Grid로 전체 레이아웃 구성

왼쪽 사이드바와 오른쪽 본문을 2단 구조로 나누기 위해 Grid를 사용했습니다.

.resume {
  display: grid;
  grid-template-columns: 300px 1fr;
}
값	역할
300px	왼쪽 사이드바 고정 너비
1fr	오른쪽 본문이 남은 공간 차지
2. Flexbox로 세부 요소 정렬

아이콘, SVG, 텍스트처럼 작은 요소를 정렬할 때 Flexbox를 사용했습니다.

display: flex;
align-items: center;
justify-content: center;

사용한 곳:

원형 아이콘 안의 SVG 중앙 정렬
스킬 로고와 텍스트 정렬
제목 아이콘과 텍스트 정렬
3. 반응형 레이아웃

PC에서는 2단 레이아웃으로 보이고,
모바일에서는 1단 세로 구조로 변경되도록 구성했습니다.

PC
[sidebar] [main-content]

Mobile
[sidebar]
[main-content]
@media (max-width: 700px) {
  .resume {
    grid-template-columns: 1fr;
  }
}
4. Hover 인터랙션

CSS hover 효과를 사용해 가벼운 움직임을 추가했습니다.

.content-section:hover {
  transform: translateY(-4px);
}

적용한 효과:

본문 섹션 hover 시 살짝 떠오름
스킬 태그 hover 시 오른쪽으로 이동
개발 방향 카드 hover 시 그림자 강조
개발하면서 배운 점

이번 프로젝트를 진행하면서 단순히 코드를 작성하는 것보다
왜 이 구조와 속성을 사용하는지 이해하는 것이 중요하다는 점을 배웠습니다.

특히 많이 고민한 부분은 다음과 같습니다.

section, aside, div의 역할 구분
Grid와 Flexbox의 사용 기준
class를 활용한 공통 스타일 관리
SVG 아이콘과 텍스트 정렬
미디어쿼리를 활용한 모바일 대응
GitHub Pages 반영 지연과 캐시 확인
사용 기술
분류	기술
Markup	HTML
Styling	CSS
Layout	Grid, Flexbox
Responsive	Media Query
Interaction	Hover Animation
Design	Figma, Canva, Photoshop / Illustrator
Deploy	GitHub Pages
앞으로 개선할 점

현재는 HTML과 CSS 중심으로 구현했습니다.
JavaScript를 학습한 뒤에는 다음 기능을 추가해보고 싶습니다.

섹션 접기 / 펼치기
다크모드 전환
프로젝트 카드 필터
스크롤 애니메이션
느낀 점

이번 프로젝트를 통해 디자인 시안을 실제 웹 화면으로 구현하는 과정을 경험했습니다.

앞으로도 결과물만 만드는 것이 아니라,
구조와 구현 방식을 이해하고 설명할 수 있는 프론트엔드 개발자가 되는 것을 목표로 학습을 이어가고자 합니다.
