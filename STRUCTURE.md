# STRUCTURE · euisin-sample

```
euisin-sample/
├─ index.html              단일 파일 (CSS·JS 인라인)
├─ wrangler.toml           name = euisin-sample → euisin-sample.lgt3232.workers.dev
├─ .assetsignore           img/ · 문서 · index_*.html · _deploy · es-logo.png 배포 제외
├─ es-hahmlet.woff2        제목 (Hahmlet 600–700, 사용 글자만)
├─ es-pretendard.woff2     본문 (Pretendard 400–700, 사용 글자만)
├─ es-logo.webp            상자 로고 투명 (헤더 · 히어로) · es-logo.png 원본
├─ es-logo-light.webp      밝은 로고 (푸터)
├─ es-*.webp               사진 13장 (히어로 1 · 떡 3 · 맞춤 포장 3 · 트럭 1 · 손 3 · 기타)
├─ favicon.png / og-euisin.jpg
├─ img/                    다올 제공 원본 145장 (배포 제외 · 개인정보 사진 포함이라 절대 올리지 말 것)
└─ CHANGELOG.md / STRUCTURE.md
```

## 섹션 순서
헤더 → 히어로 → `#tteok`(주문장 표) → `#custom`(검정 면) → 출고 → 만드는 손 → `#order`(흰 면) → `#visit` → 푸터 + 모바일 `.quick`.

## 사진 추가 규칙
스티커 사진은 글자를 실제 크기로 확인. 개인 이름 · 아이 이름 · 인물 사진 · 타 단체명이 보이면 쓰지 않음(LESSONS §25).

## 전화번호 수정 (7곳)
`tel:050714066707` 링크 전부 + 표시 숫자 + head JSON-LD telephone. grep `0507-1406` / `050714066707`.

## 폰트 재생성
문구를 바꾸면 항상 빠진 글자 검사(LESSONS §26) · `pyftsubset … --name-IDs='*' --name-languages='*' --name-legacy`(§24).
