# LOTOFÁCIL

Este é um projeto em Java de um jogo de loteria que contem três opções de aposta: de 0 a 100, de A a Z e em número par ou ímpar.

## Requisitos

- Java Development Kit (JDK)  8 ou superior.
- Editor de código (Usado: Visual Studio Code,IntelliJ).

 ## Funcionamento

O programa oferece um menu com três opções de aposta e uma opção para sair do jogo. O usuário pode escolher entre as seguintes opções:

1. **Apostar de 0 a 100**: O usuário deve inserir um número inteiro entre 0 e 100. Se o número estiver dentro do intervalo válido, o programa sorteia aleatoriamente um número entre 0 e 100 e compara com a aposta do usuário. Se os números forem iguais, o usuário ganha R$ 1.000,00; caso contrário, o programa informa o número sorteado.
2. **Apostar de A à Z**: O usuário deve inserir uma letra entre A e Z, podendo ser minúscula ou maiúscula. Se a entrada não for uma letra, o programa informa que a aposta é inválida. Em seguida, o programa compara a letra escolhida pelo usuário com uma letra premiada (no exemplo fornecido, a letra premiada é 'J'). Se as letras forem iguais, o usuário ganha R$ 500,00; caso contrário, o programa informa a letra premiada.
3. **Apostar em par ou ímpar**: O usuário deve inserir um número inteiro. O programa verifica se o número é par ou ímpar usando o operador de módulo (%). Se o número for par, o usuário ganha R$ 100,00; se for ímpar, o programa informa que a premiação é para números pares.

O loop principal permite que o usuário faça múltiplas apostas até escolher a opção de sair (0).

## Execução

1.  Clone o repositório para o seu ambiente local.
2.  Navegue até o diretório do projeto.
3.  Compile o código fonte do projeto.
4.  Execute o programa.

