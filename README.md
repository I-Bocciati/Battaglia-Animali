#include <stdio.h>
#include <string.h>

int main ()
{
    printf("Scegli il dominio tra: Eubacteria, Archaea ed Eukarya\n");
    char Dominio [40];

    scanf("%s", Dominio);
    if (strcmp(Dominio,"Archaea") == 0)
    {
        printf("Il dominio è Archaea");
    }
    else if (strcmp(Dominio,"Eukarya")==0)
    {
        printf("Il dominio è Eukarya");
    }
    else if (strcmp(Dominio,"Eubacteria")==0)
    {
        printf("Il dominio è Eubacteria");
    }
    return 0;
}
