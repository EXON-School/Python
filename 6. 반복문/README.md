# 반복문
어떤 코드를 계속 반복하고 싶을 때 쓰입니다!<br>
여러가지 반복문 종류가 있으니 꼼꼼히 봐주세요!<br>

## for문
for문은 보통 이런 형식입니다.
```python
for 변수이름 in range(처음 값, 반복할 값):
    (코드)
```
해석을 해보자면, <br>
변수이름을 처음값부터 반복할 횟수-1까지 정하고 코드를 실행합니다. <br>
그러면
```python
for i in range(0, 10):
    print(i)
```
라고 한다면 0부터 9까지 총 10번을 반복할 것입니다. <br>
<img src="../images/for.png"> <br>
이렇게 말이죠

## while문
while문의 형식은 
```python
while 조건문:
    (코드)
```
조건문이 참(true)일 경우까지 반복한다는거죠.
예를 들어,
```python
i = 0
while i < 10: #i가 10보다 작으면 반복
    print(i)
    i = i + 1 #i에 1을 더한다
    #i가 10보다 작은 경우 다시 반복한다.
```
라고 한다면 0부터 9까지 10번을 반복합니다.
<img src="../images/for.png"> <br>

<br>
<br>
오늘은 반복문을 배워보았습니다!
