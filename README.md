# movtier · MindWeb

몹티어 — AI 없이 텍스트 유사도로 자동 연결되는 마인드맵 스위트.

## 앱 구성
- `index.html` — 랜딩 페이지
- `study.html` — 공부용: 노트 + 마인드맵 동기화, 사진 OCR 캡처
- `infinite.html` — 무한증식 키워드: 위키백과 기반 자동 확장 그래프
- `flashcard.html` — 암기용: 외국어 단어 플립카드, 사진 OCR로 단어 추가

## 배포
`main` 브랜치에 푸시하면 `.github/workflows/deploy.yml`이 자동으로 GitHub Pages에 재배포합니다.
별도 설정 없이 커밋 → 푸시만 하면 바로 반영돼요.

배포 주소: https://haroseo.github.io/movtier/
