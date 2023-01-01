# kotlin-blackjack

## 요구사항
합이 21 또는 21에 가장 가까운 숫자를 가지는 쪽이 이기는 게임
- [x] 플레이어에게 두 장의 카드를 지급
    - [ ] 21을 넘지 않을 경우 원한다면 얼마든지 카드를 계속 뽑을 수 있다.
- [ ] 결과 계산
  - [ ] 숫자 계산은 카드 숫자를 기본
  - [ ] 예외로 Ace는 1 또는 11로 계산
  - [ ] King, Queen, Jack은 각각 10으로 계산
```
게임에 참여할 사람의 이름을 입력하세요.(쉼표 기준으로 분리)
pobi,jason

pobi, jason에게 2장의 나누었습니다.
pobi카드: 2하트, 8스페이드
jason카드: 7클로버, K스페이드

pobi는 한장의 카드를 더 받겠습니까?(예는 y, 아니오는 n)
y
pobi카드: 2하트, 8스페이드, A클로버
pobi는 한장의 카드를 더 받겠습니까?(예는 y, 아니오는 n)
n
jason은 한장의 카드를 더 받겠습니까?(예는 y, 아니오는 n)
n
jason카드: 7클로버, K스페이드

pobi카드: 2하트, 8스페이드, A클로버 - 결과: 21
jason카드: 7클로버, K스페이드 - 결과: 17
```