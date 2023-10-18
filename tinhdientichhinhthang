#include <stdio.h>
#include <math.h>

int main() {
    printf("Nhap vao 4 canh cua hinh thang theo thu tu a, b, c, d (Voi a la day nho, b la canh ben trai, c la canh ben phai, d la day lon): ");
    float a, b, c, d, s, stg, sbh, p, h;
    scanf("%f %f %f %f", &a, &b, &c, &d);
    p = (b + c + d - a)/2;
    stg = sqrt(p*(p - b)*(p - c)*(p - d + a));
    h = 2*stg / (d - a);
    sbh = a * h;
    s = stg + sbh;
    printf("Dien tich hinh thang la: %f", s);
    
    return 0;

}
