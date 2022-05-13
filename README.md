#include <stdio.h>
#include <string.h>
int main ()
{ char Dominio[40];
  char Regno [10];
  char Phylum [30];
  int i =0;

while (i<1)
{
    printf("Scegli un dominio tra: \n 1) Eukaryota \n 2) Prokaryota \n");
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
            while (i<3)
                {
                printf("Scegli un phylum tra: \n 1) Angiosperme \n 2) Gimnosperme \n");
                scanf("%s", Phylum);
                if (strcmp(Phylum, "Angiosperme")==0)
                {
                printf("Il phylum e' Angiosperme\n");
                i++;
                }
                else if (strcmp(Phylum, "Gimnosperme")==0)
                {
                printf("Il phylum e' Gimnosperme\n");
                i++;
                }
                }
            }
            else if (strcmp(Regno, "Animalia")==0)
            {
            printf("Il regno e' Animalia\n");
            i++;
            while (i<3)
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
    }
    else if (strcmp(Dominio,"Prokaryota")==0)
    {
        printf("Il dominio e' Prokaryota \n");
        i++;
        while (i<2)
        {
            printf("Scegli un regno tra: \n 1) Bacteria \n 2) Archaea \n");
            scanf("%s", Regno);
            if (strcmp(Regno, "Bacteria")==0)
            {
            printf("Il regno e' Bacteria\n");
            i++;
            }
            else if (strcmp(Regno, "Archaea")==0)
            {
            printf("Il regno e' Archaea\n");
            i++;
            }
        }
    }
}
return 0;
}
