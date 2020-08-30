---
layout: post
title:  "github blog - 블로그 생성"
date:   2020-08-29
categories: github blog
tags: github blog github.io jekyll plainwhite jekylltheme
---

## 개요

github 블로그를 생성한다.  
휴학중에 있어 기록용으로 블로그를 개설하게 되었다.  
기존에 2번 정도 시도하였다.   
첫번째는 minimal mistakes 로, 테마 변경을 위해 두번째 시도를 하였으나 실패, 세번째로 plainwhite 로 다시 도전하게 되었다. 다행히 블로그는 문제없이 띄웠기에 포스팅을 하게 되었다.  
이전의 방법은 컴퓨터에 jekyll 과 ruby 등 로컬에서 실행하기 위한 설치를 하였지만 이 방법은 설치하지 않고 진행한다.  
(기력이 너무 소모되기 때문이다. 다른 블로그 참고) 

## 환경

macOS Catalina 10.15.6

## 만들기

1. Jekyll Theme 선택  
   [Jekyll Theme](http://jekyllthemes.org/)
   나는 [Plainwhite](http://jekyllthemes.org/themes/PlainWhite-Jekyll/) 를 선택했다.  
   homepage 를 선택해서 github 페이지로 이동한다.  

   <img width="731" alt="스크린샷 2020-08-30 오후 1 21 14" src="https://user-images.githubusercontent.com/49097057/91651177-7a072680-eac4-11ea-95cd-a98bd8df53f2.png">

2. fork  
    우측 상단에 fork 를 클릭한다.

    <img width="1199" alt="스크린샷 2020-08-30 오후 1 30 11" src="https://user-images.githubusercontent.com/49097057/91651222-0285c700-eac5-11ea-9dc2-c450ed89f6e4.png">

    자신의 repository 에 테마 이름은 그대로 repository가 생성된다.

3. Repository name 변경

    상단 우측의 Settings 메뉴에서
    Repository name 을 [아이디].github.io 로 변경한다.

    <img width="1026" alt="스크린샷 2020-08-30 오후 1 33 16" src="https://user-images.githubusercontent.com/49097057/91651275-cdc63f80-eac5-11ea-86d5-d89f66f397d2.png">

4. 쿨타임을 가진 뒤 Settings 에서 스크롤을 내려 확인하면 아래 이미지처럼 보이게 되고,   
   [아이디].github.io 에 접속하여 확인할 수 있다.
   
   <img width="882" alt="스크린샷 2020-08-30 오후 1 39 22" src="https://user-images.githubusercontent.com/49097057/91651311-3ca39880-eac6-11ea-98b6-a256520cd208.png">

5. _config.yml 설정  
   제목, 이메일이나 설명 등 자신의 정보에 맞게 내용을 수정한다.

6. git clone 해서 로컬에 저장한다.  
    
    clone 할 주소는 아래 이미지처럼 상단좌측의 code 탭에서 Code 버튼을 누르고, 클립보드 복사 버튼을 클릭하여 복사할 수 있다.

   <img width="878" alt="스크린샷 2020-08-30 오후 1 43 43" src="https://user-images.githubusercontent.com/49097057/91651373-fac72200-eac6-11ea-9d80-2d7541d3261f.png">

    그 후 markdown 파일(post 를 위한...)을 작성하고 add, commit, push 하면 포스팅이 된다.  
    포스팅 하는 markdown 파일은 _posts 폴더 하위에 존재해야하며, 파일명은 YY-MM-DD-title.md 가 규칙이다.

