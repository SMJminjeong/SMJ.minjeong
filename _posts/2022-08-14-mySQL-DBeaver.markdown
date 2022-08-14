---
layout: post
title:  "M1에서 mySQL 설치 및 DBeaver 연동하기"
date:   2022-08-14 21:22:54 +0900
categories: jekyll update
---
brew install mysql : mySQL 설치
	mysql.server start : mySQL 서버 시작 -> SUCCESS! 떠야함
	비밀번호 설정 할 것인지 묻는 질문 - y
	비밀번호 설정 (단계별로 0/1/2)
	나는 1단계 Mysql123!로 설정 완료
	나오는 모든 질문 y로 입력
	
	mysql -uroot -p비밀번호  //비밀번호 입력 후 접속
 	mysql> 이라고 뜨면 실행 완료
	
	\q 실행 종료
	mysql.server stop //서버 종료
	brew services start mysql //실행
	mysql -uroot -p비밀번호 //wjqthr
	brew services stop mysql //종료 

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
