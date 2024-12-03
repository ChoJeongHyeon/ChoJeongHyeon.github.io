---
layout: single
title: "조회수-구글 analytics 추가하기."
categories: blog
---

# 1. google analytics

## 1-1. google analytics

- https://developers.google.com/analytics?hl=ko
- 링크로 들어가서 측정 시작하기 버튼 누르기
  ![](/assets/img/a_google_start.png)
- 절차에 따라서 가입 진행하기
  ![](/assets/img/a_new.png)
- 웹 스트림 세부정보에서 측정ID 확인하기
  ![](/assets/img/a_tracking_id.png)

# 2. vscode

## 2-1. vscode \_config.yml

- 1-1에서 복사한 측정ID
- vscode config.yml 100번대 줄로 가지고 오기
- analytics에서 proviser: "google-gtag"로 설정하기
- google: 에서 <span style="color:red">tracking_id: "복사한 측정ID" 넣어주기<span>
  ![](/assets/img/a_vscode.png)

# 3. 본인.github.io

## 3-1 조회수 확인하기

![](/assets/img/a_view.png)
