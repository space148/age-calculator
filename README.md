#//factorial
#include<stdio.h>
main()
{
	int a=1,n,i;
	printf("\nenter factorial number\n");
	scanf("%d",&n);
	for(i=1;i<=n;i++)
	a=a*i;
	printf("\nfactorial of %d is %d",n,a);
}
