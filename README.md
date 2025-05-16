# 프론트엔드 과제

Extory 프론트엔드 개발자 과제 테스트용으로 제공된 가이드라인입니다.

## 과제 소개

Extory에서 [이미 제공하고 있는 페이지](https://extory.co/blogs)를 클론 코딩하는 작업입니다. 과제를 통하여 지원자의 리액트 구현 능력, 디자이너님의 디자인을 얼마나 똑같이 구현할수 있는지, 그리고 폴더 구조나 컴포넌트를 어떤식으로 나누는지 보고자합니다.

## 제출 방법 및 기한

- 새로 깃 레파지토리를 생성 후, 과제를 진행해주세요.
- 과제 완료 후 깃 레파지토리 링크를 메일로 전달바랍니다.
- 제출 마감일자는 **2025년 5월 21일 수요일 23시 59분 59초**입니다.

## 리소스 링크

- [Swagger 바로가기](https://extory.co/api-docs)
- [Figma 바로가기](https://www.figma.com/design/rfrtG1czp6RqUTadbuScfD/%EA%B3%BC%EC%A0%9C?node-id=0-1&m=dev&t=jSd7sSzL5x1LEyEq-1)
- [익스토리 블로그 페이지](https://extory.co/blogs)
- [이미지 파일](https://github.com/michaelhur/extory-fe-assignment/tree/master/resource)

## 1. 기본 공통 요구사항

- React (18 또는 19)
- Typescript 필수
- 외부 UI 컴포넌트
  - [MUI](https://mui.com/), [shadcn](https://ui.shadcn.com/) 과 같이 이미 컴포넌트가 구현되어 있는 UI 라이브러리는 사용 **불가**
  - 단, [Tailwind](https://tailwindcss.com/), [Styled-Components](https://styled-components.com/)와 같은 CSS-inJS, JS-in-CSS, 아이콘 라이브러리 사용 가능
  - 아이콘 라이브러리를 사용시, Figma에 제공된 디자인과 *비슷한* 디자인의 아이콘을 사용하셔도 됩니다.
- npm, yarn, pnpm중 원하는 package manager 사용
- README.MD 파일 작성
  - 빌드 및 실행 방법
  - 깃 제공시 **node_modules**폴더는 제외하시기 바랍니다
- **그 외 모든 패키지** 사용 가능합니다.

## 2. 과제

- 전체 UI를 제공된 Figma 디자인과 동일하게 구현해주세요. [익스토리 블로그 페이지](https://extory.co/blogs)를 참고하면 좋습니다.
  - 제공된 Figma 디자인과 같이 1440px의 화면을 기준으로 만들어주세요.
  - 반응형으로 제작하지 않으셔도 됩니다. 1440px 화면에서만 잘 나오면 되요!
- 데이터는 제공되는 API를 통해서 받아옵니다.
  - `블로그 리스트 정보`와 `카테고리 정보`가 제공됩니다.
- 메인 페이지 접속 시, 자동으로 `블로그 목록` 페이지 `/blogs`로 리다이렉션 해주세요.
- 블로그 상세 페이지 `/blogs/:id` 접속 시, 화면에는 블로그의 id값을 보여주세요.
- 상단 `익스토리 로고`와 `블로그` 클릭시  `블로그 목록` 페이지로 리다이렉션 해주세요.
- 애니메이션은 구현하지 않으셔도 됩니다.

## 3. API

- API_BASE_URL: https://extory.co/api
- [Swagger 바로가기](https://extory.co/api-docs)