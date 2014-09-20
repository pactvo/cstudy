#include <stdio.h>
#include <stdlib.h>

int main(void)
{
    int choice,arrnum=2;
    int i=0,j;
    char datainfo[2][10];
    printf("================직원관리 프로그램V0.1=================\n");
    printf("제작자: pactvo, penguin, mosehun\n");
    printf("1.데이터 추가 2.데이터수정 3.사장님호출\n\n");
    printf("선택 : ");
    scanf("%d", &choice);
    
 if(choice == 1)
 {
        while(i<arrnum)
  {
   printf("[%d]번째 직원 이름 : ");
   scanf("%s",i+1 ,&datainfo[i]);
   i++;
  }
   for(i=0; i<arrnum; i++)
   {
    printf("[%d]번째 직원 이름 : %s\n", i+1,datainfo[i]);
   }
 }
 
    system("PAUSE");
    return 0;
}
