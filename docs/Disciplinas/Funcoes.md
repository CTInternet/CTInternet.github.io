# Funções

Em programação, uma função é um bloco de código que realiza uma tarefa específica. Ela é como uma receita que você pode seguir várias vezes, com diferentes ingredientes (parâmetros), para obter resultados diferentes.
Funções representam uma das principais ferramentas para a construção de programas modulares e organizados, uma vez que permitem agrupar operações sob um nome único, que pode ser chamado sempre que necessário. 

🗒️ Arquivo para Download <a href="https://github.com/CTInternet/arquivos/blob/main/Algoritmos%20e%20L%C3%B3gica%20de%20Programa%C3%A7%C3%A3o/08%20Fun%C3%A7%C3%B5es/Funcoes.ipynb" target="_blank">➡️ 🤓 Funções em Python 🐍 ⬅️</a> 🗒️

```python
# Definindo uma função com parâmetro
def saudacao(nome):
    print('Hello %s' %(nome))
```


```python
saudacao('Aluno')
```

    Hello Aluno
    

### Variáveis locais e globais


```python
# Variável Global
meu_numero = 10  # Esta é uma variável global

def multiplicar(num1, num2):
    meu_numero = num1 * num2  # Esta é uma variável local
    print(meu_numero)
```


```python
multiplicar(10, 15)
```

    150
    


```python
meu_numero
```




    10



### Funções Built-in (embutidas)


```python
abs(-56)
```




    56




```python
abs(23)
```




    23




```python
bool(0)
```




    False




```python
bool(1)
```




    True



### Funções str, int, float


```python
int("26")
```




    26




```python
float("123.345")
```




    123.345




```python
str(14)
```




    '14'



# Exercícios

1 - Crie uma função que receba um número e retorne o seu dobro.


```python
def dobrar_valor(numero):
    dobro = numero*2

    return (dobro)
```


```python
dobrar_valor(90)
```




    180



2 - Crie uma função que verifique se um número é par.

````python
num1 = int(input("Informe um número"))
if num1 % 2 == 0:
    print (f"{num1} é par")

else:
    print (f'{num1} é impar')
````


```python

```


```python
verifica_par(9)
```

    9 é impar
    

3 - Crie uma função que receba uma lista de números e retorne a soma de todos os elementos


```python

```


```python

```

4 - Crie uma função que receba uma lista de números e retorne a média.


```python

```


```python

```

5 - Crie uma função que receba uma lista de números e retorne uma nova lista com os números pares


```python

```


```python

```

6 - Crie uma função contar_ocorrencias que receba uma lista e um elemento, e retorne quantas vezes esse elemento aparece na lista.


```python

```


```python

```

7 - Crie uma função que verifica se o número é positivo ou negativo, e retorne seu valor absoluto. 
