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
