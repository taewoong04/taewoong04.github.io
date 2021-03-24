---
layout: single
title:: "C language"
---

## C 언어

**변수 출력**

~~~c
#include <stdio.h>

int main()
{ 
char 학점; 
printf("grade : "); 
scanf("%c", &학점); 
printf("학점 = %c\n", 학점); 
return 0; 
}

[출력 결과]
grade : 

변수를 A,B,C,D,E,F로 설정하면
"학점= "에 설정 변수가 출력된다. 
