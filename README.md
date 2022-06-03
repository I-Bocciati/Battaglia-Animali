/*
To do:
- Aggiungere errore ed istruzione nel caso il cui ci sia un errore di spelling!
- OPZIONALE: Aggiungere descrizione per ogni animale (ricordiamoci di mettere il Dodo)
*/

#include <stdio.h>
#include <string.h>

#define dim 30
typedef char stringa [dim];


void stampaListaAnimali (int n){
for(int i=0;i<n;i++){
printf("\n\nGrazie per aver giocato ma sappi che ci sono altri animali di cui puoi scoprire la descrizione. Continua a giocare per scovarle tutte! Di seguito trovi la lista completa:\n-Leone\n-Tigre\n-Leopardo nebuloso del Borneo\n-Leopardo nebuloso\n-Orso bruno americano\n-Orso polare\n-Panda maggiore\n-Panda gigante pigmeo (estinto)\n-Ornitorinco\n-Ornitorinco dentato dell'Australia del Nord (estinto)\n-Ornitorinco dentato dell'Australia del Sud (estinto)\n-Echidna dal becco lungo occidentale\n-Echidna dal becco lungo orientale\n-Echidna istrice\n-Echidna della Tasmania", i+1);
}
}

void CercaAnimale (stringa, stringa, stringa, stringa, int*);
void MostraAnimale (int);
void ConfrontaAnimali (int, int);

int main ()
{
    stringa Ordine, Famiglia, Genere, Specie;
    int Animale1, Animale2;
    printf("Benvenuto nella battaglia degli animali!\n\nDi seguito potrai scegliere due animali appartenenti alla classe Mammalia!\nArriverai a trovarli passando per tutta la tassonomia.. \nDopo ti diremo chi dei due che hai scelto vincerebbe un combattimento. Iniziamo!\n\n");

    CercaAnimale (Ordine, Famiglia, Genere, Specie, &Animale1);
    CercaAnimale (Ordine, Famiglia, Genere, Specie, &Animale2);
    printf ("%d e %d\n", Animale1, Animale2);
    ConfrontaAnimali (Animale1, Animale2);

    stampaListaAnimali (1);
    return 0;
}

void CercaAnimale (stringa Ordine, stringa Famiglia, stringa Genere, stringa Specie, int*Animale) {
    int i =0;
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
                                printf("La specie e' Leo\nL'animale e' il leone\n");
                                *Animale=14;
                                i++;
                                }
                                else if (strcmp(Specie, "Tigris")==0)
                                {
                                printf("La specie e' Tigris\nL'animale e' la tigre\n");
                                i++;
                                *Animale=13;
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
                                printf("La specie e' Diardi\nL'animale e' il leopardo nebuloso del Borneo\n");
                                i++;
                                *Animale=12;
                                }
                                else if (strcmp(Specie, "Nebulosa")==0)
                                {
                                printf("La specie e' Nebulosa\nL'animale e' il leopardo nebuloso\n");
                                i++;
                                *Animale=11;
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
                                printf("La specie e' Americanus\nL'animale e' l'orso bruno americano\n");
                                i++;
                                *Animale=10;
                                }
                                else if (strcmp(Specie, "Marittimus")==0)
                                {
                                printf("La specie e' Marittimus\nL'animale e' l'orso polare\n");
                                i++;
                                *Animale=9;
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
                                printf("La specie e' Melanoleuca\nL'animale e' il panda maggiore\n");
                                i++;
                                *Animale=8;
                                }
                                else if (strcmp(Specie, "Microta")==0)
                                {
                                printf("La specie e' Microta\nL'animale e' il panda gigante pigmeo (estinto)\n");
                                i++;
                                *Animale=7;
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
                            printf("L'unica specie di Ornithorhynchus e' Anatinus\n L'animale e' l'ornitorinco\n");
                            *Animale=6;
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
                                printf("La specie e' Dicksoni\nL'animale e' l'ornitorinco dentato dell'Australia del Nord (estinto)\n");
                                i++;
                                *Animale=5;
                                }
                                else if (strcmp(Specie, "Bartoni")==0)
                                {
                                printf("La specie e' Bartoni\nL'animale e' l'ornitorinco dentato dell'Australia del Sud (estinto)\n");
                                i++;
                                *Animale=4;
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
                                printf("La specie e' Bruijni\nL'animale e' l'echidna dal becco lungo occidentale\n");
                                i++;
                                *Animale=3;
                                }
                                else if (strcmp(Specie, "Bartoni")==0)
                                {
                                printf("La specie e' Bartoni\nL'animale e' l'echidna dal becco lungo orientale\n");
                                i++;
                                *Animale=2;
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
                                printf("La specie e' Aculeatus\nL'animale e' l'echidna istrice\n");
                                i++;
                                *Animale=1;
                                }
                                else if (strcmp(Specie, "Setosus")==0)
                                {
                                printf("La specie e' Setosus\nL'animale e' l'echidna della Tasmania\n");
                                i++;
                                *Animale=0;
                                }
                                }
                            }
                            }
                        }
                        }
                    }
                    }

}

void ConfrontaAnimali (int Animale1, int Animale2) {

    if (Animale1>Animale2) {
        MostraAnimale (Animale1);
        }
    else if (Animale2>Animale1) {
        MostraAnimale (Animale2);
        }

}

void MostraAnimale (int Animale){
    switch (Animale){
        case 14:
            printf ("L'animale piu' forte e' il leone");
            break;
        case 13:
            printf ("L'animale piu' forte e' la tigre");
            break;
        case 12:
            printf ("L'animale piu' forte e' il leopardo nebuloso del Borneo");
            break;
        case 11:
            printf ("L'animale piu' forte e' il leopardo nebuloso");
            break;
        case 10:
            printf ("L'animale piu' forte e' l'orso bruno americano");
            break;
        case 9:
            printf ("L'animale piu' forte e' l'orso polare");
            break;
        case 8:
            printf ("L'animale piu' forte e' il anda maggiore");
            break;
        case 7:
            printf ("L'animale piu' forte e' il panda gigante pigmeo (estinto");
            break;
        case 6:
            printf ("L'animale piu' forte e' l'ornitorinco");
            break;
        case 5:
            printf ("L'animale piu' forte e' l'ornitorinco dentato dell'Australia del Nord (estinto)");
            break;
        case 4:
            printf ("L'animale piu' forte e' l'ornitorinco dentato dell'Australia del Sud (estinto");
            break;
        case 3:
            printf ("L'animale piu' forte e' l'echidna dal becco lungo occidentale");
            break;
        case 2:
            printf ("L'animale piu' forte e' l'echidna dal becco lungo orientale");
            break;
        case 1:
            printf ("L'animale piu' forte e' l'echidna istrice");
            break;
        case 0:
            printf ("L'animale piu' forte e' l'echidna della Tasmania");
            break;
    }
}
