# -c


#include<stdio.h>

int main()
{
	int price=0;
	int bill=0;

	printf("��������");
	scanf("%d",&price);
	printf("������Ʊ��");
	scanf("%d",&bill);
	int t=bill-price;
	if(t>=0){
		printf("����%dԪ",t);
	}
	if(t<0){
		t=-t;
		printf("����%dԪ",t);
	}

	return 0; 
}
