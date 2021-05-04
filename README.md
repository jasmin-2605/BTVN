# BTVN
 
 
 //bai6
#include <stdio.h>
#include <stdlib.h>

int main()
{
    int n;
    printf("Moi ban nhap nam sinh: ");
    scanf("%d",&n);
    printf("so tuoi cua nguoi do tinh den nam 2021 la: %d", (2021-n));
    return 0;
}




//bai7
#include <stdio.h>
#include <stdlib.h>

int main()
{
    int a,b;
    printf("moi ban nhap a: ");
    scanf("%d",&a);
    printf("\nmoiban nhap b: ");
    scanf("%d",&b);
    printf("tong = %d\nhieu = %d\ntich = %d\nthuong = %.2f",a+b,a-b,a*b,(float)a/b);
    return 0;
}

//bai8

#include <stdio.h>
#include <stdlib.h>

int main()
{
    int b,c;
    char a[50];
   printf("nhap ten san pham:");
   gets(a);
    printf("\nmoi ban nhap so luong: ");
    scanf("%d",&b);
    printf("\nmoi ban nhap don gia: ");
    scanf("%d",&c);
    printf("\n tien phai tra: %d\n",c*b);
    printf("\n thue phai tra: %.2f",(float)c*b/10);
    return 0;
}



//bai9

#include <stdio.h>
#include <stdlib.h>

int main()
{

    int a[100];
    printf("moi ban nhap diem thi mon:\n");
    int s=0;
    for(int i=0; i<3;i++){
        if(i==0){
            printf("Mon Toan:");
            scanf("%d",&a[i]);
            s+=a[i];
        }
        if(i==1){
            printf("Mon Ly:");
            scanf("%d",&a[i]);
            s+=a[i];
        }
        if(i==2){
            printf("Mon Hoa:");
            scanf("%d",&a[i]);
            s+=a[i];
    }
    }
    printf("diem trung binh: %0.2f",(float)s/3);


    return 0;
}


//bai10

#include <stdio.h>
#include <stdlib.h>
#define PI 3.14
int main()
{

    int r;
    printf("moi ban nhap ban kinh duong tron: ");
    scanf("%d",&r);
    printf("chu vi = %0.2f", 2*PI*r);
    printf("\ndien tich = %0.2f", r*r*PI);

    return 0;
}


//bai 11

#include <stdio.h>
#include <conio.h>

int main()
{
    int n;
    int n1, n2, n3, n4, SoNut;
    printf("Nhap bien so xe (4 so): ");
    scanf("%d", &n);
    n4 = n % 10; n = n / 10;
    n3 = n % 10; n = n / 10;
    n2 = n % 10; n = n / 10;
    n1 = n;
    SoNut = (n1 + n2 + n3 + n4) % 10;
    printf("So nut la: %d\n", SoNut);
    return 0;
}








