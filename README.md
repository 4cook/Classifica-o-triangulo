//Problemas do Triangulos
#include<stdio.h>
int main (){
float A, B, C;
printf("Digite os 3 lados:");
scanf("%f %f %f",&A,&B,&C);
if(A<B+C && B<A+C &&C<A+B){
    printf("Forma um triangulo");
    if(A==B && B==C){//3 lados iguais
        printf(" EQUILATERO");
    }
    else if(A==B ||B==C || C==A){//pelo menos 2 lados iguais
      printf(" ISOSCELES");
    }
    else{
        printf(" ESCALENO");
    }
}
else{
    printf("NAO forma um triangulo");
}


}
