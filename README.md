# google_image_crawling
- 본 글은 23.06.20에 작성되었습니다.
    - 23.07.01 수정사항: img_url, img_name 변경
    - 23.07.03 수정사항: 셀레니움 4.7 -> 4.8 (원인 파악 불가, elem.send_keys(searchKey) 부분에서 ElementNotInteractableException 에러 발생, 셀레니움 버전 바꾸니 해결완료)
- 해당 크롤링 코드는 코랩에서 돌아가도록 작성되었습니다.
- 현재 셀레니움이 4.10으로 업데이트 되면서 크롬 드라이버 불러올 때 변수 지정 방식에 변화가 있습니다.
- 해당 부분에서 에러가 나서 사용하지 못하는 분들, 저처럼 4.7버전으로 다운그레이드해서 사용하시면 에러나지 않습니다.
