#include <stdio.h>
#include <string.h>

/*
To do:
- Aggiungere errore ed istruzione nel caso il cui ci sia un errore di spelling!
- Aggiungere Genere
- Aggiungere Specie
- Aggiungere descrizione per ogni animale (ricordiamoci di mettere il Dodo)
- Implementazione sottofunzioni
*/

int main ()
{
char Phylum [30];
char Classe [30];
char Ordine [30];
char Famiglia [30];
char Genere [30];
char Specie [30];
int i =0;

printf("Benvenuto nel catalogo degli animali!\n\nDi seguito potrai trovare un animale appartenente al regno Animalia!\nArriverai a trovarlo passando per tutta la tassonomia animale.. Iniziamo!\n\n");

        while (i<1)
            {
            printf("Scegli un phylum tra: \n 1) Chordata \n 2) Arthropoda \n");
            scanf("%s", Phylum);
            if (strcmp(Phylum, "Chordata")==0)
            {
            printf("Il phylum e' Chordata\n\n");
            i++;
            while (i<2)
                {
                printf("Scegli una classe tra: \n 1) Aves \n 2) Mammalia  \n");
                scanf("%s", Classe);
                if (strcmp(Classe, "Aves")==0)
                {
                printf("La Classe e' Aves \n\n");
                i++;
                while (i<3)
                    {
                    printf("Scegli un ordine tra: \n 1) Accipitriformes \n 2) Columbiformes \n");
                    scanf("%s", Ordine);
                    if (strcmp(Ordine, "Accipitriformes")==0)
                    {
                    printf("L'ordine e' Accipitriformes\n\n");
                    i++;
                    while (i<4)
                        {
                        printf("Scegli una famiglia tra: \n 1) Sagittariidae \n 2) Pandionidae \n");
                        scanf("%s", Famiglia);
                        if (strcmp(Famiglia, "Sagittariidae")==0)
                        {
                        printf("La famiglia e' Sagittariidae\n\n");
                        i++;
                        }
                        else if (strcmp(Famiglia, "Pandionidae")==0)
                        {
                        printf("La famiglia e' Pandionidae\n\n");
                        i++;
                        }
                        }
                    }
                    else if (strcmp(Ordine, "Columbiformes")==0)
                    {
                    printf("L'ordine e' Columbiformes\n\n");
                    i++;
                    while (i<4)
                        {
                        printf("Scegli una famiglia tra: \n 1) Raphines \n 2) Columbidae \n");
                        scanf("%s", Famiglia);
                        if (strcmp(Famiglia, "Raphines")==0)
                        {
                        printf("La famiglia e' Raphines\n\n");
                        i++;
                        }
                        else if (strcmp(Famiglia, "Columbidae")==0)
                        {
                        printf("La famiglia e' Columbidae\n\n");
                        i++;
                        }
                        }
                    }
                    }
                }
                else if (strcmp(Classe, "Mammalia")==0)
                {
                printf("La Classe e' Mammalia \n\n");
                i++;
                while (i<3)
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
            while (i<2)
                {
                printf("Scegli una classe tra: \n 1) Malacostraca \n 2) Insecta  \n");
                scanf("%s", Classe);
                if (strcmp(Classe, "Malacostraca")==0)
                {
                printf("La Classe e' Malacostraca \n\n");
                i++;
                while (i<3)
                    {
                    printf("Scegli un ordine tra: \n 1) Decapoda \n 2) Stomatopoda \n");
                    scanf("%s", Ordine);
                    if (strcmp(Ordine, "Decapoda")==0)
                    {
                    printf("L'ordine e' Decapoda\n\n");
                    i++;
                    }
                    else if (strcmp(Ordine, "Stomatopoda")==0)
                    {
                    printf("L'ordine e' Stomatopoda\n\n");
                    i++;
                    }
                    }
                }
                else if (strcmp(Classe, "Insecta")==0)
                {
                printf("La Classe e' Insecta \n\n");
                i++;
                while (i<3)
                    {
                    printf("Scegli un ordine tra: \n 1) Orthoptera \n 2) Lepidoptera \n");
                    scanf("%s", Ordine);
                    if (strcmp(Ordine, "Orthoptera")==0)
                    {
                    printf("L'ordine e' Orthoptera\n\n");
                    i++;
                    }
                    else if (strcmp(Ordine, "Lepidoptera")==0)
                    {
                    printf("L'ordine e' Lepidoptera\n\n");
                    i++;
                    }
                    }
                }
                }
            }
            }
return 0;
}
