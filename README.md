#include<stdio.h>
#include<string.h>
#include<stdlib.h>
#include<ctype.h>
int main()
{
	char a[100];
	char b[100];
	int n,c=0,i;
	printf("请输入：\n");
	gets(a);
	n=strlen(a);
	for(i=0;i<n;i++)
	{
     a[i]=tolower(a[i]);

	}
   
	printf("请输入一个想要统计的字符（小写）：\n");
      gets(b);
	for(i=0;i<n;i++)
	{   
        
		if(a[i]==*b)
		{
	
		 c++;
		}
	}
	printf("%d\n",c);
	return 0;
}
