# python
CH1 파이썬 문법
자료형
숫자형
정수 : 123.-20. 0
실수 : 123.45.-4321.5. 6.08e9
8진수 : 0o456. 0o123
16진수 : 0xFF. 0x00. 0x0A

변수
문자 또는 밑줄로 시작(beta,_kim)
대소문자를 구분한다.(sum, Sum, SUM)
영문자, 숫자, 밑줄(a-z, 0-9,_)
파이썬 키워드는 사용 불가

a = 10
b = 20
c = a + b
print(c)
     
30

a = 52
b = 10
c = a/b # 나눗셈
d = a-b
e = a*b
f = a//b # 몫
g = a%b # 나머지
print(c,d,e,f,g)
     
5.2 42 520 5 2

from binascii import b2a_base64
a = 10
b = 2
# 나눗셈
c = a/b
d = a//b
e = a%b
f = a*b
g = a**b
print(c,b,e,f,g)
     
5.0 2 0 20 100
문자열
큰 따옴표 : "Hello World!"
작은 따옴표 : '대한민국'
큰 따옴표 3개 : """hello!"""
작은 따옴표 3개 :
'''나랏 말쌓미 뒹궐에 다라
엔터도 먹음'''


myName = "Kim" # 카멜
my_name = "김" # 스네이크
MyName = "kk" # 파스칼
_my_name = "kim"
MYNAME = "Kim"
my2name = "123kim"
# 숫자 마이너스 스페이스바 안됨
myStr = '123' # str
myNum = 123 # int

print(myStr, myNum)
print(type(myStr))
print(type(myNum))
     
123 123
<class 'str'>
<class 'int'>
여러개 변수 할당

x,y,z = "포도","딸기","수박"
print(x)
print(y)
print(z)
     
포도
딸기
수박

a = b = c = "오렌지"
print(a)
print(b)
print(c)
     
오렌지
오렌지
오렌지

fruits = ["포도","딸기","수박"]
x,y,z = fruits
print(x)
print(y)
print(z)
     
포도
딸기
수박

x = "life"
y = "is"
z = "beautiful"
print(x,y,z)
print(x+y+z)
     
life is beautiful
lifeisbeautiful

a = 1
b = 2
c = 3
print(a,b,c)
print(a+b+c)
     
1 2 3
6
데이터 유형
텍스트
숫자
불 (bool)

a = 100
b = 200
sum = a + b
print(a,'+', b, '=', sum)

sum = a - b
print(a, '-', b, '=', sum)

sum = a * b
print(a, '*', b, '=', sum)

sum = a / b
print(a, '/', b, '=', sum)
     
100 + 200 = 300
100 - 200 = -100
100 * 200 = 20000
100 / 200 = 0.5
