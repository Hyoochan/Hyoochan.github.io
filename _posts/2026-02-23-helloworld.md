---
layout: post
title: "Hello, World!"
date: 2026-02-23
categories: []
tags: []
---
###### 이 글은 씹어먹는 C언어의 강의를 바탕으로 공부용으로 내용을 정리하고 추가하여 올린 것입니다.

# "Hello, World!" 출력하기
```c
#include <stdio.h>
int main() {
  printf("Hello, World!");
  return 0;
}
```

위 코드를 컴파일하고 실행을 하면 Hello, World!가 출력되는 것을 볼 수 있다.

## "Hello, World!" 코드 분석

```c
#include <stdio.h>
```
위 코드는 stdio라는 표준 입출력(Standard Input Output)에 관련된 .h 파일을 불러오라는 뜻이다.
> ###### .h는 헤더파일을 뜻한다. 헤더파일은 첫번째로 언급한 코드의 printf 같은 명령어들이 담겨있는 상자이다.

```c
int main() {}
```
위 코드는 main이라는 함수를 선언하고 main함수가 다 실행되었쓸때 정수(int)형태를 반환한다는 의미이다.
> ###### 함수가 아무리 여러개가 있어도 c로 작성된 프로그램은 main함수부터 실행된다. main함수는 오직 하나만 존재해야한다.
> ###### 화면에는 Hello, World!가 출력되었지, 정수 형태의 숫자가 출력되진 않았다. 이는 return 0; 명령어에 의해 0이라는 정수가 반환되었기 때문이다. 참고로 0은 프로그램이 아무 문제 없이 잘 실행되었다고 알리는 신호이다.
> ###### main()에서 ()는 main이 함수라는 것을 표시하기 위해 사용되었고 {는 main함수의 명령어가 여기서부터라는 시작점을 의미하고 }는 main함수의 명령어의 끝을 의미한다.
> 
> ###### 
