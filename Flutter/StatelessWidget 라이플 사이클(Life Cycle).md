

![[Pasted image 20231018173145.png]]

- Constructor로 생성이되고 생성이 되자마자 build 함수가 실행됩니다.
- 이전 Container 예제와 마찬가지로 변경이 필요하면 새로운 위젯을 만들어버린다.
- 하나의 StatelessWidget은 라이플 사이클동안 단 한번만 build 함수를 실행한다.

![[Pasted image 20231018173226.png]]


2 : createState -> state를 만들어요 
3 : 상태를 만들면 intState(초기화)가 불립니다 = constructor도 불리지만 state에서 constructor는 하나도 중요하지가 않다
4 : 나중에
5 : 4번을 거치면서 더러운? 상태가 된다 
6 : 5번이 변경이 필요하다

8,9 : 죽는 상태가 된

## 파라미터가 바뀌었을때 생명주기


![[Pasted image 20231018173321.png]]


## setState를 실행했을때 생명주기

![[Pasted image 20231018173354.png]]