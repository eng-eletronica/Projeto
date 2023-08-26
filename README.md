# Projeto
Quer saber qual combustível é mais vantajoso usar em seu carro? Descubra agora!

#include <stdio.h>
#include <stdlib.h>


int main()
{ int kg , ke , l, s,to,y,hg,z,tr,r;

 float g,e, qg,qe,t,f;
printf("adicione um valor em reais  \n");
scanf("%d", &r);
printf("adicione quanto seu carro faz com 1 litro de gasolina \n" );
scanf(" %d ", &kg);
printf("adicione o que seu carro faz com 1 litro de etanol  \n");
scanf(" %d ", &ke);

g= r/6.29;
e= r/4.5;

qg= g*kg;
qe= e*ke;


t=g-e;
f=e-g;



printf("valor em gasolina de %f litros  \n",g);
printf("valor em etanol de %f litros \n", e);
printf("valor de quilometragem gasolina %f quilometros \n",qg);
printf("valor de quilometragem etanol %f quilometros \n",qe);
if(qg>qe)
{
    printf(" mais vantajoso botar gasolina pelo carro ter uma autonomia de %f km a mais ", t);
}
else
{
    printf(" mais vantajoso botar etanol pelo carro ter uma autonomia de %f km a mais",f);
}



    return 0;
}
