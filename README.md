# Activitie-61_Linguagem-C
Questão de exercício sobre vetores em linguagem C.

 

 
     #include <stdio.h>
    int main() {
    int numeros[6] = { 42, -7, 23, 29, 0, 15 }, maior = numeros[1], menor = numeros[0]
    

 
     for (int i = 1; i < 6; i++) {
        if (numeros[i] > maior) {
            maior = numeros[i];
        }
        if (numeros[i] < menor) {
            menor = numeros[i];
        }
    }

    printf("O maior valor no vetor é: %d\n", maior);
    printf("O menor valor no vetor é: %d\n", menor);

    return 0;
}
