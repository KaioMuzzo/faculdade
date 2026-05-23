# Funções
Uma função é um bloco de código com propósito específico.

## Funções permitem:
    - Organizar melhor os programas.
    - Reaproveitar (reutilizar) código, inclusive entre aplicações/sistemas diferentes.

## Como criar uma função:
    - Uma função tem um cabeçalho, onde é declarado seu nome e os eventuais parâmetros (ou argumentos) que deva receber.

## Parâmetros(ou argumentos)
    - São valores passados à função no momento de sua chamada.
    - Teoricamente, uma função pode ter uma quantidade qualquer de parâmetros (veja na doc. da linguagem).
    - Se uma função espera dois parâmetros, mas apenas um valor é passado, poderá haver erro (ver doc. da linguagem).

## Retorno
    - Uma função pode retornar (devolver) um valor no local de sua chamada.
    - O valor de retorno é o resultado da execução da função.
    - Quando há o retorno do valor, a execução da função termina.

# Escopo de variáveis
- Escopo é o espaço que as variáveis ocupam na memória RAM.
- O escopo determina se a variável será visível ou não em determinada parte do programa.
- Existem dois escopos, basicamente:
    - Global: as variáveis que ocupam esse escopo são visíveis pelo programa inteiro.
    - Local: as variáveis que ocupam um escopo local (ex: uma função) são visíveis apenas dentro desse escopo.

# Biblioteca
É um arquivo separado, onde colocamos as funções que usaremos nos programas.
Dentro de cada programa, basta chamar (carregar) a biblioteca.
Com isso, funções podem ser usadas em programas diferentes.