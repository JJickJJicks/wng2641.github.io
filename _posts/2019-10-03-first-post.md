---
title: "Introducing Wiz Clock Project"
date: 20197-10-03 23:17:28 -0400
categories: test
---
## Wiz Clock Project를 소개합니다.

왜 타이머는 한 가지 시간만 작동해야 하는걸까요?
간단히 공부를 하더라도 50분 공부하고 10분 쉬는 형식인데 말이죠.
그래서 Wiz-Clock을 만들어봤습니다.

### How to work Advanced Timer?
타이머의 작동원리는 간단합니다.
ArrayList에 원하는 시간들을 저장하고 이를 순차적으로 불러와서 타이머를 작동시키면 됩니다.
다만 1-2-3의 타이머 세팅의 경우, 1-2에서는 Ending이 아닌 중간 종료라는 새로운 상태여야 되겠죠?

### Advanced Timer를 응용해보자!

Advanced Timer에서 시간 세팅을 만들면 이를 공유하고 싶어질 겁니다.
Google Firebase의 RDB를 이용하면 간단하게 Data 공유가 가능하며,
Authentication을 함께 사용하면 어느정도 무분별한 Data삽입을 막을 수 있다고 생각합니다.


### What do we have to do next?

역설적이게도 시계 어플의 기본이라 할 수 있는 알람 기능이 미구현 상태이며,
Authentication으로 막을 수 없는 무분별한 Data 삽입을 방지할 알고리즘 구현이 필요합니다.
