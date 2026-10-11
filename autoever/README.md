# 이희철 Data Engineer 포트폴리오

공개 주소: https://undernation.github.io/autoever/

2026.10.11 최종 PDF 7쪽을 그대로 보여주는 정적 웹페이지입니다. 별도 로그인·외부 CDN·JavaScript·플러그인 없이 볼 수 있으며, 상단에서 원본 PDF를 열거나 다운로드할 수 있습니다.

- `index.html`: PDF 7쪽의 이미지와 문서 링크
- `styles.css`: 반응형 문서 뷰어
- `assets/page-01.png`부터 `page-07.png`: 최종 PDF의 130 DPI 렌더 원본
- `assets/huicheol-lee-data-engineer.pdf`: 최종 제출용 PDF 원본

첫 페이지를 우선 불러오고 나머지 페이지는 브라우저의 지연 로딩을 사용합니다. PDF를 바꾸면 7쪽 이미지도 함께 갱신합니다. GitHub Pages의 기존 `main` 브랜치 루트 배포 설정을 사용합니다.

앱 소스 저장소와 업무 원본 자료는 포함하지 않습니다. HTML의 `noindex`는 검색 엔진에 색인 제외를 요청하는 설정이며 접근 제한 기능은 아닙니다.
