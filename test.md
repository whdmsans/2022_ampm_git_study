# 조은문의 일기장
---
## 목차
* 자기소개    
* 내일 할일  
* 코드
---
### 자기소개
* 소프트웨어공학과 22학번 조은문
---
### 내일 할일
* 물리학실험 보고서
* 수학 과제
* c언어 과제
* 베이스 연습
* 영어 과제
* _친구랑 롤, 레식_
* __운동__
---
### 코드S
* n! 구하기
```CS
#include <stdio.h>

int main(void){
    int c = 0;
    int n = 1;
    int i;
    for(;;){
        scanf("%d", &n);
        if(n<0)
            printf("다시 입력하세요.");
        else
            break;
    }
    if(n>0){
        for(i=1;i<=n;i++){
            c *= i;
        }
    }
    else
        c = 1;
    
    printf("%d", c);

    return 0;
}
```