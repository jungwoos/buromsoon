
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
		* 사진 업로드1 file_name_0 varchar(100) 인물사진 업로드 금지 - 초상권 문제. 용량 2메가바이트 이하 && jpg, 		  jpeg, gif, png 확장자 아닌 파일 업로드 불가.
		* (추후 확장시 추가할)사진 업로드2 file_name_1(100)
		* 임시 사진 저장 file_copied_0 varchar(100)
		* (추후 확장시 추가할)임시 사진 저장 file_copied_1 varchar(100)
		* 추천 recommend int(10) 두 사진 중 하나를 택했을 때 + 1. 그래야 나중에 정렬할 수 있지 않을까?
		* (jw)내가 알기론 int(10) -> int로 수정해도 동작할듯. 코드를 봐야 확실히 알겠지만..
	* 자랑하기, 평가하기 버튼 생성.
	* 로그인 불필요. 수정 불가. 삭제 필요.
	* 각 자랑갤러리에 "이 프로젝트 만든 게 자랑" 식으로 업로드.
	* 필요 기술.
		* bootstrap. mobile first
		* jQuery mobile
		* jQuery ajax
		* php
		* mysql
