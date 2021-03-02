# allen0530.github.io

這是我的第一個網站 ,也是我的第一個網頁

## 自我介紹
我叫朱永哲 綽號小豬

## 興趣
我喜歡打排球

```c
#include <stdio.h>
int main()
{
  printf("Hello World\n");
  return 0;
}
```


## 好玩的圖

[有一個網址](https://moodle.mcu.edu.tw/)

![圖片的名子](https://img.wreadit.com/member/158/blogId/easylifetw/149810/article_cover/149810-e23d80efef1f07da6989940f9352300b.png)
## 第一個程式
```c
#include <stdio.h>
int main()
{
	int a , b, c, d;
	scanf("%d",&a);
	printf("%d=50*%d+5*%d+1*%d\n",a,a/50,a%50/5,a%50%5/1);
	



}
```
## 第二個程式
```c
#include <stdio.h>
int main()
{
	int a,i,b=0;
	scanf("%d",&a);
	
	for(int i=1;i<=a;i++)
	{
		if(a%i==0)
		{
		b++;
		
		}
		}
	printf("%d\n",b);
	
		



}
```






## 第三個程式
```c
#include <stdio.h>
int main()
{
	int a,i,b=0;
	
	for(int i=0;i<10;i++)
	{
		scanf("%d",&a);
		if(a%3==0)
			b++;
	}
	printf("%d\n",b);
	
	





}
```




## 第四個程式
```c
#include <stdio.h>
int main()
{
	int a;
	scanf("%d",&a);
	if(a>=90) printf("A\n");
	else if(a<90&&a>=80) printf("B\n");
	else if(a<80&&a>=60) printf("C\n");
	else printf("F\n");
	




}
```






## 第五個程式
```c
#include <stdio.h>
int main()
{
	int a,b,i,ans=1;
	scanf("%d%d",&a,&b);
	for(int i=1;i<=b;i++)
	{
		if(a%i==0 && b%i==0)
			ans=i;
	}
	printf("%d %d\n",a/ans,b/ans);
	




}
```
