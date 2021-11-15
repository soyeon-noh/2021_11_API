# API 연습용

## 도로명주소 API

- 2021-11-13 시작

## 팝업 API

### API정보

- 호출방식 : POST, GET
- 요청 URL : https://www.juso.go.kr/addrlink/addrLinkUrl.do
- 출력결과 : 파라미터

### 요청변수

- confmKey : String, 필수, 신청시 발급받은 승인키
- returnUrl : String, 필수, 주소 검색 결과를 리턴받을 URL (통합검색창을 호출한 페이지)
- resultType : String, 도로명주소 검색결과 화면 출력유형
  1 : 도로명, 2 : 도로명+지번+상세보기(관련지번, 관할주민센터), 3 : 도로명+상세보기(상세건물명), 4 : 도로명+지번+상세보기(관련지번, 관할주민센터, 상세건물명)
- useDetailAddr : String, 상세주소 동/층/호정보 제공여부
  Y : 제공, N : 미제공(직접입력)
  ※ 자세한 내용은 상세주소API 메뉴에서 '팝업API 적용방법'을 참고하시기 바랍니다.

### 출력결과

-
