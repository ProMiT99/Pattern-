//For pattern 1
#include<stdio.h>
int main()
{
    int i,n,j;
    scanf("%d",&n);
    for(i=0;i<n;i++)
    {
        for(j=0;j<n;j++)
        {
            printf("*");
        }
        printf("\n");
    }
    return 0;
}
//For pattern 2
#include<stdio.h>
int main()
{
    int i,n,j,p;
    scanf("%d",&n);
    scanf("%d",&p);
    for(i=0;i<n;i++)
    {
        for(j=0;j<p;j++)
        {
            printf("*");
        }
        printf("\n");
    }
    return 0;
}
//For pattern 3
#include<stdio.h>
int main()
{
    int i,n,j;
    scanf("%d",&n);
    for(i=1;i<=n;i++)
    {
        for(j=0;j<i;j++)
        {
            printf("*");
        }
        printf("\n");
    }
    return 0;
}
//For pattern 4
#include<stdio.h>
int main()
{
    int i,n,j;
    scanf("%d",&n);
    for(i=1;i<=n;i++)
    {
        for(j=1;j<=n-i;j++){
         printf(" ");
        }
        for(j=1;j<=i;j++)
        {
            printf("*");
        }
        printf("\n");
    }
    return 0;
}
//For pattern 5
#include <stdio.h>
int main()
{
	int i,j,n,k;
    scanf("%d",&n);
	for (i=0; i<n; i++) {

		for (j=0; j<2*(n-i)-1;j++) {
			printf(" ");
		}
		for(k=0; k<2*i+1; k++) {
			printf("* ");
		}
		printf("\n");
	}
	return 0;
}
//For pattern 6
#include <stdio.h>
int main()
{
	int n,i,j,k;
	scanf("%d",&n);
	for(i=0;i<n;i++){
		for (j=0;j<2*i;j++) {
			printf(" ");
		}
		for(k=0;k<2*(n-i)-1;k++) {
			printf("* ");
		}
		printf("\n");
	}
}
//For pattern 7
#include <stdio.h>
int main()
{
	int n,i,j,k,x;
	scanf("%d",&n);
	for(i=0;i<2*n-1;i++) {
		if(i<n) {
			x=2*(n-i)-1;
		}
		else{
			x=2*(i-n+1)+1;
		}
		for(j=0;j<x;j++) {
			printf(" ");
		}
		for(k=0;k<2*n-x;k++) {
			printf("* ");
		}
		printf("\n");
	}
	return 0;
}

THANK YOU.....
