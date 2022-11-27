 #include<stdio.h>
  int main();
  {
     int sayi,birler,onlar,yuzler,toplam;
     
     printf("\nuc basamakli sayi girin:);
     
     scanf("%d",&sayi);
     
       birler=sayi%10;
       
       onlar=(sayi/10)%10;
       
       yuzler=sayi/100;
       
         toplam=birler+onlar+yuzler;  
         
             printf("toplam:%d",toplam);
        
        return 0;
        }
  
  
  
