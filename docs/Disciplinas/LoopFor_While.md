# Loops de Repetição

## Loop For

O que é um loop For?

Em programação, um loop For é uma estrutura de controle que permite executar um bloco de código repetidamente um número determinado de vezes. Ele é utilizado quando você precisa realizar uma ação várias vezes, como percorrer uma lista, realizar cálculos iterativos ou criar padrões.

Como funciona?

A sintaxe básica de um loop For varia um pouco entre as diferentes linguagens de programação, mas a ideia central é a mesma:

````python
for (inicialização; condição; incremento) {
    // Código a ser executado repetidamente
}

````


**Inicialização**: Define uma variável de controle e atribui um valor inicial.

**Condição:** É uma expressão booleana que determina se o loop continuará a ser executado.

**Incremento**: Atualiza o valor da variável de controle a cada iteração.


```python
# Criando uma tupla e imprimindo cada um dos valores
tupla = (2,3,4)
for i in tupla:
    print(i)
```

    2
    3
    4
    


```python
# Criando uma lista e imprimindo cada um dos valores
ListaDoMercado = ["Leite", "Frutas", "Carne"]
for i in ListaDoMercado:
    print(i)
```

    Leite
    Frutas
    Carne
    


```python
# Imprimindo os valores no intervalo entre 0 e 5 (exclusive)
for contador in range(0,5):
    print(contador)
```

    0
    1
    2
    3
    4
    


```python
# Imprimindo na tela os números pares da lista de números
lista = [1,2,3,4,5,6,7,8,9,10]
for num in lista:
    if num % 2 == 0:
        print (num)
```

    2
    4
    6
    8
    10
    


```python
# Listando os números no intervalo entre 0 e 101, com incremento em 2
for i in range(0,101,10):  
    print(i)
```

    0
    10
    20
    30
    40
    50
    60
    70
    80
    90
    100
    


```python
# Strings também são sequências
for caracter in 'Estudar é primordial!':
    print (caracter)
```

    E
    s
    t
    u
    d
    a
    r
     
    é
     
    p
    r
    i
    m
    o
    r
    d
    i
    a
    l
    !
    


```python
# Operando os valores de uma lista com loop for
listaB = [32,53,85,10,15,17,19]
soma = 0
for i in listaB:
    double_i = i * 2
    soma += double_i

print(soma)
```

    462
    


```python
# Loops em lista de listas
listas = [[1,2,3], [10,15,14], [10.1,8.7,2.3]]
for valor in listas:
    print(valor)
```

    [1, 2, 3]
    [10, 15, 14]
    [10.1, 8.7, 2.3]
    


```python
# Contando os itens de uma lista
lista = [5,6,10,13,17]
count = 0
for item in lista:
    count += 1
    
print(count)
```

    5
    


```python
# Pesquisando em listas
listaC = [5, 6, 7, 10, 50]

# Loop através da lista
for item in listaC:
    if item == 5:
        print("Número encontrado na lista!")
```

## Loop While

O loop while em Python é uma estrutura de controle que permite executar um bloco de código repetidamente enquanto uma determinada condição for verdadeira. Diferentemente do for, que itera um número pré-determinado de vezes, o while continua a execução até que a condição se torne falsa.


```python
# Usando o loop while para imprimir os valores de 0 a 9
counter = 0
while counter < 10:
    print(counter)
    counter = counter + 1
```

    0
    1
    2
    3
    4
    5
    6
    7
    8
    9
    

### Pass, Break e continue

Essas três palavras-chave são ferramentas poderosas em Python para controlar o fluxo de execução dentro de seus loops for e while. Elas permitem que você personalize o comportamento de seus loops, tornando seu código mais eficiente e adaptável.

**pass**

O que faz: É um comando "vazio". Ele indica ao interpretador Python que não deve fazer nada nesse ponto.

**break**

O que faz: Interrompe imediatamente a execução do loop mais interno em que está inserido.


**continue**


O que faz: Pula para a próxima iteração do loop, ignorando o restante do código dentro do loop para aquela iteração específica.


```python
for i in range(10):
    if i == 3:
        pass  # Nada acontece quando i é 3
    elif i == 5:
        break  # Sai do loop quando i é 5
    elif i % 2 == 0:
        continue  # Pula números pares
    print(i)
```

    1
    3
    
Outra maneira de agrupar pass, break e continue:

```python
counter = 0
while counter < 100:
    if counter == 4:
        break
    else:
        pass
    print(counter)
    counter = counter + 1
```

    0
    1
    2
    3
    
O loop também pode ser usado para pesquisar um determinado termo em um conjunto de dados:

```python
for verificador in "Python":
    if verificador == "h":
        continue
    print(verificador)
```

    P
    y
    t
    o
    n
    
Ao usar continue, a condição é ignorada e o próximo laço é executado:

```python
for i in range(10):
    if i % 2 == 0:
        continue  # Pula números pares
    print(i)
```

    1
    3
    5
    7
    9

    
🗒️ Arquivo sobre <a href="https://github.com/CTInternet/arquivos/blob/main/Algoritmos%20e%20L%C3%B3gica%20de%20Programa%C3%A7%C3%A3o/06%20L%C3%B3gica%20com%20python%20-%20Loops%20For%20e%20While/LoopFor_While.ipynb" target="_blank">➡️ Loops de repetição em Python ⬅️</a> 🗒️