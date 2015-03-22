
	* Basic philosophy : simple, zero to one .
	* Design philosophy : 클리앙이나 디시인사이드의 간지.
	* Title : "자랑" 포함
		* 2메가 자랑소 
		* 2메가 자랑갤 
		* 부럼순 (buromsoon)

	* DB명 - buromsoon.
	* Table명 - buromsoon_board.
		* 인덱스넘버 idx int(10) AUTO_INCREMENT PRIMARY KEY 
		* 내용 content varchar(80) = (40자) 내용이면서 동시에 제목 역할. 제목에 들어갈 때는 글자수 제한
		* 아이디 userid varchar(50) 
		* 비밀번호 userpw varchar(50) OLD_PASSWORD 
		* 업로드일자 regdate datetime 
		* 사진 업로드 upload_file 데이터타입? 인물사진 업로드 금지 - 초상권 문제. 용량 2메가바이트 이하 혹은 화소 떨어뜨리는       방법 구현

	* 자랑하기, 평가하기 버튼 생성.
	* 로그인 불필요. 수정 불가. 삭제 필요.
	* 각 자랑갤러리에 "이 프로젝트 만든 게 자랑" 식으로 업로드.
	* 필요 기술.
		* bootstrap. mobile first
		* jQuery mobile
		* jQuery ajax
		* php
		* mysql
