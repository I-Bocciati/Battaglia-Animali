#include <stdio.h>
#include <string.h>

int main ()
{
    char Dominio[40];
    int i =0;

    while (i<1)
    {
        printf("Scegli un dominio tra: \n 1) Eukaryota \n 2) Archaea \n 3) Eubacteria \n");
        scanf("%s", Dominio);
        if (strcmp(Dominio,"Eukaryota")==0)
        {
        printf("Il dominio e' Eukaryota");
        i++;
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
