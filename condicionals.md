# Estruturas Condicionais

### If e else

Em Python, os condicionais são bem tranquilos, são funções, que executam determinado linha de código se o que estiver na condição for verdadeiro:

```cpp
   x = int(input())
   if(x > 10): #Se a condição proposta dentro do if for verdadeira, ele executa o que estiver dentro do if
      print("O número é maior que 10") #Irá imprimir na tela a msg caso o x for maior que 10
   else:
      print("O numero é menor ou igual a 10") #Imprime a mensagem caso a condição anterior seja falsa      
```

### Elif

Também é possível colocar uma condição de "se não" após um if, fazendo que ele teste o primeiro caso e caso seja falso, ele pode testar outro caso com outra condição.

Ex: Ver se o número lido é maior que 30 ou menor que -1

```cpp
    x = int(input())
    if(x > 30):
        print("Numero maior que 30")
    elif(x < -1):
        print("Numero menor que -1")
    else:
        print("Numero fora do intervalo procurado")
   
```

Note que o programa verifica primeiramente se o número é maior que 30, se for verdade ele entra no primeiro comendo e depois para de executar, pois a primeira condição foi verdade, caso contrário ele entra no teste da segunda condição, verificando se o número é menor que -1, se for verdade ele entra nessa linha de comando imprimindo a mensagem de que o número é menor que -1 e caso **TODAS** as anteriores sejam falsas, ele imprime a mensagem final.

### Operações and e or 

Podemos também ter múltiplas condições dentro de um mesmo if ou elif, utilizando a operação lógica "E" \( do inglês AND\) ou a operação lógica "OU" \(do inglês OR\).

Ex1: Mesmo exemplo que o anterior, porém de um jeito mais otimizado

```cpp
x = int(input())
if(x > 30 or x < -1):
    print("Numero dentro do intervalo")
else:
    print("Numero fora do intervalo")
```

Ex2: Verificando se o numero pertence ao intervalo \[30,45\]

```cpp
x = int(input())
if(x >= 30 and x <= 45):
    print("Numero dentro do intervalo")
else:
    print("Numero fora do intervalo")
```

## Exercícios

| 1 - [Teste de Seleção 1](https://www.urionlinejudge.com.br/judge/pt/problems/view/1035) | 2 - [Fórmula de Bhaskara](https://www.urionlinejudge.com.br/judge/pt/problems/view/1036) | 3 - [Intervalo](https://www.urionlinejudge.com.br/judge/pt/problems/view/1037) |
| :--- | :--- | :--- |
| 4 -	[Lanche](https://www.urionlinejudge.com.br/judge/pt/problems/view/1038) | ... Todos até 52 \( 1035 ~ 1052\) ... | 17 - [Mês](https://www.urionlinejudge.com.br/judge/pt/problems/view/1052) |



