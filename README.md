# 내성균 격리환자 현황 지도 — 인천나은병원

감염관리실 내성균(AMR) 격리환자 현황을 평면/입체 지도로 시각화합니다.

## 파일 구조
```
index.html   ← 비밀번호 보호 진입 페이지 (이것만 GitHub Pages 루트에)
flat.html    ← 평면 지도
3d.html      ← 입체 Three.js 지도
```

## 비밀번호 변경
`index.html` 상단 스크립트의 `PASSWORD` 값을 수정하세요:
```js
const PASSWORD = 'naeun2026';  // ← 여기 변경
```

## GitHub Pages 설정
1. 저장소 Settings → Pages → Branch: main / (root)
2. URL: https://naeun-id.github.io/isolation-map/

## 날짜 업데이트
새 날짜 데이터 추가 후 `flat.html`, `3d.html` 만 교체하면 됩니다.
