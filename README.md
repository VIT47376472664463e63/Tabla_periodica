# Tabla_periodica
Tabla periodica sin terminar, por si a alguien le sirve me faltan las ultimas 6 lineas













#include <iostream>
#include <windows.h>

using namespace std;
int opcion;

int main() {

    string a;
    int opcion;






    while (1 == 1)
    {

        cout << "------MENU------" << endl;
        cout << "1 Tabla periodica " << endl;
        cout << "2 Salir" << endl;



        cout << "Eliga una opcion" << endl;
        cin >> opcion;


        switch (opcion)
        {

        case 1:

            system("color 8F");

            cout << "--------------------------------     TABLA PERIODICA      ------------------------------3""\n";

            cout << " ___                                                                                ----""\n";
            cout << "| H |                                                                              | He |""\n";
            cout << " --------                                                  -----------------------------""\n";
            cout << "| Li| Be |                                                |  B |  C |  N |  O |  F | Ne |""\n";
            cout << " --------                                                  -----------------------------""\n";
            cout << "| Na| Mg |                                                | Al | Si |  P |  S | Cl | Ar |""\n";
            cout << " ---------------------------------------------------------------------------------------""\n";
            cout << "| K | Ca | Sc | Ti | V | Cr | Mn | Fe | Co | Ni | Cu | Zn | Ga | Ge | As | Se | Br | Kr |""\n";
            cout << " ---------------------------------------------------------------------------------------""\n";
            cout << "| Rb| Sr |  Y | Zr | Nb| Mo | Tc | Ru | Rh | Pd | Ag | Cd | In | Sn | Sb | Te |  I | Xe |""\n";
            cout << " ---------------------------------------------------------------------------------------""\n";
            cout << "| Cs| Ba | Lu | Hf | Ta | W | Re | Os | Ir | Pt | Au | Hg | TI | Pb | Bi | Po | At | Rn |""\n";
            cout << " ---------------------------------------------------------------------------------------""\n";
            cout << "| Fr| Ra | Lr | Rf | Db | Sg| Bh | Hs | Mt | Ds | Rg | Cn | Nh | FI | Mc | Lv | Ts | Og |""\n";
            cout << " ---------------------------------------------------------------------------------------""\n";
            cout << "|Uuu|Uub|""\n";
            cout << " --------""\n";

            cout << "                    -------------------------------------------------------------------""\n";
            cout << "                   | La | Ce| Pr | Nd | Pm | Sm | Eu | Gd | Tb | Dy | Ho | Er | Tm | Yb |""\n";
            cout << "                    -------------------------------------------------------------------""\n";
            cout << "                   | Ac | Th| Pa |  U | Np | Pu | Am | Cm | Bk | Cf | Es | Fm | Md | No |""\n";
            cout << "                    -------------------------------------------------------------------""\n";




            cout << " Ingresa el elemento quimico que quiera tener la informacion ""\n";
            cin >> a;




            if (a == "H") {
                cout << "  ____________________ ""\n";
                cout << " |            1.00797 |""\n";
                cout << " |  1               1 |""\n";
                cout << " |                    |""\n";
                cout << " | -225               |""\n";
                cout << " | -259     H         |""\n";
                cout << " | 0,071              |""\n";
                cout << " |                    |""\n";
                cout << " |          1         | ""\n";
                cout << " |        1s          | ""\n";
                cout << " |      HIDROGENO     |""\n";
                cout << "  -------------------- ""\n";
                system("color 1F");
            }


            if (a == "Li") {
                cout << "  ____________________ ""\n";
                cout << " |            6.941   |""\n";
                cout << " |  3               1 |""\n";
                cout << " |                    |""\n";
                cout << " | 1330               |""\n";
                cout << " | 188,5     Li       |""\n";
                cout << " | 0,53               |""\n";
                cout << " |                    |""\n";
                cout << " |          1  1      | ""\n";
                cout << " |        1s 2s       | ""\n";
                cout << " |        LITIO       |""\n";
                cout << "  -------------------- ""\n";
                system("color 9F");


            }



            if (a == "Be") {
                cout << "  ____________________ ""\n";
                cout << " |            9.0112  |""\n";
                cout << " |  4               2 |""\n";
                cout << " |                    |""\n";
                cout << " | 2770               |""\n";
                cout << " | 1277     Be        |""\n";
                cout << " | 1,85               |""\n";
                cout << " |                    |""\n";
                cout << " |          2  2      | ""\n";
                cout << " |        1s 2s       | ""\n";
                cout << " |        BERILIO     |""\n";
                cout << "  -------------------- ""\n";
                system("color 6F");


            }


            if (a == "Na") {
                cout << "  ____________________ ""\n";
                cout << " |            22.9898 |""\n";
                cout << " |  11               1|""\n";
                cout << " |                    |""\n";
                cout << " | 892                |""\n";
                cout << " | 97.8     Na        |""\n";
                cout << " | 0.97               |""\n";
                cout << " |                    |""\n";
                cout << " |              1     | ""\n";
                cout << " |        (Ne)3s      | ""\n";
                cout << " |        Sodio       |""\n";
                cout << "  -------------------- ""\n";

                system("color 9F");
            }


            if (a == "Mg") {
                cout << "  ____________________ ""\n";
                cout << " |            24.305  |""\n";
                cout << " |  12               2|""\n";
                cout << " |                    |""\n";
                cout << " | 1107               |""\n";
                cout << " | 650     Mg         |""\n";
                cout << " | 1.74               |""\n";
                cout << " |                    |""\n";
                cout << " |              2     | ""\n";
                cout << " |        (Ne)3s      | ""\n";
                cout << " |        MAGNESIO    |""\n";
                cout << "  -------------------- ""\n";

                system("color 6F");
            }

            if (a == "K") {
                cout << "  ____________________ ""\n";
                cout << " |            39.098  |""\n";
                cout << " |  19               1|""\n";
                cout << " |                    |""\n";
                cout << " | 760                |""\n";
                cout << " | 63.7     K         |""\n";
                cout << " | 0.86               |""\n";
                cout << " |                    |""\n";
                cout << " |              1     | ""\n";
                cout << " |        (Ar)4s      | ""\n";
                cout << " |        POTASIO     |""\n";
                cout << "  -------------------- ""\n";

                system("color 9F");
            }

            if (a == "Ca") {
                cout << "  ____________________ ""\n";
                cout << " |            40.08   |""\n";
                cout << " |  20               2|""\n";
                cout << " |                    |""\n";
                cout << " | 1440               |""\n";
                cout << " | 838     Ca         |""\n";
                cout << " | 1.55               |""\n";
                cout << " |                    |""\n";
                cout << " |              2     | ""\n";
                cout << " |        (Ar)4s      | ""\n";
                cout << " |        CALSIO      |""\n";
                cout << "  -------------------- ""\n";

                system("color 6F");
            }

            if (a == "Rb") {
                cout << "  ____________________ ""\n";
                cout << " |            85.47   |""\n";
                cout << " |  37               1|""\n";
                cout << " |                    |""\n";
                cout << " | 688                |""\n";
                cout << " | 38.9     Rb        |""\n";
                cout << " | 1.53               |""\n";
                cout << " |                    |""\n";
                cout << " |              1     | ""\n";
                cout << " |        (Kr)5s      | ""\n";
                cout << " |       RUBIDIO      |""\n";
                cout << "  -------------------- ""\n";

                system("color 9F");
            }

            if (a == "Sr") {
                cout << "  ____________________ ""\n";
                cout << " |            87.62   |""\n";
                cout << " |  38               2|""\n";
                cout << " |                    |""\n";
                cout << " | 1380               |""\n";
                cout << " | 768     Sr         |""\n";
                cout << " | 2.6                |""\n";
                cout << " |                    |""\n";
                cout << " |              2     | ""\n";
                cout << " |        (Kr)5s      | ""\n";
                cout << " |      ESTRONCIO     |""\n";
                cout << "  -------------------- ""\n";

                system("color 6F");
            }

            if (a == "Cs") {
                cout << "  ____________________ ""\n";
                cout << " |           132.905  |""\n";
                cout << " |  55               1|""\n";
                cout << " |                    |""\n";
                cout << " | 690                |""\n";
                cout << " | 28.7     Cs        |""\n";
                cout << " | 1.90               |""\n";
                cout << " |                    |""\n";
                cout << " |              1     | ""\n";
                cout << " |        (Xe)6s      | ""\n";
                cout << " |        CESIO       |""\n";
                cout << "  -------------------- ""\n";

                system("color 9F");
            }

            if (a == "Ba") {
                cout << "  ____________________ ""\n";
                cout << " |           137.34   |""\n";
                cout << " |  56               2|""\n";
                cout << " |                    |""\n";
                cout << " | 1640               |""\n";
                cout << " | 714     Ba         |""\n";
                cout << " | 3.5                |""\n";
                cout << " |                    |""\n";
                cout << " |              2     | ""\n";
                cout << " |        (Xe)6s      | ""\n";
                cout << " |        BARIO       |""\n";
                cout << "  -------------------- ""\n";

                system("color 6F");
            }

            if (a == "Fr") {
                cout << "  ____________________ ""\n";
                cout << " |            (223)   |""\n";
                cout << " |  87               1|""\n";
                cout << " |                    |""\n";
                cout << " |  --                |""\n";
                cout << " | (27)     Fr        |""\n";
                cout << " |  --                |""\n";
                cout << " |                    |""\n";
                cout << " |              1     | ""\n";
                cout << " |        (Rn)7s      | ""\n";
                cout << " |       FRANCIO      |""\n";
                cout << "  -------------------- ""\n";

                system("color 9F");
            }

            if (a == "Ra") {
                cout << "  ____________________ ""\n";
                cout << " |           (226)    |""\n";
                cout << " |  88               2|""\n";
                cout << " |                    |""\n";
                cout << " |  --                |""\n";
                cout << " | 700     Ba         |""\n";
                cout << " | 5.0                |""\n";
                cout << " |                    |""\n";
                cout << " |              2     | ""\n";
                cout << " |        (Rn)7s      | ""\n";
                cout << " |        RADIO       |""\n";
                cout << "  -------------------- ""\n";

                system("color 6F");
            }

            if (a == "Uuu") {
                cout << "  ____________________ ""\n";
                cout << " |           (272)    |""\n";
                cout << " |  111               |""\n";
                cout << " |                    |""\n";
                cout << " |  --                |""\n";
                cout << " |  --     Uuu        |""\n";
                cout << " |  --                |""\n";
                cout << " |                    |""\n";
                cout << " |       14  10  1    | ""\n";
                cout << " |(Rn)5f   6d  7s     | ""\n";
                cout << " |      Unununio      |""\n";
                cout << "  -------------------- ""\n";

                system("color 7");
            }

            if (a == "Uub") {
                cout << "  ____________________ ""\n";
                cout << " |            124     |""\n";
                cout << " |  111               |""\n";
                cout << " |                    |""\n";
                cout << " |  --                |""\n";
                cout << " |  --     Ubq        |""\n";
                cout << " |  --                |""\n";
                cout << " |                    |""\n";
                cout << " |        4   2       | ""\n";
                cout << " |      5g  8s        | ""\n";
                cout << " |      Unbiquadium   |""\n";
                cout << "  -------------------- ""\n";

                system("color 7");
            }

            if (a == "Sc") {
                cout << "  ____________________ ""\n";
                cout << " |            78.96   |""\n";
                cout << " |  34           2,4,6|""\n";
                cout << " |                    |""\n";
                cout << " |  685               |""\n";
                cout << " |  217     Se        |""\n";
                cout << " |  4.79              |""\n";
                cout << " |                    |""\n";
                cout << " |       18  2   4    | ""\n";
                cout << " | (Ar)3d  4s  4p     | ""\n";
                cout << " |      SELENIO       |""\n";
                cout << "  -------------------- ""\n";

                system("color 26");
            }

            if (a == "Ti") {
                cout << "  ____________________ ""\n";
                cout << " |            47.90   |""\n";
                cout << " |  22           2,3,4|""\n";
                cout << " |                    |""\n";
                cout << " |  3250              |""\n";
                cout << " |  1668     Ti       |""\n";
                cout << " |  4.51              |""\n";
                cout << " |                    |""\n";
                cout << " |       2  2         | ""\n";
                cout << " | (Ar)3d  4s         | ""\n";
                cout << " |      TITANIO       |""\n";
                cout << "  -------------------- ""\n";

                system("color 26");
            }

            if (a == "Y") {
                cout << "  ____________________ ""\n";
                cout << " |            88.906  |""\n";
                cout << " |  39               3|""\n";
                cout << " |                    |""\n";
                cout << " |  2927              |""\n";
                cout << " |  1509     Y        |""\n";
                cout << " |  4.47              |""\n";
                cout << " |                    |""\n";
                cout << " |           1   2    | ""\n";
                cout << " |     (Kr)4d  5s     | ""\n";
                cout << " |      ITRIO         |""\n";
                cout << "  -------------------- ""\n";

                system("color 26");
            }

            if (a == "Zr") {
                cout << "  ____________________ ""\n";
                cout << " |            91.22   |""\n";
                cout << " |  40           2,3,4|""\n";
                cout << " |                    |""\n";
                cout << " |  3580              |""\n";
                cout << " |  1852     Zr       |""\n";
                cout << " |  6.49              |""\n";
                cout << " |                    |""\n";
                cout << " |           2   2    | ""\n";
                cout << " |     (Kr)4d  5s     | ""\n";
                cout << " |      CIRCONIO      |""\n";
                cout << "  -------------------- ""\n";

                system("color 26");
            }

            if (a == "Lu") {
                cout << "  ____________________ ""\n";
                cout << " |            174.97  |""\n";
                cout << " |  71               3|""\n";
                cout << " |                    |""\n";
                cout << " |  3327              |""\n";
                cout << " |  1652     Lu       |""\n";
                cout << " |  9.84              |""\n";
                cout << " |                    |""\n";
                cout << " |       14  1  2     | ""\n";
                cout << " | (Xe)4f  5d 6s      | ""\n";
                cout << " |      LUTECIO       |""\n";
                cout << "  -------------------- ""\n";

                system("color 26");
            }

            if (a == "Hf") {
                cout << "  ____________________ ""\n";
                cout << " |            178.49  |""\n";
                cout << " |  72           2,3,4|""\n";
                cout << " |                    |""\n";
                cout << " |  5400              |""\n";
                cout << " |  2222     Hf       |""\n";
                cout << " |  13.1              |""\n";
                cout << " |                    |""\n";
                cout << " |       14  2  2     | ""\n";
                cout << " | (Xe)4f  5d 6s      | ""\n";
                cout << " |      HAFNIO        |""\n";
                cout << "  -------------------- ""\n";

                system("color 26");
            }

            if (a == "Lr") {
                cout << "  ____________________ ""\n";
                cout << " |            (262)   |""\n";
                cout << " |  103               |""\n";
                cout << " |                    |""\n";
                cout << " |   --               |""\n";
                cout << " |   --     Lr        |""\n";
                cout << " |   --               |""\n";
                cout << " |                    |""\n";
                cout << " |       14  1  2     | ""\n";
                cout << " | (Rn)5f  6d 7s      | ""\n";
                cout << " |      LAWRECIO      |""\n";
                cout << "  -------------------- ""\n";

                system("color 26");
            }

            if (a == "V") {

                cout << "  ____________________ ""\n";
                cout << " |           50.942   |""\n";
                cout << " |  23        2,3,4,5 |""\n";
                cout << " |                    |""\n";
                cout << " |  3450              |""\n";
                cout << " |  1900     V        |""\n";
                cout << " |  4.51              |""\n";
                cout << " |                    |""\n";
                cout << " |             3  2   | ""\n";
                cout << " |       (Ar)3d 4s    | ""\n";
                cout << " |      VANADIO       |""\n";
                cout << "  -------------------- ""\n";

                system("color 26");
            }

            if (a == "Cr") {

                cout << "  ____________________ ""\n";
                cout << " |           51.996   |""\n";
                cout << " |  24       2,3,4,5,6|""\n";
                cout << " |                    |""\n";
                cout << " |  2665              |""\n";
                cout << " |  1875     Cr       |""\n";
                cout << " |  7.19              |""\n";
                cout << " |                    |""\n";
                cout << " |             5  1   | ""\n";
                cout << " |       (Ar)3d 4s    | ""\n";
                cout << " |        CROMO       |""\n";
                cout << "  -------------------- ""\n";

                system("color 26");
            }

            if (a == "Nb") {

                cout << "  ____________________ ""\n";
                cout << " |           92.906   |""\n";
                cout << " |  41         2,3,4,5|""\n";
                cout << " |                    |""\n";
                cout << " |  3300              |""\n";
                cout << " |  2468     Nb       |""\n";
                cout << " |  8.4               |""\n";
                cout << " |                    |""\n";
                cout << " |         4          | ""\n";
                cout << " |       (Kr)4d 5s    | ""\n";
                cout << " |        NIOBIO      |""\n";
                cout << "  -------------------- ""\n";

                system("color 26");
            }
            if (a == "Mo") {

                cout << "  ____________________ ""\n";
                cout << " |           95,94    |""\n";
                cout << " |  42       2,3,4,5,6|""\n";
                cout << " |                    |""\n";
                cout << " |  5568              |""\n";
                cout << " |  2618    Mo        |""\n";
                cout << " |  18.2              |""\n";
                cout << " |                    |""\n";
                cout << " |             5  1   | ""\n";
                cout << " |       (Kr)4d 5s    | ""\n";
                cout << " |       MOLIBDENO    |""\n";
                cout << "  -------------------- ""\n";

                system("color 26");
            }
            if (a == "Ta") {

                cout << "  ____________________ ""\n";
                cout << " |           180.948  |""\n";
                cout << " |  73         2,3,4,5|""\n";
                cout << " |                    |""\n";
                cout << " |  5525              |""\n";
                cout << " |  2996    Mo        |""\n";
                cout << " |  16.61             |""\n";
                cout << " |                    |""\n";
                cout << " |          14  3  2  | ""\n";
                cout << " |    (Xe)4f  5d 6s   | ""\n";
                cout << " |       TANTALO      |""\n";
                cout << "  -------------------- ""\n";

                system("color 26");
            }
            if (a == "W") {

                cout << "  ____________________ ""\n";
                cout << " |           183.85   |""\n";
                cout << " |  74       2,3,4,5,6|""\n";
                cout << " |                    |""\n";
                cout << " |  5525              |""\n";
                cout << " |  2996    W         |""\n";
                cout << " |  19.3              |""\n";
                cout << " |                    |""\n";
                cout << " |          14  4  2  | ""\n";
                cout << " |    (Xe)4f  5d 6s   | ""\n";
                cout << " |      VOLFRAMIO     |""\n";
                cout << "  -------------------- ""\n";

                system("color 26");
            }
            if (a == "Re") {

                cout << "  ____________________ ""\n";
                cout << " |           186.2    |""\n";
                cout << " |  75         2,4,6,7|""\n";
                cout << " |                    |""\n";
                cout << " |  5900              |""\n";
                cout << " |  3180    Re        |""\n";
                cout << " |  21                |""\n";
                cout << " |                    |""\n";
                cout << " |          14  4  2  | ""\n";
                cout << " |    (Xe)4f  5d 6s   | ""\n";
                cout << " |        RENIO       |""\n";
                cout << "  -------------------- ""\n";

                system("color 26");
            }
            if (a == "Sg") {

                cout << "  ____________________ ""\n";
                cout << " |           (263)    |""\n";
                cout << " | 106         -----  |""\n";
                cout << " |                    |""\n";
                cout << " |  ---               |""\n";
                cout << " |  ---     Sg        |""\n";
                cout << " |  ---               |""\n";
                cout << " |                    |""\n";
                cout << " |          14  4  2  | ""\n";
                cout << " |    (Xe)4f  5d 7s   | ""\n";
                cout << " |      SEABORGIO     |""\n";
                cout << "  -------------------- ""\n";

                system("color 26");
            }
            if (a == "Bh") {

                cout << "  ____________________ ""\n";
                cout << " |           (262)    |""\n";
                cout << " | 107         -----  |""\n";
                cout << " |                    |""\n";
                cout << " |  ---               |""\n";
                cout << " |  ---     Bh        |""\n";
                cout << " |  ---               |""\n";
                cout << " |                    |""\n";
                cout << " |          14  5  2  | ""\n";
                cout << " |    (Xe)4f  6d 7s   | ""\n";
                cout << " |        BOHRIO      |""\n";
                cout << "  -------------------- ""\n";

                system("color 26");
            }
            if (a == "Fe") {

                cout << "  ____________________ ""\n";
                cout << " |           55.847   |""\n";
                cout << " | 26             2,3 |""\n";
                cout << " |                    |""\n";
                cout << " |  3000              |""\n";
                cout << " |  1536     Fe       |""\n";
                cout << " |  7.86              |""\n";
                cout << " |                    |""\n";
                cout << " |           6   2    | ""\n";
                cout << " |     (Ar)3d  4s     |  ""\n";
                cout << " |        HIERRO      |""\n";
                cout << "  -------------------- ""\n";

                system("color 26");
            }
            if (a == "Co") {

                cout << "  ____________________ ""\n";
                cout << " |           58.93    |""\n";
                cout << " | 27             2,3 |""\n";
                cout << " |                    |""\n";
                cout << " |  2900              |""\n";
                cout << " |  1495     Co       |""\n";
                cout << " |  8.9               |""\n";
                cout << " |                    |""\n";
                cout << " |           7   2    | ""\n";
                cout << " |     (Ar)3d  4s     |  ""\n";
                cout << " |       COBALTO      |""\n";
                cout << "  -------------------- ""\n";

                system("color 26");
            }
            if (a == "Ru") {

                cout << "  ____________________ ""\n";
                cout << " |             101.07 |""\n";
                cout << " | 44       2,3,4,6,8 |""\n";
                cout << " |                    |""\n";
                cout << " |  4900              |""\n";
                cout << " |  2500     Ru       |""\n";
                cout << " |  12.2              |""\n";
                cout << " |                    |""\n";
                cout << " |           7   1    | ""\n";
                cout << " |     (Kr)4d  5s     |  ""\n";
                cout << " |       RUTENIO      |""\n";
                cout << "  -------------------- ""\n";

          

                system("color 26");
            }
            if (a == "Rh") {

                cout << "  ____________________ ""\n";
                cout << " |             102.905|""\n";
                cout << " | 45             2,3 |""\n";
                cout << " |                    |""\n";
                cout << " |  4500              |""\n";
                cout << " |  1966     Rh       |""\n";
                cout << " |  12.4              |""\n";
                cout << " |                    |""\n";
                cout << " |           8   1    | ""\n";
                cout << " |     (Kr)4d  5s     |  ""\n";
                cout << " |       RODIO        |""\n";
                cout << "  -------------------- ""\n";



                system("color 26");
            }
            if (a == "Os") {

                cout << "  ____________________ ""\n";
                cout << " |             190.2  |""\n";
                cout << " | 76        2,3,4,6,8|""\n";
                cout << " |                    |""\n";
                cout << " |  5500              |""\n";
                cout << " |  3000     Os       |""\n";
                cout << " |  22.6              |""\n";
                cout << " |                    |""\n";
                cout << " |         14  6  2   | ""\n";
                cout << " |   (Xe)4f  5d 6s    |  ""\n";
                cout << " |       OSMIO        |""\n";
                cout << "  -------------------- ""\n";



                system("color 26");
            }
            if (a == "Ir") {

                cout << "  ____________________ ""\n";
                cout << " |             192.2  |""\n";
                cout << " | 77            2,3,4|""\n";
                cout << " |                    |""\n";
                cout << " |  5300              |""\n";
                cout << " |  2454     Ir       |""\n";
                cout << " |  22.5              |""\n";
                cout << " |                    |""\n";
                cout << " |         14  7  2   | ""\n";
                cout << " |   (Xe)4f  5d 6s    |  ""\n";
                cout << " |       IRIDIO       |""\n";
                cout << "  -------------------- ""\n";



                system("color 26");
            }
            if (a == "HS") {

                cout << "  ____________________ ""\n";
                cout << " |             (265)  |""\n";
                cout << " | 108            --- |""\n";
                cout << " |                    |""\n";
                cout << " |  ---               |""\n";
                cout << " |  ---     Ir        |""\n";
                cout << " |  ---               |""\n";
                cout << " |                    |""\n";
                cout << " |         14  6  2   | ""\n";
                cout << " |   (Rn)5f  6d 7s    |  ""\n";
                cout << " |       HASSIO       |""\n";
                cout << "  -------------------- ""\n";



                system("color 26");
            }
            if (a == "Mt") {

                cout << "  ____________________ ""\n";
                cout << " |             (266)  |""\n";
                cout << " | 109            --- |""\n";
                cout << " |                    |""\n";
                cout << " |  ---               |""\n";
                cout << " |  ---     Mt        |""\n";
                cout << " |  ---               |""\n";
                cout << " |                    |""\n";
                cout << " |         14  7  2   | ""\n";
                cout << " |   (Rn)5f  6d 7s    |  ""\n";
                cout << " |      MEITNERIO     |""\n";
                cout << "  -------------------- ""\n";



                system("color 26");
            }
            if (a == "Ni") {

                cout << "  ____________________ ""\n";
                cout << " |             58.71  |""\n";
                cout << " | 28             2,3 |""\n";
                cout << " |                    |""\n";
                cout << " |  2730              |""\n";
                cout << " |  1453     Ni       |""\n";
                cout << " |   8.9              |""\n";
                cout << " |                    |""\n";
                cout << " |         8  2       | ""\n";
                cout << " |   (Ar)3d 4s        |  ""\n";
                cout << " |       NIQUEL       |""\n";
                cout << "  -------------------- ""\n";



                system("color 26");
            }
            if (a == "Cu") {

                cout << "  ____________________ ""\n";
                cout << " |             63.54  |""\n";
                cout << " | 29             1,2 |""\n";
                cout << " |                    |""\n";
                cout << " |  2595              |""\n";
                cout << " |  1083     Cu       |""\n";
                cout << " |  8.96              |""\n";
                cout << " |                    |""\n";
                cout << " |         10  1      | ""\n";
                cout << " |   (Ar)3d  4s       |  ""\n";
                cout << " |       COBRE        |""\n";
                cout << "  -------------------- ""\n";



                system("color 26");
            }
            if (a == "Pd") {

                cout << "  ____________________ ""\n";
                cout << " |             106.4  |""\n";
                cout << " | 46             2,4 |""\n";
                cout << " |                    |""\n";
                cout << " |  3980              |""\n";
                cout << " |  1552     Pd       |""\n";
                cout << " |  12.0              |""\n";
                cout << " |                    |""\n";
                cout << " |         10  0      | ""\n";
                cout << " |   (Kr)4d  4s       |  ""\n";
                cout << " |      PALADIO       |""\n";
                cout << "  -------------------- ""\n";



                system("color 26");
            }
            if (a == "Ag") {

                cout << "  ____________________ ""\n";
                cout << " |            107.870 |""\n";
                cout << " | 47               1 |""\n";
                cout << " |                    |""\n";
                cout << " |  2210              |""\n";
                cout << " |  960.8     Ag      |""\n";
                cout << " |  10.5              |""\n";
                cout << " |                    |""\n";
                cout << " |         10  1      | ""\n";
                cout << " |   (Kr)4d  5s       |  ""\n";
                cout << " |       PLATA        |""\n";
                cout << "  -------------------- ""\n";



                system("color 26");
            }
            if (a == "Pt") {

                cout << "  ____________________ ""\n";
                cout << " |            195.09  |""\n";
                cout << " | 78             2,4 |""\n";
                cout << " |                    |""\n";
                cout << " |  4530              |""\n";
                cout << " |  1769     Pt       |""\n";
                cout << " |  21.4              |""\n";
                cout << " |                    |""\n";
                cout << " |        14  9  1    | ""\n";
                cout << " |  (Xe)4f  5d 6s     |  ""\n";
                cout << " |      PLATINO       |""\n";
                cout << "  -------------------- ""\n";



                system("color 26");
            }
            if (a == "Au") {

                cout << "  ____________________ ""\n";
                cout << " |           196.967  |""\n";
                cout << " | 79             1,3 |""\n";
                cout << " |                    |""\n";
                cout << " |  2970              |""\n";
                cout << " |  1063     Au       |""\n";
                cout << " |  19.3              |""\n";
                cout << " |                    |""\n";
                cout << " |        14  9  1    | ""\n";
                cout << " |  (Xe)4f  5d 6s     |  ""\n";
                cout << " |         ORO        |""\n";
                cout << "  -------------------- ""\n";



                system("color 26");
            }
            if (a == "Ds") {

                cout << "  ____________________ ""\n";
                cout << " |              (271) |""\n";
                cout << " | 110            --- |""\n";
                cout << " |                    |""\n";
                cout << " |  ---               |""\n";
                cout << " |  ---      Ds       |""\n";
                cout << " |  ---               |""\n";
                cout << " |                    |""\n";
                cout << " |        14  9  2    | ""\n";
                cout << " |      5f  6d 7s     |  ""\n";
                cout << " |     DARMSTADTIUM   |""\n";
                cout << "  -------------------- ""\n";



                system("color 26");
            }
            if (a == "Rf") {

                cout << "  ____________________ ""\n";
                cout << " |              (261) |""\n";
                cout << " | 104            --- |""\n";
                cout << " |                    |""\n";
                cout << " |  ---               |""\n";
                cout << " |  ---      Rf       |""\n";
                cout << " |  ---               |""\n";
                cout << " |                    |""\n";
                cout << " |        14  2  2    | ""\n";
                cout << " |   (Rn)5f 6d 7s     |  ""\n";
                cout << " |     RUTHERFODIO    |""\n";
                cout << "  -------------------- ""\n";



                system("color 26");
            }
            if (a == "Db") {

                cout << "  ____________________ ""\n";
                cout << " |             (262)  |""\n";
                cout << " | 105            --- |""\n";
                cout << " |                    |""\n";
                cout << " |  ---               |""\n";
                cout << " |  ---      Db       |""\n";
                cout << " |  ---               |""\n";
                cout << " |                    |""\n";
                cout << " |        14  3  2    | ""\n";
                cout << " |   (Rn)5f 6d 7s     |  ""\n";
                cout << " |      DUBINIO       |""\n";
                cout << "  -------------------- ""\n";



                system("color 26");
            }
            if (a == "Rg") {

                cout << "  ____________________ ""\n";
                cout << " |              (281) |""\n";
                cout << " | 111            --- |""\n";
                cout << " |                    |""\n";
                cout << " |  ---               |""\n";
                cout << " |  ---      Rg       |""\n";
                cout << " |  ---               |""\n";
                cout << " |                    |""\n";
                cout << " |        14  10 1    | ""\n";
                cout << " |      5f  6d 7s     |  ""\n";
                cout << " |     ROENTGENIUM    |""\n";
                cout << "  -------------------- ""\n";



                system("color 26");
            }
            if (a == "Zn") {

                cout << "  ____________________ ""\n";
                cout << " |              65.37 |""\n";
                cout << " | 30               2 |""\n";
                cout << " |                    |""\n";
                cout << " |  906               |""\n";
                cout << " |  419.5      Zn     |""\n";
                cout << " |  7.14              |""\n";
                cout << " |                    |""\n";
                cout << " |           10 2     | ""\n";
                cout << " |     (Ar)3d  4s     |  ""\n";
                cout << " |         ZINC       |""\n";
                cout << "  -------------------- ""\n";



                system("color 26");
            }
            if (a == "Cd") {

                cout << "  ____________________ ""\n";
                cout << " |             112.40 |""\n";
                cout << " | 48               2 |""\n";
                cout << " |                    |""\n";
                cout << " |  765               |""\n";
                cout << " |  320.9      Cd     |""\n";
                cout << " |  8.65              |""\n";
                cout << " |                    |""\n";
                cout << " |           10 2     | ""\n";
                cout << " |     (Kr)4d  5s     |  ""\n";
                cout << " |        CADMIUM     |""\n";
                cout << "  -------------------- ""\n";



                system("color 26");
            }
            if (a == "Hg") {

                cout << "  ____________________ ""\n";
                cout << " |              200.59|""\n";
                cout << " | 80             1,2 |""\n";
                cout << " |                    |""\n";
                cout << " |  357               |""\n";
                cout << " | -38.4       Hg     |""\n";
                cout << " |  16.6              |""\n";
                cout << " |                    |""\n";
                cout << " |        14  10  2   | ""\n";
                cout << " |  (Xe)4f  5d  6s    |  ""\n";
                cout << " |       MERCURIO     |""\n";
                cout << "  -------------------- ""\n";



                system("color 26");
            }
            if (a == "Cn") {

                cout << "  ____________________ ""\n";
                cout << " |              (285) |""\n";
                cout << " | 112              - |""\n";
                cout << " |                    |""\n";
                cout << " |  ---               |""\n";
                cout << " |  ---        Cn     |""\n";
                cout << " |  ---               |""\n";
                cout << " |                    |""\n";
                cout << " |       14  10  2    | ""\n";
                cout << " |     5f  6d  7s     |  ""\n";
                cout << " |     COPERNICIUM    |""\n";
                cout << "  -------------------- ""\n";



                system("color 26");
            }
            if (a == "Mn") {

                cout << "  ____________________ ""\n";
                cout << " |             54.938 |""\n";
                cout << " | 25       2,3,4,6,7 |""\n";
                cout << " |                    |""\n";
                cout << " |  2150              |""\n";
                cout << " |  1245       Mn     |""\n";
                cout << " |  7.43              |""\n";
                cout << " |                    |""\n";
                cout << " |           5   2    | ""\n";
                cout << " |     (Ar)3d  4s     |  ""\n";
                cout << " |     MANGANESO      |""\n";
                cout << "  -------------------- ""\n";



                system("color 26");
            }
            if (a == "Tc") {

                cout << "  ____________________ ""\n";
                cout << " |               (97) |""\n";
                cout << " | 43               7 |""\n";
                cout << " |                    |""\n";
                cout << " |  ---               |""\n";
                cout << " |  21.40      Tc     |""\n";
                cout << " |  11.5              |""\n";
                cout << " |                    |""\n";
                cout << " |           5   2    | ""\n";
                cout << " |     (Kr)4d  5s     |  ""\n";
                cout << " |        TECNECIO    |""\n";
                cout << "  -------------------- ""\n";



                system("color 26");
            }
            if (a == "Hs") {

                cout << "  ____________________ ""\n";
                cout << " |              (265) |""\n";
                cout << " | 108                |""\n";
                cout << " |                    |""\n";
                cout << " |  ---               |""\n";
                cout << " |  ---        Hs     |""\n";
                cout << " |  ---               |""\n";
                cout << " |                    |""\n";
                cout << " |         14  6  2   | ""\n";
                cout << " |   (Rn)5f  6d 7s    |  ""\n";
                cout << " |        HASSIO      |""\n";
                cout << "  -------------------- ""\n";



                system("color 26");
            }

              



            else {
                HANDLE hConsole = GetStdHandle(STD_OUTPUT_HANDLE);
                SetConsoleTextAttribute(hConsole, opcion);
                cout << " esa opcion no existe-------------------------------------------------------------------------------------------------- ""\n";



            }




            break;
            system("cls");

        case 2:
            exit(EXIT_SUCCESS);
            break;

        default:
            break;
        }



    }
    cin.get();
    return 0;
}






