# Programação com Python - Aula 02 - Semana Intensiva 


## Estrutura de Decisão

O que é Estrutura de Decisão?

Imagine que você está escrevendo um programa para verificar se uma pessoa é maior de idade. Você precisará tomar uma decisão: se a idade for maior ou igual a 18, a pessoa é considerada maior de idade, caso contrário, é menor. Essa capacidade de tomar decisões com base em condições é o que chamamos de estrutura de decisão.

Em Python, as estruturas de decisão são implementadas principalmente com as palavras-chave if, elif e else.


**O Comando ``if``**

O comando if permite executar um bloco de código somente se uma determinada condição for verdadeira.

```python
idade = 18
if idade >= 18:
    print("Você é maior de idade.")
```

**O Comando ``else``**
O comando ``else`` é usado para executar um bloco de código caso a condição do if seja falsa.

```python
idade = 15
if idade >= 18:
    print("Você é maior de idade.")
else:
    print("Você é menor de idade.")
```

**O Comando ``elif``**
O comando ``elif`` (abreviação de "else if") permite testar múltiplas condições em sequência.

```python
nota = 7.5
if nota >= 9:
    print("Aprovado com louvor!.")
elif nota >= 7:
    print("Aprovado.")
else:
    print("Reprovado.")
```

**Tipos de Dados True e False**

Já estudamos alguns tipos de dados. Os dados númericos ``int`` e ``float`` e as cadeias de caracteres ``strings``.

O que são dados Booleanos?

Em Python, os valores True (verdadeiro) e False (falso) representam o tipo de dado booleano. Eles são fundamentais para a tomada de decisões em seus programas, permitindo que você compare valores, execute ações condicionais e construa lógica mais complexa.

Quando usamos Booleanos?

_Expressões lógicas:_ Resultados de comparações (igualdade, desigualdade, maior que, menor que).

_Condições_: Dentro de estruturas de controle como if, elif e else.
Funções que retornam valores booleanos: Por exemplo, funções que verificam se um elemento está presente em uma lista.


**Operadores Lógicos**

Os operadores lógicos em Python são ferramentas poderosas que permitem combinar várias condições em uma única expressão, tornando seu código mais conciso e expressivo. Eles são especialmente úteis ao trabalhar com estruturas de decisão, como o ``if``, ``elif`` e ``else``.

**Quais são os principais operadores lógicos em Python?**

``and``: Retorna True(verdadeiro) se todas as condições forem verdadeiras. Pode ser entendido como operador de soma (e)

``or``: Retorna True(verdadeiro) se pelo menos uma das condições for verdadeira. Pode ser entendido como operador de alternativa (ou)

``not``: Inverte o valor lógico de uma expressão. Se for verdadeiro(True) converte em falso(False). Pode ser entendido como operador de alternativa (não)

#### Exemplo 1

```python
idade = 25
tem_carteira = True

# Verificando se a pessoa é maior de idade e tem carteira de motorista
if idade >= 18 and tem_carteira:
    print("Pode dirigir.")

# Verificando se a pessoa é menor de idade ou não tem carteira de motorista
if idade < 18 or not tem_carteira:
    print("Não pode dirigir.")
```

#### Exemplo 2

```python
nota = 7
faltas = 5

if nota >= 7 and faltas <= 10:
    print("Aprovado.")
elif nota < 7 or faltas > 10:
    print("Reprovado.")
```

Baixe aqui o arquivo da aula aqui 

https://github.com/CTInternet/arquivos/blob/main/L%C3%B3gica%20com%20python%20-%20Estrutura%20decis%C3%A3o/Aula02_EstruturaDecis%C3%A3o.ipynb