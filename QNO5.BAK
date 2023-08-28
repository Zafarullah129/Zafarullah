#include<stdio.h>
#include<conio.h>
int main ()
{
clrscr();
	int amount ;
	int denominations[8]={500,100,50,20,10,5,2,1};
	int counts [8]={0};

	printf("Enter any amount:");
	scanf("%d",&amount);

	for (int i =0; i<8; i++)
	{
	counts[i]=amount/denominations[i];
	amount%=denominations[i];
	}
	printf(" denominations :\n");
	for ( i=0;i<8;i++)
	{
	printf("%d \t",denominations[i]);
	}
	 printf("\n");
	printf("counts:\n");
	for ( i=0;i<8;i++) {
	printf("%d\t",counts[i]);
	}
	getch();

	return 0;
	}