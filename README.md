# buromsoon
심플이 철학
디자인 철학 : 클리앙 디시 같은 느낌

네이밍 : 자랑 포함

2메가 자랑소(가제)
2메가 자랑갤 - 
부럼순 (buromsoon)

DB 스키마..

인덱스 idx int ai pk
내용 content varchar(80) = 제목 (40자) 제목에 들어갈 때는 글자수 제한
닉네임 nickname varchar(50)
비밀번호 userpw varchar(50) OLD_PASSWORD
업로드일자 regdate datetime
사진 업로드 (1장) upload_file (인물사진 업로드 금지, 용량 2메가바이트 이하 혹은 화소 떨어뜨리는 방법 구현)


자랑하기, 평가하기 버튼 생성
로그인 불필요
수정 불가
삭제 필요

자랑갤에 이 프로젝트 만든 게 자랑. 식으로 업로드
