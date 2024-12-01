---
layout: single
title: "댓글 기능 추가하기."
---

# 1 Disqus

## 1-1. Disqus

- Get stared 버튼 누르기
  ![](/assets/img/disqus1.png)
- 프로필 작성하기
  ![](/assets/img/disqus2.png)
- 무료버전 구독하기

- Jekyll로 설정하기
  ![](/assets/img/disqus3.png)

# 2 vscode

## 2-1. vscode config.yml

- config.yml파일 맨 아랫쪽에 defaults: 에서 comments에서 '#' 제거하기
- config.yml파일 30번대 줄에 가면 provider에 내가 사용하는 웹 사이트 써주기 ex.disqus
- <span style="color:red">provider 아래 shortname 변경하기<span>
  - 찾기 어려움
  - Disqus -> settings -> General 에서 shortname 확인할 수 있다.
  - 이거 틀리면 안 돌아가니까 잘 적어줘야 한다.
    ![](/assets/img/disqus%20shortname.png)
