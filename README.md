<h1>팀프로젝트 프로젝트명: Connect Job</h1>

<h3>개발기간</h3> 
3.25 ~ 4.17

<h3>개발 목표</h3>
스프링을 이용하여 IT분야 직장인과 취업준비생을 위한 기업정보 탐색, 기업 리뷰, 구인/구직 서비스 회원이 작성한 이력서를 바탕으로 기업과 연결해주는 커뮤니티 웹 사이트 개발

<h3>개발 환경</h3> 
운영체제- Window10

서버- Tomcat8.5

사용 언어- Java, Javascript, Html, css

DB– oracle 11g

라이브러리, 프레임워크- Jquery, Bootstrap

IDE- 이클립스

<h3>DB설계</h3> 
<img width="889" alt="default" src="https://user-images.githubusercontent.com/36668707/65387315-2606a480-dd81-11e9-801f-682d968d9502.png">

<h3>구현기능</h3>

<h3>이메일 인증</h3>
먼저 회원 가입을 하면
이메일 인증이 안 되었기 때문에 인증을 해달라는
메시지창이 뜬다.

그리고 자신이 가입한 이메일을 확인해 보면 인증 메일이 도착한 것을 확인할 수 있다.
도착한 메일에서 이메일 
인증 확인이라는 것을 
클릭하면 이메일 인증이 
완료되었다는 메시지창이 뜨고 로그인 화면으로 이동한다.
<img width="889" alt="default" src="https://user-images.githubusercontent.com/36668707/65387500-0bcdc600-dd83-11e9-9993-804aa5312b1e.png">
<img width="889" alt="default" src="https://user-images.githubusercontent.com/36668707/65387509-2ef87580-dd83-11e9-9b08-b8b50da767f4.png">
<img width="889" alt="default" src="https://user-images.githubusercontent.com/36668707/65387545-45063600-dd83-11e9-81a4-05bbdfc7db0e.png">

<hr>

<h3>유효성 검사</h3>
직종, 질문유형, 제목과 내용 입력창이 비어있으면, 경고창이 뜸.
★이미지
<hr>

<h3>AJAX 이용한 댓글 기능</h3>
AJAX를 통해 아이디와 내용, 현재 날짜를 데이터베이스에 저장한다.
그리고 저장이 성공했다면, 저장된 아이디, 내용, 현재날짜를 조회해서 댓글 영역 하단에 출력한다.
★이미지
<hr>

<h3>페이징 처리</h3>
DB에서 전체 리스트 중에서 10개를 받아와서 화면에 페이지를 나눠준다.
질문들이 10개가 넘어가면 한 페이지씩 생성이 된다.
페이지가 10개가 넘어가서 11페이지 이상이면 다음 버튼을 눌러서 페이지를 이동시킬 수 있다.
★이미지
<hr>

<h3>개선사항</h3> 

1 코드 리팩토링
2 인터페이스 사용하여 클래스간 의존성 낮추기
3 테스트 코드 추가
