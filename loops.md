# Estruturas de Repetição

As  estruturas de repetição, ou conhecidas também por laços de repetição, são estruturas que executam parte do código em uma certa quantidade de vezes. Pare para pensar, se você possui um problema que a entrada são 3 números? A resposta é simplesmente fazer 3 `input()`, mas e se agora a entrar for **n **números? Basta fazer um laço de repetição n vezes e colocar um `input()` dentro.

### For loops

O for é uma estrutura de repetição que possui uma sintaxe um pouco diferente das outras, pois ele pode ser escrito de diversas maneiras. Basicamente, o for é divido em 2 partes: `for X in Y` , o X vai ser uma variável que será atribuída com valores propostos em Y, como por exemplo:

##### 1 - Iterações/Caminhando em números

Para iterar a variável declarada no lugar de X em números, primeiro deve ser definido a variável X \(que pode ser qualquer nome da variável, porém é mais utilizado a variável i apenas por convenção\) e depois por onde que ela irá iterar/caminhar. O método `range(x)` quem em português seria "alcance" determina o intervalo limite de iterações, **note que as iterações COMEÇAM em 0** **e o limite é enquanto a iteração for menor que o valor colocado dentro do **`range()`**.**

```cpp
# O valor de i vai começar em 0 e vai sendo incrementado de 1 em 1 enquanto i < 5
for i in range(5):
    print(i)  #Será impresso na tela os números 0,1,2,3,4
```

Dentro do próprio `range(x)`, pode ser colocado mais parâmetros que tornam o laço for diferente, como por exemplo

```py
# Adicionando mais 1 numero dentro do range(x, y), agora o i vai começar em x e continua enquanto x < y
for i in range(3, 8):
    print(i) #Imprime 3,4,5,6,7

# Adicionando ainda mais 1 numero, range(x, y, z), agora o i começa em x, vai até y e vai pulando de z em z
for i in range(3, 10, 2): #Antes o i ia de 1 em 1, agora com o 2 no terceiro parâmetro ele irá de 2 em 2
    print(i) #Imprime 3, 5, 7, 9
```

##### 2 - Iterações/Caminhando em outros tipos de dados

Também é possível iterar em vetores, mapas e diversas estruturas de dados, como por exemplo

```cpp
nomes = ["Thiago", "Maria", "José", "Douglas"]
for i in nomes:
    print(i)
```

### **While loops**

Já os laços While, que em português significa "enquanto", se assemelha com o condicional if, porém no if se a condição dentro for verdadeira ele executa aquele bloco de código, ja no while, enquanto a condição proposta for verdadeira ele repete aquela linha de código, ele não só executa como repete tudo caso ainda seja verdade.

```cpp
n = 10
while(n > 0): #Enquanto o n for positivo ele continua imprimindo na tela e a cada iteração ele diminui uma unidade de n
 print(n)
 n = i - 1
```

Tomem bastante cuidado para não entrar no famoso **loop infinito, **caso a condição proposta seja sempre verdade.

```cpp
n = 10
while(n < 20): #Como o n já é menor que 20 e ele está decrementando o n, a condição de dentro SEMPRE será verdade
 print(n) #Irá imprimir para sempre o valor de n
 n = n - 1
```

### Break e Continue

O break é utilizado dentro de laços de repetição para poder sair dele.

```cpp
n = 10
while(n > 0):
    print(n) #Imprime 10,9,8,7,6,5
    if(n == 5): #Caso n seja = 5, o break é executado para sair do laço
        break
    n = n-1
```

Já o continue é utilizado \(não somente\)  para ignorar o restante do bloco dentro o laço e partir para a próxima iteração

```cpp
for i in range(5,14):
    if(i%2 == 0): #Verifica se o número é par, caso seja ele ignora o resto do código e vai para o próximo número
        continue
    print(i) #Imprime 5,7,9,11,13
```

## Exercícios

| 1 - [Números Pares](https://www.urionlinejudge.com.br/judge/pt/problems/view/1059) | 2 - [Números Positivos](https://www.urionlinejudge.com.br/judge/pt/problems/view/1060) | 3 - [Positivos e Média](https://www.urionlinejudge.com.br/judge/pt/problems/view/1064) |
| :--- | :--- | :--- |
| 4 - [Pares entre Cinco Números](https://www.urionlinejudge.com.br/judge/pt/problems/view/1065) | 5 -[ Fibonacci Fácil](https://www.urionlinejudge.com.br/judge/pt/problems/view/1151) | 6 - [Dividindo X por Y](https://www.urionlinejudge.com.br/judge/pt/problems/view/1116) |
| 7-   [Número Primo](https://www.urionlinejudge.com.br/judge/pt/problems/view/1165) | ... Todos de repetição ... | 9 -[ Número Perfeito](https://www.urionlinejudge.com.br/judge/pt/problems/view/1164) |



