# Python 기초 문법 정리

> Python을 처음 시작할 때 알아두면 좋은 핵심 문법들을 간단히 정리한 문서입니다.

---

## 소개

Python은 문법이 간결하고 읽기 쉬워서
입문용 프로그래밍 언어로 많이 사용됩니다.

이 문서에서는 다음 내용을 다룹니다.

- 변수
- 조건문
- 반복문
- 함수 기초

---

## 목차

1. 변수
2. 조건문
3. 반복문
4. 함수 기초
5. 마무리

---

# 1. 변수

변수는 데이터를 저장하는 공간입니다.

## 문자열 변수

```python
name = "Python"
print(name)
```

---

## 숫자 변수

```python
age = 20
height = 175.5

print(age)
print(height)
```

---

## 여러 변수 사용

```python
x = 10
y = 20

print(x + y)
```

---

# 2. 조건문

조건문은 특정 조건에 따라 코드를 실행합니다.

## if 문

```python
age = 18

if age >= 18:
    print("성인입니다.")
```

---

## if ~ else 문

```python
age = 15

if age >= 18:
    print("성인입니다.")
else:
    print("미성년자입니다.")
```

---

## elif 사용

```python
score = 85

if score >= 90:
    print("A")
elif score >= 80:
    print("B")
else:
    print("C")
```

---

# 3. 반복문

반복문은 같은 작업을 여러 번 수행할 때 사용합니다.

## for 문

```python
for i in range(5):
    print(i)
```

출력 결과:

```text
0
1
2
3
4
```

---

## 리스트 반복

```python
fruits = ["apple", "banana", "orange"]

for fruit in fruits:
    print(fruit)
```

---

## while 문

```python
count = 0

while count < 5:
    print(count)
    count += 1
```

---

# 4. 함수 기초

함수는 반복해서 사용하는 코드를 묶는 기능입니다.

## 함수 정의

```python
def hello():
    print("Hello Python")
```

---

## 함수 호출

```python
hello()
```

---

## 매개변수 사용

```python
def greet(name):
    print("안녕하세요,", name)
```

호출:

```python
greet("밤톨")
```

---

## 반환값 사용

```python
def add(a, b):
    return a + b

result = add(10, 20)

print(result)
```

---

# 5. 마무리

이번 문서에서는 Python의 가장 기본적인 문법들을 정리했습니다.

Python은 기초 문법이 단순하고 직관적이라
자동화, 데이터 분석, AI, 웹 개발 등 다양한 분야에서 활용됩니다.

다음 단계에서는 아래 내용을 공부해보면 좋습니다.

- 리스트와 딕셔너리
- 클래스
- 파일 입출력
- 예외 처리
- 모듈 사용법

꾸준히 직접 코드를 작성해보는 것이 가장 중요합니다 🚀