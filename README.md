# functions-1-
created by saisree

#include<stdio.h>
int sum(int a);
int main()
{
    int num,result;
    scanf("%d",&num);
    result=sum(num);
    printf("sum of digits:%d",result);
    return 0;
}
int sum(int num)
 {
    if(num!=0)
    {
        
      return(num%10+sum(num/10));
    }
else
  {
    return 0;
  }
}

