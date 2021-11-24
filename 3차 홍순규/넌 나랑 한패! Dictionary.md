## 넌 나랑 한패! Dictionary

### 문제 설명

- 사전형 자료를 만드는 방법을 익혀봅시다.

### 자료 구조

- **my_dict**
    - 타입 : 사전형
    - 저장 데이터 : 과일이름의 키와 값이 담긴 사전형자료

- **var1**
    - 타입 : 문자열
    - 저장 데이터 : my_dict에서 “사과”를 Key로 넣어 나온 Value

### 풀이 과정

```txt
1. my_dict 를 선언

2. var1 변수에 my_dict["사과"] 를 통해 나오는 값 저장

3. my_dict["당근"] 값 삭제

4. 새로운 값 추가
```

### 코드 구현
- 사용 언어 : 파이썬

```python
my_dict = {"사과":"apple", "바나나":"banana", "당근":"carrot"}

var1 = my_dict["사과"]
del my_dict["당근"]
my_dict["체리"] = 'cherry'
```

- 점수 : 100점 / 100점
