#include <stdio.h>
#include <stdlib.h>

/* 4 kisinin bilgilerini ve randevu saatlerini girdigi,4 giristen sonra da 
randevu saatlerini gosteren randevu sistemi.*/

int main() 
{
int i,v;
long long tcno;
char annead[16],babaad[16],isim[16],soyisim[16],hizmet;
double randsaat,saatler[4][1];

for(i=0;i<4;i++)
{
	
printf("****X Konsoloslugu Randevu Sistemine Hosgeldiniz****\n\n");

printf("Kimlik numaranizi giriniz\n");
scanf("%lld",&tcno);
getchar();                                       //newline karakterini temizlemesi icin.

printf("Isminizi giriniz\n");
gets(isim);

printf("Soyisminizi giriniz\n");
gets(soyisim);

printf("Anne adinizi giriniz\n");
gets(annead);

printf("Baba adinizi giriniz\n");
gets(babaad);

for(randsaat=9.00;randsaat<9.60;randsaat+=0.15)
{
	printf("Uygun randevu saati: %.2lf\n",randsaat);
}


printf("4 Randevu saatinden secmek istediginizi yaziniz\n");
scanf(" %lf", &randsaat);
saatler[i][0]=randsaat;


do
{
	
printf("Vize Basvurusu icin V,Pasaport kaybi icin P harfini giriniz.\n");
scanf(" %c",&hizmet);

switch(hizmet)
{
 case 'V':
 {
 printf("Pasaport,biometrik fotograf getirmeyi ve vize ucretini yatirmayi unutmayiniz.\n\n");
	break;
 }
 
 case 'P':
 {
 	printf("Bulundugunuz bolgedeki yerel polise hemen bildirimde bulununuz,raporunu cikartiniz.\n\n");
	break;
 }
 
 default: printf("Gecerli bir harf giriniz.\n");
	 
}

}while(hizmet!='V'&& hizmet!='P');


printf("****X Konsoloslugu Randevu Sistemi ****\n\n");

printf("Tc Kimlik Numaraniz %lld\n",tcno);
printf("Ad-Soyadiniz %s %s\n",isim,soyisim);
printf("Anne-baba adiniz %s %s\n",annead,babaad);
printf("Randevunuz saat %.2lf olarak ayarlanmistir.\n",randsaat);
printf("Hizmet tipi : %c\n\n",hizmet);

}

printf("4 musterinin secmis oldugu saatler:\n\n");

for(v=0;v<4;v++)
{
printf("%.2lf\n",saatler[v][0]);
}

	return 0;
}
