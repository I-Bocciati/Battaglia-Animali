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
            printf("Scegli un phylum tra: \n 1) Angiosperme \n 2) Gimnosperme \n");
            scanf("%s", Phylum);
            if (strcmp(Phylum, "Angiosperme")==0)
            {
            printf("Il phylum e' Angiosperme\n");
            i++;
            while (i<3)
                {
                printf("Scegli una classe tra: \n 1) Dicotiledoni \n 2) Monocotiledoni \n");
                scanf("%s", Classe);
                if (strcmp(Classe, "Dicotiledoni")==0)
                {
                printf("Il phylum e' Dicotiledoni\n");
                i++;
                }
                else if (strcmp(Classe, "Monocotiledoni")==0)
                {
                printf("Il phylum e' Monocotiledoni\n");
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
