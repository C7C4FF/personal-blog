---
layout: post
title: "넷플릭스 추천 시스템"
subtitle: "공부한 내용 정리"
date: 2020-07-24 13:00:00 +0900
background: '/img/posts/06.jpg'
categories: ['programming', 'machine learning']
---

# Netflix Prize

넷플릭스는 자체 추천 알고리즘이 있었지만, Netflix Prize를 만들어 이미 가지고 있는 알고리즘을 개선하고자 했음. 제시된 문제는 현재 넷플릭스의 추천 시스템의 RMSE를 10% 가량 개선시키기. 머신러닝으로 실제 RMSE를 개선시키는 이 상의 상금은 10억 원 가량. 문제가 2006년 10월에 공지되었으니 알고리즘은 그 당시를 기준으로 평가되었다. (이 때의 RMSE는 0.9514) 1995 ~ 2005년 동안의 data로 Training set 1억개, Probe set 140만 개, Quiz set 140만개, Test set 140 만개 를 제공했다. 이 정도는 개인 컴퓨터에서 돌릴 수 있을만큼의 Data Set 이었고, 개발자들은 자신의 알고리즘을 평가하기 위해 하루에 한 번 정도 (최대 1번) Quiz Set에 자신의 알고리즘을 적용시켜 RMSE를 알 수도 있었다.

...     
이하의 내용은 노션에서 작성한 TeX 문법이 적용되지 않는 결과로 링크로 대체함

[노션링크](https://www.notion.so/Netflix-d75d16bef3cb443dba4fe31379464cbc)

---
연관 글     
[Recommendation](/2020-07-24-Recommendation.md)

---

참고 사이트

[Netflix Prize](https://en.wikipedia.org/wiki/Netflix_Prize)
[인터넷 속의 수학 - How does Netflix recommend movies? (1/2) - README](http://sanghyukchun.github.io/30/)
[NETFLIX PRIZE - 다이나믹 했던 알고리즘 대회 (2) - shalomeir's blog](http://www.shalomeir.com/2014/11/netflix-prize-2/)
