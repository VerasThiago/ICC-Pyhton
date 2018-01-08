# Variáveis e entrada de dados
### Variáveis.
Em Python, declarar e ler varáveis é algo bem simples, veja o exemplo:
```cpp
    x = 10             # x recebe 10
    y = "Olá amigos"   # y recebe a frase "Olá amigos"
```
Deve se atentar ao sinal "=", pois em programação este sinal não significa igualdade, e sim atribuição, então deve ter em mente que x = 10 é equivalente a x recebe 10. Para equivalência, se utiliza "==".

### Entrada de dados.
Apenas trabalhar com atribuição de variáveis seria algo muito sem graça, com isso podemos ler do teclado qualquer entrada do usuário, por exemplo:
```
    x = input() 
    y = input()
    print(x)
```
Com este comando a sua IDE ou o terminal ficará esperando que o usuário digite alguma coisa, podendo ser um numero, uma grase e depois pressione enter para poder atribuir a entrada a variável x, e o mesmo com a variável y. Já o comando print é utilizado para imprimir na tela vários tipos de conteúdos, inclusive o conteúdo da variável x por exemplo.

### Operações
Em python, as variável são atribuidas e trabalhas como se fossem Strings (frases), então caso tivéssemos um programa assim:

```
    x = input() 
    y = input()
    z = x + y
    print(z)
```
Se o usuário digitar 10 e pressionar o enter e depois 20 e pressionar o enter, o que será impresso na tela será 10 + 20 = 1020   ?!?! Para resolver este problema, bastar dar um cast (forçar o input para o tipo do cast que for feito) na variável, para torná-la do tipo que o programador quiser.

```
    x = int(input()) #Dando cast no input para transformar em inteiro
    y = int(input())
    z = x + y
    print(z)
``` 
Existem diversos tipos variáveis, mas o mais comuns são:
1. Inteiros (int)
2. Os numero reais ou ponto flutuante (float)
3. Frases (string)

Agora que já foi explicado tudo sobre variáveis e entrada de dados, segue uma lista de exercícios para treinar, para isso, voce deve se cadastar no site do [URI].(https://www.urionlinejudge.com.br/judge/en/login) e efetuar o login para poder começar a exercitar, basta escrever seu código que solucione o problema descrito, depois copiá-lo, clicar no botão de enviar, colar o seu código, escolher a linguagem Python 3 (Python 3.4.3)[+1s] e enviar para que um corretor online julgue seu programa como certo ou errado.

## Exercícios
1 - [Extremamente Básico](https://www.urionlinejudge.com.br/judge/pt/problems/view/1001)

2 - [Área do Círculo](https://www.urionlinejudge.com.br/judge/pt/problems/view/1002)

3 - [Soma Simples](https://www.urionlinejudge.com.br/judge/pt/problems/view/1003)

4 - [Produto Simples](https://www.urionlinejudge.com.br/judge/pt/problems/view/1004)

5 - [Média 1](https://www.urionlinejudge.com.br/judge/pt/problems/view/1005)

6 - [Média 2](https://www.urionlinejudge.com.br/judge/pt/problems/view/1006)

7 - [Diferença](https://www.urionlinejudge.com.br/judge/pt/problems/view/1007)

.

. Todos até 21 (Estão na ordem no site, na categoria iniciante do 1001 ~ 1021)

.

21 - [Notas e Moedas](https://www.urionlinejudge.com.br/judge/pt/problems/view/1021)








