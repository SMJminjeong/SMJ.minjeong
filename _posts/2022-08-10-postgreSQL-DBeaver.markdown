---
layout: post
title:  "M1에서 postgreSQL 설치 및 DBeaver 연동하기"
date:   2022-07-06 19:45:38 +0900
categories: jekyll update
---
brew install postgresql : postgreSQL 설치
	sql postgres : postgres 연결
	create user postgres password '1234'; : 유저 생성 (이름 posdtgres/비밀번호 1234)
	create database testdb encoding 'utf-8'; : 인코딩 utf-8로 testdb생성
	alter database testdb owner to postgres; : postgres에게 tested 주인 설정
	grant all on database testdb to postgres with grant option; : 권한 부여 
	
	postgreSQL 나가기 : \q
Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
