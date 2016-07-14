#include<stdio.h>
#include<string.h>

int main()
{
	char a[20],ch[20];
	int num[20];
	int i,j=0,d=1,t,s=0,len;

	gets(a);

	len=strlen(a);

	for(i=len-1;i>=0;i--)
	{
		if(a[i]>=48 && a[i]<=58)
		{
			t=a[i]-48;
			s=s+(t*d);
			d=d*10;
		}
		else if((a[i]>=97 && a[i]<=123) || (a[i]>=65 && a[i]<=90))
		{
			num[j]=s;
			ch[j]=a[i];
			s=0;
			d=1;
			j++;
		}
	}
	for(i=j-1;i>=0;i--)
	{
		for(t=0;t<num[i];t++){
			printf("%c",ch[i]);
		}
	}

return 0;
}
