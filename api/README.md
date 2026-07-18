# api/ — 서버 함수 (파트 A·D)

Vercel serverless functions. Upstage API 키는 이 폴더의 코드에서만 사용한다(환경변수 `UPSTAGE_API_KEY`).

| 파일 | 파트 | 역할 |
|---|---|---|
| `parse-menu.js` | A (이식) | 메뉴판 사진 → Document Parse → 메뉴·가격 |
| `parse-query.js` | A (이식) | 검색 문장 → Solar → 예산·거리·태그 |
| `events.js` | D | 행동 기록 저장 |
| `recommend.js` | D | 추천 목록 + Solar 추천 이유 |

입출력 규격: `docs/api-contract.md` (동결)
