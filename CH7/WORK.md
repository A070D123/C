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
```

# 1+3+5+399 (While Loop)
```
#include <stdio.h>
#include <stdlib.h>
int main(void)
{
   int i=1,sum=0;	/* 設定迴圈初值 */
   while(i<=399)    /* while迴圈，當sum小於100則繼續累加 */
   {
      sum+=i;
      printf("從1累加到%2d=%2d\n",i,sum);
      i+=2;
   }
   printf("必須累加到%d\n",i+2);
   system("pause");
   return 0;
}
```

```
#include <stdio.h>
#include <stdlib.h>
int main(void)
{
   int i=2,sum=0;	/* 設定迴圈初值 */
   while(i<=298)    /* while迴圈，當sum小於100則繼續累加 */
   {
      sum+=i;
      printf("從1累加到%2d=%2d\n",i,sum);
      i+=2;
   }
   printf("必須累加到%d\n",i+2);
   system("pause");
   return 0;
}
