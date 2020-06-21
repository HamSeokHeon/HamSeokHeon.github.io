---
title: Categories
date: 2020-06-21 18:17:00
categories:
- Foo
- Bar
- Baz
---

This is a highlight test.



```C++
#include<stdio.h>
int main()
{
    int A,B,C;
    int num[10]={0};
    unsigned int h;
    scanf("%d",&A);
    scanf("%d",&B);
    scanf("%d",&C);
    h=A*B*C;
    while(h!=0)
    {
        num[h%10]=num[h%10]+1;
        h=h/10;    
    }
    for(int i=0;i<10;i=i+1)
    {
        printf("%d\n",num[i]);
    }
    
}
 
```



 



