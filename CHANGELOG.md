# CHANGELOG — nail-urban-green-sample (네일어반 세이지 그린 시안 · B안)

## 2026-07-14 — 그린 변형 독립 레포로 분리
- nail-urban-sample의 index_green.html을 **루트 index.html로 승격**해 독립 레포/워커로 분리. 서브경로(/index_green.html) 캐시·경로 이슈로 타인에게 빈 페이지로 보이던 문제 해소가 목적.
- 내용은 A안(그레이지, nail-urban-sample)과 100% 동일 구조·기능(구글지도 Embed·마커·구글맵 길찾기·폼·라이트박스). **색만 차분한 세이지 그린**: accent #6F9A76 / CTA #4C7D5B(흰텍 4.78:1 통과) / deep #3F6A50 / bg #F3F6F1 / ink #36473A / 히어로마커 rgba(146,180,150,.40).
- 이미지 8종 self-host(A안과 동일 소스). CF 연결은 사용자가 대시보드에서 마무리 → nail-urban-green-sample.lgt3232.workers.dev 예상.
