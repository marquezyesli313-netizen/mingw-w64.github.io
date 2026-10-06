ENCABEZADO'
#include <stdio.h> // libreria para usar printf (imprimir en pantalla)
CUERPO DEL PROGRAMA'
int main() // aqui empieza todo programa en C
DECLARACION DE VARIABLES'
Aunque tu flujograma es lineal, declaramos'
variables por si quieres guardar horas'
    int hora_inicio = 5; // 5 am
    int hora_clases = 7; // 7 am
    int hora_salida = 14; // 2 pm = 14 hrs
    char nombre[20] = "Estudiante"; // ejemplo de variable texto

    // Mensaje de inicio
    printf("=== MI RUTINA DIARIA - Flujograma Personal ===\n");
    printf("Estudiante de Ing. Quimica - Pachuca\n\n");

    // Cada cuadro de tu flujograma es un printf
    printf("5:00 am - Me levanto (Inicio)\n");
    printf("5:15 am - Me bano\n");
    printf("5:30 am - Me alisto\n");
    printf("5:40 am - Tiendo mi cama\n");
    printf("6:00 am - Desayuno\n");
    printf("6:15 am - Me lavo los dientes\n");
    printf("6:30 am - Me voy a la UNI\n");
    printf("7:00 am - Primera clase\n");
    printf("2:00 pm - Salida de clases\n");
    printf("2:30 - 3:00 pm - Llegada a mi cuarto\n");
    printf("3:30 - 4:00 pm - Como\n");
    printf("4:15 pm - Limpio todo mi cuarto\n");
    printf("5:20 pm - Realizo todas mis tareas\n");
    printf("11:00 pm - 5:00 am - Duermo / Fin\n");

    printf("\n--- Fin del dia. Total: 24 horas ---\n");

    return 0; // indica que el programa termino bien


