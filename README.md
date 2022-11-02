# lab-dev-1
vücut kitle indeksi hesaplama

#include<stdio.h>
int main()
{
	int kilo,vki;
	float boy;
	
	printf("KILONUZU GIRINIZ: \n");
	scanf("%d" , &kilo);
    printf("BOYUNUZU GIRINIZ: \n");
	scanf("%f" , &boy);
	
	vki = (kilo/(boy*boy));
	
	printf("VUCUT KUTLE INDEKSINIZ %d OLARAK HESAPLANMISTIR. \n ", vki);
	
	if(vki<=18) 
	{
		printf("zayif");
	}
	
	else if(vki<=25)
	{
		printf("normal");
	}
	
	else if(vki<=30)
	{
		printf("fazla kilolu");
	}
	
	else if(vki<=35 && vki<=45)
	{
		printf("sisman");
	}
	
	else
	{
	    printf("asiri sisman");
	}
	
	return 0;	
}

