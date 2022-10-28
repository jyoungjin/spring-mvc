# spring-mvc

#### HTTP 요청
1. GET - 쿼리 파라미터
2. POST - HTML Form
3. HTTP message body에 데이터를 직접 담아서 요청 (POST, PUT, PATCH)

#### HTTP 응답
1. 정적 리소스
2. 뷰 템플릿
3. HTTP 메시지 사용

#### 요청 파라미터 vs HTTP 메시지 바디
1. 요청 파라미터를 조회하는 기능: @RequestParam , @ModelAttribute
2. HTTP 메시지 바디를 직접 조회하는 기능: @RequestBody