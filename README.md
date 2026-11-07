# enkbooks 홈페이지

영어 교육 출판사 enkbooks(이엔케이북스)의 홈페이지입니다. GitHub Pages로 호스팅합니다.

## 책·자료 수정하는 곳

`index.html` 안의 `데이터 영역` 주석 아래에서 고칩니다.

- `BOOKS`: 교재 목록. 책을 추가하려면 한 항목을 복사해서 내용을 바꿉니다.
- `resources[].url`: 부가자료 파일 주소. 넣으면 "준비 중" 버튼이 "받기"로 바뀝니다.
- `resources[].access`: `"all"`(누구나) 또는 `"teacher"`(교사 회원).
- `SITE.shop.enabled`: 자체 판매를 열 때 `true`로 바꿉니다.
- `NOTICES`, `ERRATA`, `FAQ`: 공지사항, 정오표, 자주 묻는 질문.

지금 들어 있는 책 7권과 회사 소개 문구는 예시입니다.
