# Listas

## O que são listas

Listas em Python são estruturas de dados extremamente versáteis que podem armazenar coleções de itens. Imagine uma lista como uma caixa onde você pode guardar diversos objetos, cada um com suas próprias características.

**Características**

**Ordenadas:** Cada elemento da lista possui um índice numérico, iniciando em 0, que indica sua posição.

**Mutáveis:** Você pode modificar o conteúdo de uma lista após sua criação, adicionando, removendo ou alterando elementos.

**Heterogêneas:** Uma lista pode conter elementos de diferentes tipos de dados, como números, strings, booleanos e até outras listas.
Dinâmicas: O tamanho de uma lista não é fixo e pode crescer ou diminuir conforme você adiciona ou remove elementos.

### Para que servem as listas

**Armazenar dados**: Listas são ideais para armazenar coleções de dados relacionados, como nomes de alunos, preços de produtos, etc.

**Manipular dados**: Você pode realizar diversas operações em listas, como filtrar, ordenar, buscar e modificar dados.

**Criar estruturas de dados mais complexas**: Listas podem ser utilizadas como base para criar outras estruturas de dados, como pilhas, filas e matrizes.


### Exemplos de listas


```python
# Lista vazia
lista_vazia = []

# Lista com números
lista_numeros = [1, 2, 3, 4, 5]

# Lista com strings
lista_nomes = ["Alice", "Bob", "Charlie"]

# Lista mista
lista_mista = [10, "dez", True, [1, 2, 3]]
```

A lista pode ser impressa como uma variável. Usando o comando `print` ou em ambientes do Jupyter apenas digitando o nome da lista


```python
lista_numeros
```




    [1, 2, 3, 4, 5]




```python
lista_nomes
```




    ['Alice', 'Bob', 'Charlie']



### Acessando Elementos


```python
# Acessando o primeiro elemento (índice 0)
lista_nomes[0]
```




    'Alice'




```python
# Acessando um elemento qualquer da lista
lista_numeros[4]
```




    5




```python
# Acessando o último elemento
lista_nomes[-1]
```




    'Charlie'




```python
# Verificando o tamanho da lista
len(lista_mista)
```




    4



### Modificando Listas


```python
# Alterando um elemento
lista_numeros[2] = 10
```


```python
lista_numeros
```




    [1, 2, 10, 4, 5]




```python
# Adicionando um elemento ao final
lista_nomes.append("Batore")
```


```python
lista_nomes
```




    ['Alice', 'Bob', 'Charlie', 'Batore']




```python
# Removendo um elemento pelo valor
lista_numeros.remove(2)
```


```python
lista_numeros
```




    [1, 10, 4, 5]




```python
# Removendo um elemento pelo valor
lista_nomes.remove("Bob")
```


```python
lista_nomes
```




    ['Alice', 'Charlie', 'Batore']




```python
# Removendo um elemento pela posição
del lista_nomes[1]
```


```python
lista_nomes
```




    ['Alice', 'Batore']



### Operações comuns com listas

#### Concatenando listas


```python
nova_lista = lista_nomes + lista_numeros
nova_lista
```




    ['Alice', 'Batore', 1, 10, 4, 5]



#### Verificando se um elemento está em uma lista


```python
'Alice' in nova_lista
```




    True



#### Obtendo o tamanho da lista


```python
# Len advém de lenght que tem como tradução tamanho ou comprimento.
len(nova_lista) 
```




    6



## Exercícios

1 - Crie uma lista em linguagem python para representar uma lista de compras de supermercado. Dica: utilize letras mínusculas


<!-- ```python

``` -->

2 - Adicione 5 itens à lista. Utilize o método `append()`


<!-- ```python

``` -->

3 - Imprima a lista completa.


<!-- ```python

``` -->

4 - Remova o segundo item da lista


<!-- ```python

``` -->

5 - Delete (apagar) o último item de sua lista


<!-- ```python

``` -->

🗒️ Arquivo sobre <a href="https://github.com/CTInternet/arquivos/tree/main/Algoritmos%20e%20L%C3%B3gica%20de%20Programa%C3%A7%C3%A3o/04%20L%C3%B3gica%20com%20python%20-%20Listas" target="_blank">➡️ Listas em Python ⬅️</a> 🗒️

