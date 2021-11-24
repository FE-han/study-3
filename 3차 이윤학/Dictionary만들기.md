## 평균 구하기(평균 구하기!)

### 문제 설명

- Dictionary 선언,Value추출,삭제,추가<br>



### 자료 구조

- my_dict<br>
    - 타입 : dict
    - 저장 데이터 : {"사과":"apple","바나나":"banana","당근":"carrot"}



### 풀이 과정
```txt
1. 사전만들기

2. my_dict["사과"] 의 벨류 var1에 넣기

3. 당근 제거

4. 체리추가

```

### 코드 구현
```python
# 풀이과정 1,2,3
my_dict = {"사과":"apple","바나나":"banana","당근":"carrot"}
var1 = my_dict["사과"]
del my_dict["당근"]
my_dict["체리"] = "cherry"
print(my_dict)
```


점수 : 100/100 <br>
