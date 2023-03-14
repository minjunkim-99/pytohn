# pytohn
#**CH1 파이썬 문법**
## 자료형  
#### 숫자형  
* 정수 : 123, -20, 0  
* 실수 : 123.45, -423.24, 6.08e9  
* 8진수 : 0o456, 0o123  
* 16진수 : 0xFF, 0x0D, 0x0A
#### 문자열  
1.큰 따옴표 : "Hello World! it'\s"  
2.작은 따옴표 : '안녕하세요'  
3.큰 따옴표 3 : """Hello!"""  
4.작은 따옴표 4 : ''''대충 문장이 길면 작은 따옴표 4개 쓴다는 뜻''''  
#### 변수
* 문자 또는 밑줄로 시작 (alpha, beta, _kim)  
* 대소문자로 구분한다.(sum, Sum, SUM)
* 영문자, 숫자, 밑줄(a-z, 0-9,_)  
* 파이썬 키워드는 사용 불가
myName="minjun Kim" #카멜 표기법 약칭 낙타표기법
my_Name="김민준" #스네이크 표기법
MyName="kim" #파스칼 표기법
_my_Name="korea"
MYNAME="failed"
my2name="12345"
#틀린 예시 
#2myname='9876'
#my-name="6974"
#my name='00000'
myStr='123' # 작은 따옴표는 글자
myNum=123 # <--경우는 숫자
print(myStr,myNum)
print(type(myStr))
print(type(myNum))
####여러개 변수 할당
x,y,z="바나나","알러지","원숭이"
print(x)
print(y)
print(z)
fruit=["포도","사과","바나나"]
x,y,z=fruit
print(x)
print(y)
print(z)
x="Life"
y="is"
z="Beautiful"
print(x,y,z)
print(x+y+z)
a=1
b=2
c=3
print(a,b,c,)
print(a+b+c)
#### 데이터 유형  
+ 텍스트  
+ 숫자  
+ 불(Bool)  
a=10
b=3
c=a/b #나눗셈
d=a//b #몫
e=a%b #나머지
f=a*b #곱셈
g=a**b #제곱
print(c,d,e,f,g)
