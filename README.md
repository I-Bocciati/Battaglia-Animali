#include <stdio.h>
#include <string.h>

int main ()
{
    char Dominio[40];
    char Regno [10];
    int i =0;

    while (i<1)
    {
        printf("Scegli un dominio tra: \n 1) Eukaryota \n 2) Archaea \n 3) Eubacteria \n");
        scanf("%s", Dominio);
        if (strcmp(Dominio,"Eukaryota")==0)
        {
            printf("Il dominio e' Eukaryota\n");
            i++;
            while (i<2)
            {
                printf("Scegli un regno tra: \n 1) Animalia \n 2) Plantae \n");
                scanf("%s", Regno);
                if (strcmp(Regno, "Plantae")==0)
                {
                printf("Il regno e' Plantae\n");
                i++;
                }
                else if (strcmp(Regno, "Animalia")==0)
                {
                printf("Il regno e' Animalia\n");
                i++;
                }
            }

        }
        else if (strcmp(Dominio,"Archaea")==0)
        {
            printf("Il dominio e' Archaea");
            i++;
        }
        else if (strcmp(Dominio,"Eubacteria")==0)
        {
            printf("Il dominio e' Eubacteria");
            i++;
        }
    }
    return 0;
}
