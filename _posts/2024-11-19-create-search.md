---
layout: single
title: "검색엔진 등록하기. (google, naver)"
categories: blog
tag: study
---

# 1. Google Search Console

## 1-1. Google Search Console

- https://search.google.com/search-console
- 해당 주소로 들어가기
- 우측 URL 접두어에서 URL 본인 깃허브 주소 넣기
  ![](/assets/img/g_start.png)
- 계속 버튼 누르기
- 소유권 확인이라는 창을 확인할 수 있다.
- 파일 다운로드 하기

# 2. vscode

## 2-1. vscode

- 다운로드 한 파일을 index.html, LICENSE와 열에 옮기기
  ![](/assets/img/g_down.png)
- git add부터 push까지 진행하기

## 1-2.Google Search Console

- 파일 다운로드 한 칸에서 확인을 누르기
- 초록색 창으로 소유권이 확인 되었다고 확인하고 속성으로 이동 누르기
  ![](/assets/img/g_ok.png)
- sitemap으로 이동해서 새 사이트 맵 추가에 본인주소 옆에 sitemap.xml 입력하기
- 아래 제출된 사이트맵에 <span style="color:red">가져올 수 없음<span>이라고 뜨더라도 당황하기 말기
  ![](/assets/img/g_miss.png)
- 등록한지 얼마 되지 않았을 경우 나타나지 않음
- https://chojeonghyeon.github.io/sitemap.xml
- 다음과 같이 본인 주소 뒤에 /sitemap.xml을 넣고 확인하기
  ![](/assets/img/g_clear.png)
- 다음과 같은 화면이 나오면 정상적으로 등록되었다는 것을 알 수 있다.

# 3. 네이버 Search Advisor

## 3-1. 네이버 Search Advisor

- https://searchadvisor.naver.com/ 해당 주소로 들어가기
- 웹 마스터 도구 들어가기
  ![](/assets/img/n_start.png)
- 사이트 등록에 본인 블로그 주소 넣어주기
  ![](/assets/img/n_2.png)
- html 태그로 눌러주고, 아래 content 내용을 복사한다.
  ![](/assets/img/n_3.png)

# 4. vscode

## 4-1. vscode

- \_config.yml파일 "naver_site_verification:" 반영해주면 된다.
  ![](/assets/img/n_vscode.png)
- 변경한 내용을 git add, commit, push 과정을 통해 반영해주기

## 3-2. 네이버 Search Advisor

- 소유확인을 누르고 인증을 진행한다.
  ![](/assets/img/n_check.png)
- 해당 주소로 들어간다.
  ![](/assets/img/n_7.png)
- 요약, 리포트 등 다양한 내용들을 확인할 수 있다. 하지만 등록한다고 해서 바로 반영이 되는 것이 아니라서 짧게는 2-3일 길게는 한달이라는 시간이 걸린다.
  ![](/assets/img/n_8.png)
- 사이트맵 제출하기
  ![](/assets/img/n_9.png)
- Robots.txt 제출하기
  ![](/assets/img/n_10.png)
