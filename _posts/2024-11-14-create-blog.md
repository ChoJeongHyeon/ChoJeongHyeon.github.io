---
layout: single
title: "블로그 만들기."
categories: blog
tag: study
---

# 1-1. Repository 생성하기

- github username, repository name 동일하게 생성
  <span style="color: blue">ex) ChoJeonghyeon -> ChoJeonghyeon.github.io</span>

## 1-2. 확인하기

- repository를 clone해서 안에 간단하게 html를 만들기
- add, commit, push 과정을 진행
- 1-1에서 만든 주소를 통해 정상적으로 html 잘 만들어졌는지 확인

# 2-1. 개발 환경 구축

- ruby
- jekyll
- bundler
- webrick 설치하기

## 2-2 테마 적용해서 잘 설치가 되었는지 확인하기

- 마음에 드는 테마를 본인이 클론한 저장소에 테마를 넣고
- bundle install
- bundle exec jekyll serve
- 위 과정을 통해 본인 주소로 들어가서 테마가 잘 적용되었는지 확인

### 나한테 나타난 오류 사항

- mac을 사용하는 유저로 ruby설치 과정이 달랐고 혼자서 이것저것 설치하는 과정에서 버전이 맞지 않아 Homebrew를 지우고 재설치를 진행하였다.
- gem install jekyll bundler명령어를 통해 jekyll와 bundler를 한번에 설치 했고 bundler 버전이 맞지 않아 버전을 맞추어 주었다.
