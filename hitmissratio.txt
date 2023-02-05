#include<stdio.h>

int Hit_ratio(){
	float hr,mr;
	printf("Enter the hit ratio: ");
	scanf("%f",&hr);
	printf("Enter the miss ratio: ");
	scanf("%f",&mr);
	printf("\nHit_ratio: %f",hr/(mr+hr));
	
	
    return 0;
}

int Miss_ratio(){
	float hr,mr;
	printf("Enter the hit ratio: ");
	scanf("%f",&hr);
	printf("Enter the miss ratio: ");
	scanf("%f",&mr);
	printf("\nMiss_ratio: %f",mr/(mr+hr));

    return 0;
}

void main(){
	int op;
	
	printf("Enter the option:\n1)Hit_ratio\n2)Miss_ratio\t:");
	scanf("%d",&op);
	
	printf("\n");
	
	if(op==1)
	  Hit_ratio();
	else if(op==2)
	  Miss_ratio();
	else
	  printf("Wrong option...!");
	
}