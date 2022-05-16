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
        printf("Il regno e' Plantae\n\n");
        i++;
        while (i<2)
            {
            printf("Scegli un phylum tra: \n 1) Magnoliophyta \n 2) Rhodophyta \n");
            scanf("%s", Phylum);
            if (strcmp(Phylum, "Magnoliophyta")==0)
            {
            printf("Il phylum e' Magnoliophyta\n\n");
            i++;
            while (i<3)
                {
                printf("Scegli una classe tra: \n 1) Magnoliopsida \n 2) Liliopsida \n");
                scanf("%s", Classe);
                if (strcmp(Classe, "Magnoliopsida")==0)
                {
                printf("La Classe e' Magnoliopsida\n\n");
                i++;
                }
                else if (strcmp(Classe, "Liliopsida")==0)
                {
                printf("La Classe e' Liliopsida\n\n");
                i++;
                }
                }
            }
            else if (strcmp(Phylum, "Rhodophyta")==0)
            {
            printf("Il Phylum e' Rhodophyta\n\n");
            i++;
            while (i<3)
                {
                printf("Scegli una classe tra: \n 1)Floridaphyceae \n 2)Bangiophyceae  \n");
                scanf("%s", Classe);
                if (strcmp(Classe, "Floridaphyceae")==0)
                {
                printf("La Classe e' Floridaphyceae\n\n");
                i++;
                }
                else if (strcmp(Classe, "Bangiophyceae")==0)
                {
                printf("La Classe e' Bangiophyceae\n\n");
                i++;
                }
                }
            }
            }
        }
        else if (strcmp(Regno, "Animalia")==0)
        {
        printf("Il regno e' Animalia\n\n");
        i++;
        while (i<2)
            {
            printf("Scegli un phylum tra: \n 1) Chordata \n 2) Arthropoda \n");
            scanf("%s", Phylum);
            if (strcmp(Phylum, "Chordata")==0)
            {
            printf("Il phylum e' Chordata\n\n");
            i++;
            while (i<3)
                {
                printf("Scegli una classe tra: \n 1) Aves \n 2) Mammalia  \n");
                scanf("%s", Classe);
                if (strcmp(Classe, "Aves")==0)
                {
                printf("La Classe e' Aves \n\n");
                i++;
                }
                else if (strcmp(Classe, "Mammalia")==0)
                {
                printf("La Classe e' Mammalia \n\n");
                i++;
                while (i<4)
                    {
                    printf("Scegli un ordine tra: \n 1) Carnivora \n 2) Monotremata \n");
                    scanf("%s", Ordine);
                    if (strcmp(Ordine, "Carnivora")==0)
                    {
                    printf("L'ordine e' Carnivora\n\n");
                    i++;
                    }
                    else if (strcmp(Ordine, "Monotremata")==0)
                    {
                    printf("L'ordine e' Monotremata\n\n");
                    i++;
                    }
                    }
                }
                }
            }
            else if (strcmp(Phylum, "Arthropoda")==0)
            {
            printf("Il phylum e' Arthropoda \n\n");
            i++;
            while (i<3)
                {
                printf("Scegli una classe tra: \n 1) Malacostraca \n 2) Insecta  \n");
                scanf("%s", Classe);
                if (strcmp(Classe, "Malacostraca")==0)
                {
                printf("La Classe e' Malacostraca \n\n");
                i++;
                }
                else if (strcmp(Classe, "Insecta")==0)
                {
                printf("La Classe e' Insecta \n\n");
                i++;
                }
                }
            }
            }
        }
    }
return 0;
}
