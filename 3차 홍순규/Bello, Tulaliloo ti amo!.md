## Bello, Tulaliloo ti amo!

### 문제 설명

- 영화 <슈퍼 배드>에 나오는 미니언즈는 Minionese라고 하는 신기한 언어를 사용합니다.
우리가 미니언 용어를 모르기 때문에 Minionese를 한국어로 번역해주는 사전을 하나 만들고자 합니다.

아래 미니언 용어 사전을 참고해서
key = Minionese, value = 한국어인 Dictionary를 변수 miniWord에 담아봅시다.

### 자료 구조

- **cvs**
    - 타입 : 리스트
    - 저장 데이터 : 미니언들이 한 말들이 리스트

- **miniWord**
    - 타입 : 사전형
    - 저장 데이터 : 미니언 용어 사전

### 풀이 과정

```txt
1. Minionese와 한국어가 담긴 miniWord 딕셔너리를 선언하고

2. miniWord를 이용해 cvs에 담긴 리스트에 해당하는 값 출력
```

### 코드 구현
- 사용 언어 : 파이썬

```python
cvs = ["Bello", "Bello", "Tulaliloo_ti_amo", "Tank_yu", "Poopaye", "Poopaye"]

# Minionese와 한국어가 담긴 miniWord 딕셔너리를 만드세요.
miniWord = {"Bello":"안녕","Poopaye":"잘가","Tank_yu":"고마워","Tulaliloo_ti_amo":"우린 너를 사랑해"}

for i in cvs:
    print(miniWord[i])
```

- 점수 : 100점 / 100점
