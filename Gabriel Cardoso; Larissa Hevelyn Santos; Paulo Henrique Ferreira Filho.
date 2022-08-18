#include <stdio.h>
#include <stdlib.h>
#include <string.h>
#define MAX_CLIENTES 3

struct Clientes {
    char nome[50];
    int idade;
    char sexo;
    int i;

    Clientes () {
        for (i=0; i<=49; i++) {
                scanf("%s", &nome[i]);
        }
        printf("Sexo: M ou F?: \n");
        scanf("%c", &sexo);
    }
};


struct Data_de_nascimento {
    int dia, mes, ano;
    int dia_atual, mes_atual, ano_atual;
    printf("Informe a sua data de nascimento:/n dia: /n, mes: /n, ano; /n");
    scanf("%d %d %d", &dia, &mes, &ano);
    printf("Informe a data de hoje:/n dia: /n, mes: /n, ano; /n");
    scanf("%d %d %d", &dia_atual, &mes_atual, &ano_atual);

    void Calcula_idade (int _dia, int _mes, int _ano, int _dia_atual, int _mes_atual, int _ano_atual) {
        idade = (dia_atual - dia) (mes_atual - mes) (ano_atual - ano);
    }

};

struct Clientes cliente[MAX_CLIENTES] {
    int n_clientes = 0;
};

    void Cadastra_cliente (struct clientes cliente) {
        clientes[n_clientes] = cliente;
        n_clientes++;
    }

    void Imprimir_clientes () {
        for (i=0; i<n_clientes; i++) {
                printf ("Nome: %s \n", Clientes[i].nome);
                printf("sexo: %c \n", Clientes[i].sexo);
                printf("Idade: %d \n", Clientes[i].idade);
        }
    }
return 0;
