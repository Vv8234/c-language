#include <stdio.h>
#include <string.h>
#include <math.h>
int main() {float distance,mt,feet,inch,centi;
            scanf("%f",&distance);
            mt=(1000.0)*distance;
            feet=(1000.0)*3.28084*distance;
            inch=(1000.0)*39.3701*distance;
            centi=(100000.0)*distance;
            printf("%.2f m\n%.2f ft\n%.2f in\n%.2f cm",mt,feet,inch,centi);
            
    return 0;
}
