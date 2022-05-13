#include <stdio.h>
#include <string.h>
int main ()
{
char Regno [10];
char Phylum [30];
char Classe [30];
int i =0;

while (i<1)
    {
        printf("Scegli un regno tra: \n 1) Animalia \n 2) Plantae \n");
        scanf("%s", Regno);
        if (strcmp(Regno, "Plantae")==0)
        {
        printf("Il regno e' Plantae\n");
        i++;
        while (i<2)
            {
            printf("Scegli un phylum tra: \n 1) Magnoliophyta \n 2) Viridiplantae \n");
            scanf("%s", Phylum);
            if (strcmp(Phylum, "Magnoliophyta")==0)
            {
            printf("Il phylum e' Magnoliophyta\n");
            i++;
            }
            else if (strcmp(Phylum, "Viridiplantae")==0)
            {
            printf("Il Phylum e' Viridiplantae\n");
            i++;
            }
            }
        }
        else if (strcmp(Regno, "Animalia")==0)
        {
        printf("Il regno e' Animalia\n");
        i++;
        while (i<2)
            {
            printf("Scegli un phylum tra: \n 1) Chordata \n 2) Arthropoda \n");
            scanf("%s", Phylum);
            if (strcmp(Phylum, "Chordata")==0)
            {
            printf("Il phylum e' Chordata\n");
            i++;
            }
            else if (strcmp(Phylum, "Arthropoda")==0)
            {
            printf("Il phylum e' Arthropoda \n");
            i++;
            }
            }
        }
    }
return 0;
}
