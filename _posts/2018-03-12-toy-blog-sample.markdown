---
layout: post
title: "안녕하세요! jekyll 에 글쓰는 중입니다."
date: 2018-03-12 13:45:35 +0900
categories: jekyll sample
---

#Github:pages 와 Jekyll 을 이용한 블로그 만들기

## Github 계정 생성하기

Github Desktop 을 실행하고 로그인을 합니다.

## Github 저장소 생성하기

![Github 저장소 생성](https://raw.githubusercontent.com/springloops-toy/img_sample/master/imgs/dt_log.png)

## Jekyll 설치

다음 명령어를 터미널을 이용해 실행합니다.

~~~bash
$ xcode-select —install

$ \curl -sSL https://get.rvm.io | bash -s stable

$ source ~/.rvm/scripts/rvm

$ rvm install 2.5.0

$ gem install jekyll bundle
~~~

## Jekyll 사이트 만들기
다음 명령어를 터미널을 이용해 실행하면 블로그를 만듭니다.

~~~bash
# cd github desktop에서 만든 저장소로 이동
$ cd /Users/min/play/toys/springloops-toy.github.io

$ jykell new .

$ jykell serve

~~~

## 글 써보기

| 테이블도 | 이렇게  | 그릴 수 있구요 |
|--------|--------|-----------|
| 1|  2      |3|
| 4|  5      |6|


