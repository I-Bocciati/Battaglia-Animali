#include <stdio.h>
#include <string.h>

/*
To do:
- Aggiungere errore ed istruzione nel caso il cui ci sia un errore di spelling!
- Aggiungere Specie
- Aggiungere descrizione per ogni animale (ricordiamoci di mettere il Dodo)
- Implementazione sottofunzioni
*/

int main ()
{
char Ordine [30];
char Famiglia [30];
char Genere [30];
char Specie [30];
int i =0;

printf("Benvenuto nel catalogo degli animali!\n\nDi seguito potrai trovare un animale appartenente al regno Animalia!\nArriverai a trovarlo passando per tutta la tassonomia animale.. Iniziamo!\n\n");


                while (i<1)
                    {
                    printf("Scegli un ordine tra: \n 1) Carnivora \n 2) Monotremata \n");
                    scanf("%s", Ordine);
                    if (strcmp(Ordine, "Carnivora")==0)
                    {
                    printf("L'ordine e' Carnivora\n\n");
                    i++;
                    while (i<2)
                        {
                        printf("Scegli una famiglia tra: \n 1) Felidae \n 2) Ursidae \n");
                        scanf("%s", Famiglia);
                        if (strcmp(Famiglia, "Felidae")==0)
                        {
                        printf("La famiglia e' Felidae\n\n");
                        i++;
                        while (i<3)
                            {
                            printf("Scegli un genere tra: \n 1) Panthera \n 2) Neofelis \n");
                            scanf("%s", Genere);
                            if (strcmp(Genere, "Panthera")==0)
                            {
                            printf("Il genere e' Panthera\n\n");
                            i++;
                            }
                            else if (strcmp(Genere, "Neofelis")==0)
                            {
                            printf("Il Genere e' Neofelis\n\n");
                            i++;
                            }
                            }
                        }
                        else if (strcmp(Famiglia, "Ursidae")==0)
                        {
                        printf("La famiglia e' Ursidae\n\n");
                        i++;
                        while (i<3)
                            {
                            printf("Scegli un genere tra: \n 1) Ursus \n 2) Ailuropoda \n");
                            scanf("%s", Genere);
                            if (strcmp(Genere, "Ursus")==0)
                            {
                            printf("Il genere e' Ursus\n\n");
                            i++;
                            }
                            else if (strcmp(Genere, "Ailuropoda")==0)
                            {
                            printf("Il Genere e' Ailuropoda\n\n");
                            i++;
                            }
                            }
                        }
                        }
                    }
                    else if (strcmp(Ordine, "Monotremata")==0)
                    {
                    printf("L'ordine e' Monotremata\n\n");
                    i++;
                    while (i<2)
                        {
                        printf("Scegli una famiglia tra: \n 1) Ornithorhynchidae \n 2) Tachyglossidae \n");
                        scanf("%s", Famiglia);
                        if (strcmp(Famiglia, "Ornithorhynchidae")==0)
                        {
                        printf("La famiglia e' Ornithorhynchidae\n\n");
                        i++;
                        while (i<3)
                            {
                            printf("Scegli un genere tra: \n 1) Ornithorhynchus \n 2) Obdurodon \n");
                            scanf("%s", Genere);
                            if (strcmp(Genere, "Ornithorhynchus")==0)
                            {
                            printf("Il genere e' Ornithorhynchus\n\n");
                            i++;
                            }
                            else if (strcmp(Genere, "Obdurodon")==0)
                            {
                            printf("Il Genere e' Obdurodon\n\n");
                            i++;
                            }
                            }
                        }
                        else if (strcmp(Famiglia, "Tachyglossidae")==0)
                        {
                        printf("La famiglia e' Tachyglossidae\n\n");
                        i++;
                        while (i<3)
                            {
                            printf("Scegli un genere tra: \n 1) Zaglossus \n 2) Tachyglossus \n");
                            scanf("%s", Genere);
                            if (strcmp(Genere, "Zaglossus")==0)
                            {
                            printf("Il genere e' Zaglossus\n\n");
                            i++;
                            }
                            else if (strcmp(Genere, "Tachyglossus")==0)
                            {
                            printf("Il Genere e' Tachyglossus\n\n");
                            i++;
                            }
                            }
                        }
                        }
                    }
                    }
                }
