# Revisão de Prova Bimestral - Tema 1 - Strings

### Criando uma String
Para criar uma string em Python você pode usar aspas simples ou duplas. Por exemplo:


```python
# Uma única palavra
'Oi'
```


```python
# Uma frase
'Criando uma string em Python'
```




    'Criando uma string em Python'




```python
# Podemos usar aspas duplas
"Podemos usar aspas duplas ou simples para strings em Python"
```


```python
# Você pode combinar aspas duplas e simples
"Testando strings em 'Python'"
```

### Imprimindo uma String


```python
print ('Testando Strings em Python')
```


```python
print ('Testando \nStrings \nem \nPython')
```


```python
print ('\n')
```

### Indexando Strings


```python
# Atribuindo uma string
s = 'Data Science Academy'
```


```python
print(s)
```


```python
# Primeiro elemento da string. 
s[0]
```


```python
s[1]
```


```python
s[2]
```

Podemos usar um : para executar um slicing que faz a leitura de tudo até um ponto designado. Por exemplo:


```python
# Retorna todos os elementos da string, começando pela posição (lembre-se que Python começa a indexação pela posição 0),
# até o fim da string.
s[1:]
```


```python
# A string original permanece inalterada
s
```


```python
# Retorna tudo até a posição 3
s[:3]
```


```python
s[:]
```


```python
# Nós também podemos usar a indexação negativa e ler de trás para frente.
s[-1]
```


```python
# Retornar tudo, exceto a última letra
s[:-1]
```

Nós também podemos usar a notação de índice e fatiar a string em pedaços específicos (o padrão é 1). Por exemplo, podemos usar dois pontos duas vezes em uma linha e, em seguida, um número que especifica a frequência para retornar elementos. Por exemplo:


```python
s[::1]
```


```python
s[::2]
```


```python
s[::-1]
```

### Propriedades de Strings


```python
s
```


```python
# Concatenando strings
s + ' é a melhor maneira de estar preparado para o mercado de trabalho em Ciência de Dados!'
```


```python
s = s + ' é a melhor maneira de estar preparado para o mercado de trabalho em Ciência de Dados!'
```


```python
print(s)
```


```python
# Podemos usar o símbolo de multiplicação para criar repetição!
letra = 'w'
```


```python
letra * 3
```

### Funções Built-in de Strings


```python
s
```


```python
# Upper Case 
s.upper()
```


```python
# Lower case
s.lower()
```


```python
# Dividir uma string por espaços em branco (padrão)
s.split()
```


```python
# Dividir uma string por um elemento específico
s.split('y')
```

### Funções String


```python
s = 'seja bem vindo ao universo de python'
```


```python
s.capitalize()
```


```python
s.count('a')
```


```python
s.find('p')
```


```python
s.center(20, 'z')
```


```python
s.isalnum()
```


```python
s.isalpha()
```


```python
s.islower()
```


```python
s.isspace()
```


```python
s.endswith('o')
```


```python
s.partition('!')
```

### Comparando Strings


```python
print("Python" == "R")
```


```python
print("Python" == "Python")
```

# Exercícios

1 - Crie uma string com seu nome completo e imprima-a na tela.


```python

```

2 - Indexe a string para obter a primeira letra do seu nome.


```python

```

3 - Fatie a string para obter apenas o seu sobrenome.


```python

```

4 - Concatene sua string com a frase "está aprendendo Python".


```python

```

5 - Converta toda a string para letras maiúsculas e depois para minúsculas.


```python

```

6 - Crie uma string com uma frase qualquer e conte quantas vezes a letra "a" aparece.


```python

```
