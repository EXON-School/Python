# 조건문
사용자가 입력한 값이 0보다 작으면 "음수입니다" 0보다 크면 "양수입니다" 0이면 "0입니다" 라고 하고 싶은데 어떻게 하지? <br>
조건문은 이러한 상황에 쓰입니다. <br>
그럼, 어떻게 쓰는지 알아볼까요? <br>
<br>
조건문은 이런 형태로 쓰입니다. <br>
```python
if(조건):
    (코드)
```

다음은 조건의 형식입니다. <br>
|같다면|다르다면|크다면|작다면|이상|이하|
|---|---|---|---|---|---|
|a == b|a != b|a > b| a < b|a >= b|a <= b|

## 코드
```python
a = int(input()) #정수 형식으로 입력받음
if (a == 0): #a가 0이면?
    print("0입니다.")
if (a < 0): #a가 0보다 작다면?
    print("음수입니다.")
if (a > 0): #a가 0보다 크다면?
    print("양수입니다.")
```