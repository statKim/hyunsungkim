---
# Wowchemy 홈페이지 위젯: News
widget: blank       # 빈 위젯 (본문을 그대로 출력)
headless: true      # 단독 페이지로 만들지 않음
active: true
weight: 10          # 홈에서의 순서 (작을수록 위). about.md의 weight보다 크게.
 
title: Recent News
subtitle: ''
 
design:
  columns: '1'      # 제목을 위에, 내용을 전체 폭으로
---
 
{{< news limit="5" more="news/" >}}
 