## 변수선언이란?
프로그램이 동작하기 위해서는 많은 값들을 메모리에 저장해야합니다. <br/>
예를들이 사용자에게 3이라는 값을 입력받아 화면에 출력하는 프로그램을 작성한다면, 사람에게 3을 입력받은 후 그것을 저장해 놓지 않는다면<br/>
방금 값을 입력했어도 컴퓨터는 해당내용을 알수없게 됩니다.

## 변수 선언 및 값을 넣는 방법
선언 기본형식 : TYPE name ;<br/>
### 예시:<br/>
```C
#include<stdio.h>

int main(void) {
    int age = 50;
    float PI = 3.14;

	return 0;
}
```

    
## 변수 TYPE  종류와 용도, 메모리 크기   
1) int   : 정수형 값 저장  , 4바이트<br/>
2) short : 정수형 값 저장  , 2바이트 , 작은 값에 사용<br/>
3) float : 실수형 값 저장  , 4바이트 , 작은 실수 값 사용<br/>
4) double: 실수형 값 저장  , 8바이트 <br/>
5) char  : 문자형 값 저장  , 1바이트 <br/>

<image src = https://github.com/kuj0210/Language/blob/master/C/img/1-1.png/>

#### 이미지로 들어간 소스코드 예시는 반드시 직업 타이핑 해보시길 바랍니다.
