# 程式設計
### 使用三種迴圈完成1+5+9+..+401等差之總和
```
#include <stdio.h>
#include <stdlib.h>
int for_1(int x) /* for */
{
 int i;
 int total=0;
 for (i=1;i<=x;i+=4)
 {
  total+=i;
 }	 	   
 return total;
}
/*                                */
int while_1(int x) /* whille */
{
  int i=1;
  int total=0;
  while(i<=x)
 {
   total+=i;
   i+=4;	   
 }
  return total;
}
/*               */
int do_while1(int x) /* do while */
{
  int i=1;
  int total=0;
  do
	{
	 total+=i;
	 i+=4;
	}
  while(i<=x);
  return total; 	
}
int main(void)
{
    int n;
    printf("你要出多少:");
    scanf("%d",&n);
    printf("for       1+5+9+...+%d=%d\n",n,for_1(n));
    printf("while     1+5+9+...+%d=%d\n",n,while_1(n));
    printf("dowhile   1+5+9+...+%d=%d\n",n,do_while1(n));
    system("pause");
    return 0;
}	

