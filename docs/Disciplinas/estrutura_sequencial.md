# Programação com Python - Aula 01 - Semana Intensiva 

## Estrutura Sequencial

O que é Estrutura Sequencial?

Imagine um programa de computador como uma receita: cada passo precisa ser executado em uma ordem específica para se chegar ao resultado final. A estrutura sequencial é o conceito fundamental que define essa ordem linear de execução. Em Python, as instruções são executadas linha por linha, uma após a outra.

Conceitos Essenciais
**Variáveis:**
São como recipientes que armazenam dados, como números, textos ou valores lógicos.
Exemplo:
```python
nome = "João"
idade = 30
altura = 1.75
```

**Input:**
A função input() permite que o programa interaja com o usuário, solicitando dados.
Exemplo:
Python
```python
nome = input("Digite seu nome: ")
print("Olá,", nome + "!")
```

**Print:**
A função print() exibe informações na tela.
Exemplo:
Python
```python
numero1 = 10
numero2 = 5
soma = numero1 + numero2
print("A soma é:", soma)
```
**Conversão de tipos**
É crucial converter a entrada do usuário para o tipo de dado desejado, pois a função input() sempre retorna uma string.

**Input de Inteiros**
Quando você precisa que o usuário digite um número inteiro, como uma idade ou um quantidade, você pode utilizar a função `input()` e converter o valor retornado para o tipo `int.`

```python
idade = int(input("Digite sua idade: "))
print("Você tem", idade, "anos.")
```
*Explicação:*

`input("Digite sua idade: ")` ➡️ Essa parte exibe a mensagem para o usuário e aguarda a entrada.
`int()` ➡️ Essa função converte a string digitada pelo usuário em um número inteiro.
`idade`  O valor convertido é armazenado na variável idade.

**Input de Números de Ponto Flutuante (Float)**
Para coletar números com casas decimais, como alturas ou pesos, utilizamos a função `float()` para converter a entrada.
```python
altura = float(input("Digite sua altura (em metros): "))
print("Sua altura é", altura, "metros.")
```
#### Exemplo Completo
```python
nome = input("Digite seu nome: ")
idade = int(input("Digite sua idade: "))
altura = float(input("Digite sua altura (em metros): "))

print("Olá,", nome + "!")
print("Você tem", idade, "anos e", altura, "metros de altura.")
```
