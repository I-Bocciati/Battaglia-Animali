#include <stdio.h>
#include <string.h>
int main ()
{
char Regno [10];
char Phylum [30];
char Classe [30];
char Ordine [30];
char Famiglia [30];
char Genere [30];
char Specie [30];
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
            printf("Scegli un phylum tra: \n 1) Magnoliophyta \n 2) Rhodophyta \n");
            scanf("%s", Phylum);
            if (strcmp(Phylum, "Magnoliophyta")==0)
            {
            printf("Il phylum e' Magnoliophyta\n");
            i++;
            while (i<3)
                {
                printf("Scegli una classe tra: \n 1) Magnoliopsida \n 2) Liliopsida \n");
                scanf("%s", Phylum);
                if (strcmp(Phylum, "Magnoliopsida")==0)
                {
                printf("La Classe e' Magnoliopsida\n");
                i++;
                }
                else if (strcmp(Phylum, "Liliopsida")==0)
                {
                printf("La Classe e' Liliopsida\n");
                i++;
                }
                }
            }
            else if (strcmp(Phylum, "Rhodophyta")==0)
            {
            printf("Il Phylum e' Rhodophyta\n");
            i++;
            while (i<3)
                {
                printf("Scegli una classe tra: \n 1)Floridaphyceae \n 2)Bangiophyceae  \n");
                scanf("%s", Phylum);
                if (strcmp(Phylum, "Floridaphyceae")==0)
                {
                printf("La Classe e' Floridaphyceae\n");
                i++;
                }
                else if (strcmp(Phylum, "Bangiophyceae")==0)
                {
                printf("La Classe e' Bangiophyceae\n");
                i++;
                }
                }
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
