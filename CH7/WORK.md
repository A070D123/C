#  1+3+5+...399 (for loop)
```
#include <stdio.h>
#include <stdlib.h>
int main(void)
{
 int i,sum=0;
 for(i=1;i<=399;i++)			/* 計算1+2+...+10的結果 */
    sum+=i++;
 printf("1+3+5+...+399=%d\n",sum);	/* 印出sum的值 */
  
 system("pause");
 return 0;
}
```

# 2+4+6+...398
```
#include <stdio.h>
#include <stdlib.h>
int main(void)
{
 int i,sum=0;
 for(i=1;i<=298;i++)			/* 計算1+2+...+10的結果 */
    sum+=i++;
 printf("2+4+6+...+398=%d\n",sum);	/* 印出sum的值 */
  
 system("pause");
 return 0;
}
