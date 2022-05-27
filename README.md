#include <stdio.h>
#include <string.h>

/*
To do:
- Aggiungere errore ed istruzione nel caso il cui ci sia un errore di spelling!
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
                            while (i<4)
                                {
                                printf("Scegli una specie tra: \n 1) Leo \n 2) Tigris \n");
                                scanf("%s", Specie);
                                if (strcmp(Specie, "Leo")==0)
                                {
                                printf("La specie e' Leo\n L'animale e' il leone\n");
                                i++;
                                }
                                else if (strcmp(Specie, "Tigris")==0)
                                {
                                printf("La specie e' Tigris\n L'animale e' la tirge\n");
                                i++;
                                }
                                }
                            }
                            else if (strcmp(Genere, "Neofelis")==0)
                            {
                            printf("Il Genere e' Neofelis\n\n");
                            i++;
                            while (i<4)
                                {
                                printf("Scegli una specie tra: \n 1) Diardi \n 2) Nebulosa \n");
                                scanf("%s", Specie);
                                if (strcmp(Specie, "Diardi")==0)
                                {
                                printf("La specie e' Diardi\n L'animale e' il leopardo nebuloso del Borneo\n");
                                i++;
                                }
                                else if (strcmp(Specie, "Nebulosa")==0)
                                {
                                printf("La specie e' Nebulosa\n L'animale e' il leopardo nebuloso\n");
                                i++;
                                }
                                }
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
                             while (i<4)
                                {
                                printf("Scegli una specie tra: \n 1) Americanus \n 2) Marittimus \n");
                                scanf("%s", Specie);
                                if (strcmp(Specie, "Americanus")==0)
                                {
                                printf("La specie e' Americanus\n L'animale e' l'orso bruno americano\n");
                                i++;
                                }
                                else if (strcmp(Specie, "Marittimus")==0)
                                {
                                printf("La specie e' Marittimus\n L'animale e' l'orso polare\n");
                                i++;
                                }
                                }
                            }
                            else if (strcmp(Genere, "Ailuropoda")==0)
                            {
                            printf("Il Genere e' Ailuropoda\n\n");
                            i++;
                            while (i<4)
                                {
                                printf("Scegli una specie tra: \n 1) Melanoleuca \n 2) Microta \n");
                                scanf("%s", Specie);
                                if (strcmp(Specie, "Melanoleuca")==0)
                                {
                                printf("La specie e' Melanoleuca\n L'animale e' il panda maggiore\n");
                                i++;
                                }
                                else if (strcmp(Specie, "Microta")==0)
                                {
                                printf("La specie e' Microta\n L'animale e' il panda gigante pigmeo (estinto)\n");
                                i++;
                                }
                                }
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
                            printf("L'unica specie di Ornithorhynchus e' Anatinus\n L'animale e' l'ornitorinco");
                            }
                            else if (strcmp(Genere, "Obdurodon")==0)
                            {
                            printf("Il Genere e' Obdurodon\n\n");
                            i++;
                            while (i<4)
                                {
                                printf("Scegli una specie tra: \n 1) Dicksoni \n 2) Bartoni \n");
                                scanf("%s", Specie);
                                if (strcmp(Specie, "Dicksoni")==0)
                                {
                                printf("La specie e' Dicksoni\n L'animale e' l'ornitorinco dentato dell'Australia del Nord (estinto)\n");
                                i++;
                                }
                                else if (strcmp(Specie, "Bartoni")==0)
                                {
                                printf("La specie e' Bartoni\n L'animale e' l'ornitorinco dentato dell'Australia del Sud (estinto)\n");
                                i++;
                                }
                                }
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
                            while (i<4)
                                {
                                printf("Scegli una specie tra: \n 1) Bruijni \n 2) Bartoni \n");
                                scanf("%s", Specie);
                                if (strcmp(Specie, "Bruijni")==0)
                                {
                                printf("La specie e' Bruijni\n L'animale e' l'echidna dal becco lungo occidentale\n");
                                i++;
                                }
                                else if (strcmp(Specie, "Bartoni")==0)
                                {
                                printf("La specie e' Bartoni\n L'animale e' l'echidna dal becco lungo orientale\n");
                                i++;
                                }
                                }
                            }
                            else if (strcmp(Genere, "Tachyglossus")==0)
                            {
                            printf("Il Genere e' Tachyglossus\n\n");
                            i++;
                            while (i<4)
                                {
                                printf("Scegli una specie tra: \n 1) Aculeatus \n 2) Setosus \n");
                                scanf("%s", Specie);
                                if (strcmp(Specie, "Aculeatus")==0)
                                {
                                printf("La specie e' Aculeatus\n L'animale e' l'echidna istrice\n");
                                i++;
                                }
                                else if (strcmp(Specie, "Setosus")==0)
                                {
                                printf("La specie e' Setosus\n L'animale e' l'echidna della Tasmania\n");
                                i++;
                                }
                                }
                            }
                            }
                        }
                        }
                    }
                    }
                }
