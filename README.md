#include <stdio.h>
int sub(int a,int b)
{
    return a+b;
}
int main()
{
    int c,d;
    scanf("%d%d",&c,&d);
    int res=sub(c,d);
    printf("%d",res);
}
