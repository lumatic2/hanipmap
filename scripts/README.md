# scripts/ — 자동 수집 (파트 A)

- `crawl-cafeteria.js`: 성균관대 학식 페이지에서 오늘 식단을 읽어 `cafeteria_menus` 테이블에 저장. 하루 1회 실행.
- `seed-places.js`: 네이버/카카오 Local API로 명륜동 식당의 이름·좌표·주소를 `places` 테이블에 일괄 등록.

메뉴·가격은 여기서 수집하지 않는다. 메뉴·가격은 팀 실촬영 사진을 제보 기능으로 입력한다(결정 사항).
