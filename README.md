# c-
关于c语言的学习记录
//指针数组
/*#include <stdio.h>
int main()
{
	int a=1;
	int b=2;
	int c=3;
	int d=4;
	int e=5;
	int *p1[5]={&a,&b,&c,&d,&e};
	int i;
	for(i=0;i<5;i++)
	{
		printf("%d\n",*p1[i]);//"*"是取地址符，可以取出1 2 3 4 5
	}
	return 0;
 }*/

 #include <stdio.h>
 int main()
 {
 	char *p1[5]={"啦啦啦"
	 			 "666我的宝贝"
				  "RNM,退钱"
				  "LALALA"
				  "LUELUELUE"};
	int i;
	for(i=0;i<5;i++)
	{
		printf("%s/n",p1[i]);//此处不用取地址符是因为要打印出的字符及地址名
	 } 
 	return 0;
 }
