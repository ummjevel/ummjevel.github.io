---
layout: post
title:  "github blog - 댓글 설정"
date:   2020-08-29
categories: [github blog]
tags: [github, jekyll, plainwhite]
---

## 개요

생성한 github 블로그에 댓글을 추가한다.


## 환경

macOS Catalina 10.15.6


## 설정

1. [DISQUS](https://disqus.com/) 접속해서 회원가입
2. Universal Code 발급받기.  
   
    Settings 로 이동  

    <img width="1010" alt="스크린샷 2020-08-30 오후 2 16 14" src="https://user-images.githubusercontent.com/49097057/91651780-b2f6c980-eacb-11ea-854a-620698e6baa1.png">
    
    Add Disqus To Site 클릭,   

    <img width="204" alt="스크린샷 2020-08-30 오후 2 19 48" src="https://user-images.githubusercontent.com/49097057/91651791-e89bb280-eacb-11ea-872b-9705b1c6826a.png">

    
    하단의 GET STARTED 버튼 클릭,  
    I want to install Disqus on my site 클릭 후,  
    사이트주소 입력  
    ( [아이디].github.io 라고 입력,  여기서 입력하는 주소가 disqus_shortname 이 되는 것을 이후에 볼 수 있다.)  
    하단의 Basic Plan 선택 (이게 free)  
    하단의 Universal Code 선택
    나오는 코드를 포스팅 페이지의 공통 레이아웃에 붙여넣기 하면 되는데,


    내가 쓰는 테마의 경우 README.md 에 disqus_shortname 만 넣어주면 작동한다고 설명이 나와있었다.  

    <img width="817" alt="스크린샷 2020-08-30 오후 2 28 44" src="https://user-images.githubusercontent.com/49097057/91651902-22b98400-eacd-11ea-9806-bf86236f22d7.png">

    포스트 레이아웃을 한번 확인해보면, 이렇게 되어있다. 
    Universal code 복사하여 넣는 내용과 거의 일치한다.

    <img width="939" alt="스크린샷 2020-08-30 오후 2 30 51" src="https://user-images.githubusercontent.com/49097057/91651936-82179400-eacd-11ea-948a-72c615e7f150.png">


    _config.yml 에 설정해준다.

    ~~~
    plainwhite:
        ...
        disqus_shortname: [아이디]-github-io
    ~~~

    왜 ' . ' 대신 ' - ' 으로 설정해주었냐면,  
    universal code 내용을 보면 아래 이미지에  .disqus.com 전의 주소가 저렇게 되어있다.  
    아래 빨간색 박스로 표시한 부분이 위 이미지의 보라색 부분 주위에 상응하기 떄문이다.  


    <img width="925" alt="스크린샷 2020-08-30 오후 2 36 30" src="https://user-images.githubusercontent.com/49097057/91652031-429d7780-eace-11ea-88c2-c1003a6392c9.png">


3. 쿨타임 이후에 사이트에서 게시물 조회 시 하단에 댓글창이 생기는 것을 확인하면 된다.
   
   <img width="1061" alt="스크린샷 2020-08-30 오후 2 41 00" src="https://user-images.githubusercontent.com/49097057/91652099-e25b0580-eace-11ea-8626-93ecce22c5cb.png">



