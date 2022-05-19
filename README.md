#include <stdio.h>
#include <string.h>

/*
To do:
- Aggiungere errore ed istruzione nel caso il cui ci sia un errore di spelling!
- Aggiungere Generi degli Arthropoda
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
                        printf("Scegli una famiglia tra: \n 1) Cathartidae \n 2) Accipitridae \n");
                        scanf("%s", Famiglia);
                        if (strcmp(Famiglia, "Cathartidae")==0)
                        {
                        printf("La famiglia e' Cathartidae\n\n");
                        i++;
                        while (i<5)
                            {
                            printf("Scegli un genere tra: \n 1) Gymnogyps \n 2) Vultur \n");
                            scanf("%s", Genere);
                            if (strcmp(Genere, "Gymnogyps")==0)
                            {
                            printf("Il genere e' Gymnogyps\n\n");
                            i++;
                            }
                            else if (strcmp(Genere, "Vultur")==0)
                            {
                            printf("Il Genere e' Vultur\n\n");
                            i++;
                            }
                            }
                        }
                        else if (strcmp(Famiglia, "Accipitridae")==0)
                        {
                        printf("La famiglia e' Accipitridae\n\n");
                        i++;
                        while (i<5)
                            {
                            printf("Scegli un genere tra: \n 1) Aquila \n 2) Ictinaetus \n");
                            scanf("%s", Genere);
                            if (strcmp(Genere, "Aquila")==0)
                            {
                            printf("Il genere e' Aquila\n\n");
                            i++;
                            }
                            else if (strcmp(Genere, "Ictinaetus")==0)
                            {
                            printf("Il Genere e' Ictinaetus\n\n");
                            i++;
                            }
                            }
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
                        while (i<5)
                            {
                            printf("Scegli un genere tra: \n 1) Raphus \n 2) Pezophaps \n");
                            scanf("%s", Genere);
                            if (strcmp(Genere, "Raphus")==0)
                            {
                            printf("Il genere e' Raphus\n\n");
                            i++;
                            }
                            else if (strcmp(Genere, "Pezophaps")==0)
                            {
                            printf("Il Genere e' Pezophaps\n\n");
                            i++;
                            }
                            }
                        }
                        else if (strcmp(Famiglia, "Columbidae")==0)
                        {
                        printf("La famiglia e' Columbidae\n\n");
                        i++;
                        while (i<5)
                            {
                            printf("Scegli un genere tra: \n 1) Geotrygon \n 2) Claravis \n");
                            scanf("%s", Genere);
                            if (strcmp(Genere, "Geotrygon")==0)
                            {
                            printf("Il genere e' Geotrygon\n\n");
                            i++;
                            }
                            else if (strcmp(Genere, "Claravis")==0)
                            {
                            printf("Il Genere e' Claravis\n\n");
                            i++;
                            }
                            }
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
                    while (i<4)
                        {
                        printf("Scegli una famiglia tra: \n 1) Felidae \n 2) Ursidae \n");
                        scanf("%s", Famiglia);
                        if (strcmp(Famiglia, "Felidae")==0)
                        {
                        printf("La famiglia e' Felidae\n\n");
                        i++;
                        while (i<5)
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
                        while (i<5)
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
                    while (i<4)
                        {
                        printf("Scegli una famiglia tra: \n 1) Ornithorhynchidae \n 2) Tachyglossidae \n");
                        scanf("%s", Famiglia);
                        if (strcmp(Famiglia, "Ornithorhynchidae")==0)
                        {
                        printf("La famiglia e' Ornithorhynchidae\n\n");
                        i++;
                        while (i<5)
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
                        while (i<5)
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
                    while (i<4)
                        {
                        printf("Scegli una famiglia tra: \n 1) Coenobitidae \n 2) Majidae \n");
                        scanf("%s", Famiglia);
                        if (strcmp(Famiglia, "Coenobitidae")==0)
                        {
                        printf("La famiglia e' Coenobitidae\n\n");
                        i++;
                        }
                        else if (strcmp(Famiglia, "Majidae")==0)
                        {
                        printf("La famiglia e' Majidae\n\n");
                        i++;
                        }
                        }
                    }
                    else if (strcmp(Ordine, "Stomatopoda")==0)
                    {
                    printf("L'ordine e' Stomatopoda\n\n");
                    i++;
                    while (i<4)
                        {
                        printf("Scegli una famiglia tra: \n 1) Odontodactylidae \n 2) Gonodactylidae \n");
                        scanf("%s", Famiglia);
                        if (strcmp(Famiglia, "Odontodactylidae")==0)
                        {
                        printf("La famiglia e' Odontodactylidae\n\n");
                        i++;
                        }
                        else if (strcmp(Famiglia, "Gonodactylidae")==0)
                        {
                        printf("La famiglia e' Gonodactylidae\n\n");
                        i++;
                        }
                        }
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
                    while (i<4)
                        {
                        printf("Scegli una famiglia tra: \n 1) Acrididae \n 2) Tettigoniidae \n");
                        scanf("%s", Famiglia);
                        if (strcmp(Famiglia, "Acrididae")==0)
                        {
                        printf("La famiglia e' Acrididae\n\n");
                        i++;
                        }
                        else if (strcmp(Famiglia, "Tettigoniidae")==0)
                        {
                        printf("La famiglia e' Tettigoniidae\n\n");
                        i++;
                        }
                        }
                    }
                    else if (strcmp(Ordine, "Lepidoptera")==0)
                    {
                    printf("L'ordine e' Lepidoptera\n\n");
                    i++;
                    while (i<4)
                        {
                        printf("Scegli una famiglia tra: \n 1) Pieridae \n 2) Riodinidae \n");
                        scanf("%s", Famiglia);
                        if (strcmp(Famiglia, "Pieridae")==0)
                        {
                        printf("La famiglia e' Pieridae\n\n");
                        i++;
                        }
                        else if (strcmp(Famiglia, "Riodinidae")==0)
                        {
                        printf("La famiglia e' Riodinidae\n\n");
                        i++;
                        }
                        }
                    }
                    }
                }
                }
            }
            }
return 0;
}
