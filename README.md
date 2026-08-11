# 신동와인 손익 페이지

비밀번호로 보호된 손익 분석 페이지 모음. 모두 StatiCrypt(AES-256)로 암호화된 단일 HTML이며, 열람 시 비밀번호가 필요합니다.

| 페이지 | URL | 내용 |
|---|---|---|
| `index.html` | https://stonggold.github.io/sdw/ | 손익보고서 — 손익분기점(BEP) 계산기 + 부서별 손익 탭(엑셀 업로드) |
| `monthly.html` | https://stonggold.github.io/sdw/monthly.html | 월별손익 대시보드 — 월 누계 손익 전년동기 비교 (2026년 7월 누계) |

- 원본 소스는 저장소에 포함되지 않습니다. (`monthly.html` 원본: `바탕화면\AI\월별손익_대시보드.html`)
- 갱신 방법: 원본 HTML을 수정한 뒤 같은 비밀번호로 StatiCrypt 암호화하여 덮어씁니다.
  salt는 `.staticrypt.json`에 고정돼 있으므로 같은 디렉터리에서 실행해야 기존 비밀번호가 유지됩니다.
