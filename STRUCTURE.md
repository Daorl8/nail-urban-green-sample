# STRUCTURE — nail-urban-green-sample (B안 · 세이지 그린)

단일 파일 정적 사이트 (스탠다드형 · 문의받기). Cloudflare Workers 정적 자산 배포.
**A안(그레이지)=nail-urban-sample 레포와 구조·기능 동일, 색만 세이지 그린.**

```
nail-urban-green-sample/
├─ index.html        # 세이지 그린 버전 (A안 index.html 복사 후 재색상)
├─ nu-hero.jpg       # 히어로 배경
├─ nu-about.jpg      # 소개 섹션
├─ nu-g1~g6.jpg      # 갤러리 6컷 (라이트박스)
├─ wrangler.toml     # CF Workers 배포 설정 (name=nail-urban-green-sample)
├─ .assetsignore     # 배포 제외 (.git 노출 방지 등)
├─ CHANGELOG.md
└─ STRUCTURE.md
```

## 디자인 토큰 (A안 대비 색만 변경)
- 팔레트: bg `#F3F6F1` + 세이지 accent `#6F9A76` / CTA `#4C7D5B` / deep `#3F6A50` + 딥 그린 잉크 `#36473A`. 히어로 마커=세이지 워시 rgba(146,180,150,.40).
- 타이포·구조·섹션 순서·스크립트는 A안과 동일.

## 배포
- 레포: github.com/Daorl8/nail-urban-green-sample → Cloudflare 연결(사용자) → nail-urban-green-sample.lgt3232.workers.dev (예상)
- A안(메인/우선 제안) = nail-urban-sample.lgt3232.workers.dev
