
<h1 align="center">
  Lista de Exercícios
</h1>

<h4 align="center">Revisão de Conceitos da Disciplina SI100 - Algoritmos e Programação de Computadores I.</h4>

| Tópico | Descrição |
|---|-------|
| A | [Algoritmos e Fluxogramas](#topico-a) |
| B | [Tipos de Dados, Constantes, Variáveis e Printf (valor, endereço e tamanho)](#topico-b) |
| C | [Scanf e Precedência de Operadores (atribuição, aritmético, incremento, decremento, relacionais, lógicos)](#topico-c) |
| D | [Estruturas de decisão (if, switch)](#topico-d) |
| E | [Estruturas de repetição (for, while, do-while)](#topico-e) |

## Recomendações

 Ao ler cada exercício, se pergunte:
 1. Eu conseguiria fazer esse código com os conhecimentos que tenho?
 2. Saberia explicar o porquê de cada parte do código funciona como funciona?
 3. O que preciso aprender para conseguir fazer esse exercício?

 Algumas instruções:
 1. Faça os exercícios sem ajuda de IA para gerar os códigos, tente se forçar a
 pensar de acordo com a lógica da programação para a encontrar as soluções
 2. Se necessário, use IA para corrigir seus erros depois do código já feito,
 mas também pode-se buscar a ajuda dos colegas (para aprenderem juntos)
 e do monitor pelo contato fornecido no Moodle.

## Exercícios

<details id="topico-a">
    <summary style="font-size:20px"><b>A. Algoritmos e Fluxogramas</b></summary>

1. Transforme o <mark>algoritmo</mark> abaixo em um programa:

```
ALGORITMO PERIMETRO_AREA

/* Calcula o perímetro e a área de uma circunferência
   de raio R (fornecido pelo usuário) */

/* Definir variáveis */
    int Raio;
    float Perim, Area, PI;
    PI = 3.14159;

/* Obter Raio da circunferência */
    Escreva("Entre com o valor do raio:");
    Leia(Raio);

/* Calcular Perímetro do Círculo */
    Perim = 2 * PI * Raio;

/* Calcular área da circunferência */
    Area = PI * Raio * Raio;

/* Exibir Resultados */
    Escreva("O perimetro da circunferencia de raio ", Raio, " eh ", Perim);
    Escreva("e a area eh ", Area);

/* Terminar Programa */

FIM_ALGORITMO PERIMETRO_AREA
```

```c
#include <stdio.h>

void main()
{
    // ToDo
}
```
</details>

<br>

<details id="topico-b">
    <summary style="font-size:20px"><b>B. Tipos de Dados, Constantes, Variáveis e Printf (valor, endereço e tamanho)</b></summary>

2. Para o código abaixo, apresente o <mark>teste de mesa</mark> e a saída do programa:

```c
#include <stdio.h>
int main()
{
    int x, y, z;
    x = y = 10;
    z = x++;
    y = ++x;
    x = -x;
    y++;
    x = x + y - z--;
    printf("%d " "%d " "%d ", x, y, z);
    return 0;
}
```
| Variável | Memória |
|---|-------|
| x | |
| y | |
| z | |

> **Saída:**

3. Para o código abaixo, apresente a <mark>saída do programa</mark>:

```c
#include <stdio.h>
int main()
{
    printf("%d \n", 5 + 10 * 5 % 6); (ORDEM * % +)
    printf("%d \n", 10 / 4);
    printf("%f  \n", 10.0 / 4.0);
    printf("%.2f \n", 10.0 / 4.0);

    float b = 15.2983;
    printf ("|%f| \n", b);
    printf ("|%2f| \n", b);
    printf ("|%8.1f| \n", b);
    printf ("|%-7.2f| \n", b);
    printf ("|%09.3f| \n", b);

    int a = 3;
    printf ("%d, %d, %d, %d", a == 3, a = 3, a != 3, a == '3');
    
     printf ("%d", ('C' == 'C' || 'C' == 'c') && 'C' == 'c');
    return 0;
}
```

> **Saída:**

4. Escreva um programa que <mark>declare</mark> duas variáveis inteiras e exiba seus valores na tela.

```c
#include <stdio.h>

void main()
{
    // ToDo
}
```
</details>

<br>

<details id="topico-c">
    <summary style="font-size:20px"><b>C. Scanf e Precedência de Operadores (atribuição, aritmético, incremento, decremento, relacionais, lógicos)</b></summary>

5. Escreva um programa que <mark>leia</mark> 3 números inteiros. Apresente a soma, média e o produto dos números.

```c
#include <stdio.h>

void main()
{
    // ToDo
}
```

6. Faça um programa que pergunte o salário por hora e o número de horas trabalhadas no mês. <mark>Calcule e mostre</mark> o total do salário no referido mês.

```c
#include <stdio.h>

void main()
{
    // ToDo
}
```

7. Faça um programa que leia o nome de um usuário e exiba uma mensagem de boas-vindas.

```c
#include <stdio.h>

void main()
{
    // ToDo
}
```

8. Crie um programa que leia dois números inteiros e exiba a soma, subtração, multiplicação e divisão entre eles.

```c
#include <stdio.h>

void main()
{
    // ToDo
}
```

9. Desenvolva um programa que calcule a área de um retângulo a partir da leitura da largura e altura.

```c
#include <stdio.h>

void main()
{
    // ToDo
}
```

10. Escreva um programa que converta uma temperatura de Fahrenheit para Celsius, a partir de um dado do usuário.

```c
#include <stdio.h>

void main()
{
    // ToDo
}
```

11. Faça um programa que leia o salário de um funcionário e calcule o valor de um <mark>aumento de 10%</mark>, exibindo o novo salário.

```c
#include <stdio.h>

void main()
{
    // ToDo
}
```

12. Crie um programa que leia três números reais e calcule a média aritmética entre eles.

```c
#include <stdio.h>

void main()
{
    // ToDo
}
```

13. Desenvolva um programa que leia o valor de um produto e o percentual de desconto e calcule o preço final do produto.

```c
#include <stdio.h>

void main()
{
    // ToDo
}
```

14. Escreva um programa que leia um número inteiro e calcule o <mark>seu quadrado e o seu cubo</mark>.

```c
#include <stdio.h>

void main()
{
    // ToDo
}
```

15. Faça um programa que leia o raio de um círculo e calcule o valor da sua área e circunferência.

```c
#include <stdio.h>

void main()
{
    // ToDo
}
```
</details>

<br>

<details id="topico-d">
    <summary style="font-size:20px"><b>D. Estruturas de decisão (if, switch)</b></summary>

16. Escreva um programa que leia um número inteiro e verifique se ele é <mark>par ou ímpar</mark>.

```c
#include <stdio.h>

void main()
{
    // ToDo
}
```

17. Desenvolva um programa que leia a idade de uma pessoa e verifique se ela é maior de idade.

```c
#include <stdio.h>

void main()
{
    // ToDo
}
```

18. Faça um programa que leia três números e exiba o maior entre eles.

```c
#include <stdio.h>

void main()
{
    // ToDo
}
```

19. Escreva um programa que calcule o IMC (Índice de Massa Corporal) de uma pessoa e determine a classificação de acordo com a tabela padrão.

```c
#include <stdio.h>

void main()
{
    // ToDo
}
```

20. Crie um programa que leia dois números e determine se o primeiro é <mark>divisível</mark> pelo segundo.

```c
#include <stdio.h>

void main()
{
    // ToDo
}
```

21. Faça um programa que leia um número e exiba se ele é positivo, negativo ou zero.

```c
#include <stdio.h>

void main()
{
    // ToDo
}
```

22. Escreva um programa que leia a nota de um aluno e informe se ele foi aprovado, reprovado ou se está em recuperação, considerando os seguintes critérios: 
- nota >= 7 (aprovado)
- 5 <= nota < 7 (recuperação)
- nota < 5 (reprovado).

```c
#include <stdio.h>

void main()
{
    // ToDo
}
```

23. Crie um programa que leia a distância percorrida (em km) e o tempo gasto (em horas) e calcule a velocidade média de um veículo.

```c
#include <stdio.h>

void main()
{
    // ToDo
}
```

24. Desenvolva um programa que leia o preço de três produtos e determine qual deles é o mais barato.

```c
#include <stdio.h>

void main()
{
    // ToDo
}
```

25. Escreva um programa que leia o salário de um funcionário e exiba o valor do imposto de renda a ser pago, com base nas seguintes faixas de tributação:
 - até R$ 1.903,98 (isento)
 - de R$ 1.903,99 a R$ 2.826,65 (7,5%)
 - de R$ 2.826,66 a R$ 3.751,05 (15%)
 - de R$ 3.751,06 a R$ 4.664,68 (22,5%)
 - acima de R$ 4.664,68
 (27,5%).

```c
#include <stdio.h>

void main()
{
    // ToDo
}
```
</details>

<br>

<details id="topico-e">
    <summary style="font-size:20px"><b>E. Estruturas de repetição (for, while, do-while)</b></summary>

26. Crie um programa que exiba os números de 1 a 10 utilizando um loop <mark>for</mark>.

```c
#include <stdio.h>

void main()
{
    // ToDo
}
```

27. Escreva um programa que leia um número e exiba todos os números de 0 até esse número, utilizando um loop <mark>while</mark>.

```c
#include <stdio.h>

void main()
{
    // ToDo
}
```

28. Faça um programa que calcule a soma dos números de 1 a 100 utilizando um loop for.

```c
#include <stdio.h>

void main()
{
    // ToDo
}
```

29. Desenvolva um programa que exiba a tabuada de um número fornecido pelo usuário, utilizando um loop for.

```c
#include <stdio.h>

void main()
{
    // ToDo
}
```

30. Escreva um programa que leia um número e exiba todos os números pares entre 1 e esse número, utilizando um loop while.

```c
#include <stdio.h>

void main()
{
    // ToDo
}
```

31. Faça um programa que leia 10 números e conte quantos deles são positivos, negativos ou zero.

```c
#include <stdio.h>

void main()
{
    // ToDo
}
```

32. Crie um programa que leia um número e determine se ele é <mark>primo</mark> ou não, utilizando um loop for.

```c
#include <stdio.h>

void main()
{
    // ToDo
}
```

33. Escreva um programa que leia um número e exiba a <mark>soma dos seus dígitos</mark>, utilizando um loop while.

```c
#include <stdio.h>

void main()
{
    // ToDo
}
```

34. Faça um programa que leia vários números inteiros até que o número 0 seja digitado, e calcule a média desses números.

```c
#include <stdio.h>

void main()
{
    // ToDo
}
```

35. Crie um programa que gere <mark>números aleatórios</mark> de 1 a 100 e permita que o usuário tente adivinhar, fornecendo dicas de "maior" ou "menor" até acertar o número correto

```c
#include <stdio.h>

void main()
{
    // ToDo
}
```

36. Para o código abaixo, apresente a saída do programa, considerando o comportamento dos comandos <mark>break e continue</mark>:

```c
#include <stdio.h>
int main() {
    for (int i = 1; i <= 10; i++) {
        int num = i;

        while (num < 10) {
            if (num % 2 == 0) { 
                num++;
                continue;
            }

            printf("%d", num);
            
            if (num > 8)
                break;

            num++;
        }
    }
    return 0;
}

```

> **Saída:**
</details>




