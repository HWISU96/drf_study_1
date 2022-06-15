# drf_study_1
과제

1. args, kwargs를 사용하는 예제 코드 짜보기
def ex(*args, **kwargs):
    for arg in args:
        print(arg)

    for key, value in kwargs.items():
        print(f"key = {key}, value = {value}")

myFun('django', 'drf', 'study', key1 ='value1', key2 ='value2', key3='value3')


2. mutable과 immutable은 어떤 특성이 있고, 어떤 자료형이 어디에 해당하는지 서술하기
mutable 은 변경가능한 객체이고, immutable 은 변경불가능한 객체이다.
mutable: 리스트(list)와 딕셔너리(dict)
immutable: 일반적인 자료형 int, string 등 과 튜플(tuple) 등


3. DB Field에서 사용되는 Key 종류와 특징 서술하기
FK : Foreign Key의 약자이며, 다른 테이블을 참조 할 때 사용된다.
UK : Unique Key의 약자이며, 중복 값을 허용하지 않는다.
PK : Primary Key의 약자이며, 테이블에서 반드시 존재해야 한다.
    - PK는 두개 이상 존재 할 수 없고, UK와 마찬가지로 중복 값을 허용하지 않는다.
    - Foreign Key를 사용할 경우 참조 할 테이블의 PK를 바라본다.


4. django에서 queryset과 object는 어떻게 다른지 서술하기
