## Tuplas

**O que são tuplas?**

Tuplas em Python são sequências imutáveis de elementos. Isso significa que, uma vez criada, uma tupla não pode ser modificada: você não pode adicionar, remover ou alterar elementos individuais. Essa característica as torna ideais para armazenar dados que não devem ser alterados, como coordenadas, datas de nascimento ou informações de um produto.


```python
# Criando uma tupla
tupla1 = ("Geografia", 23, "Elefantes")
```


```python
# Imprimindo a tupla
tupla1
```




    ('Geografia', 23, 'Elefantes')




```python
# Tuplas não suportam append()
tupla1.append("Chocolate")   
```


    ---------------------------------------------------------------------------

    AttributeError                            Traceback (most recent call last)

    <ipython-input-4-cb90e5e5a1a0> in <module>
          1 # Tuplas não suportam append()
    ----> 2 tupla1.append("Chocolate")
    

    AttributeError: 'tuple' object has no attribute 'append'



```python
# Tuplas não suportam delete de um item específico
del tupla1["Gatos"]  
```


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    <ipython-input-5-24facd06bb21> in <module>
          1 # Tuplas não suportam delete de um item específico
    ----> 2 del tupla1["Gatos"]
    

    TypeError: 'tuple' object does not support item deletion



```python
# Tuplas podem ter um único item
tupla1 = ("Chocolate")
```


```python
tupla1
```




    'Chocolate'



**Por que usar tuplas?**

Imutabilidade: Garante que os dados não sejam alterados acidentalmente, evitando erros.
Eficiência: Tuplas são geralmente mais eficientes em termos de memória do que listas, especialmente para dados que não precisam ser modificados.
Chaves em dicionários: Tuplas podem ser usadas como chaves em dicionários, pois são hashable (imutáveis).
Retorno de múltiplos valores: Funções podem retornar múltiplos valores em uma tupla.


```python
tupla1 = ("Geografia", 23, "Elefantes")
```


```python
tupla1[0]
```




    'Geografia'




```python
# Verificando o comprimento da tupla
len(tupla1)
```




    3




```python
# Slicing, da mesma forma que se faz com listas
tupla1[1:]
```




    (23, 'Elefantes')




```python
tupla1.index('Elefantes')
```




    2




```python
# Tuplas não suportam atribuição de item
tupla1[1] = 21
```


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    <ipython-input-13-59bcc25f7f2b> in <module>
          1 # Tuplas não suportam atribuição de item
    ----> 2 tupla1[1] = 21
    

    TypeError: 'tuple' object does not support item assignment



```python
# Deletando a tupla
del tupla1
```


```python
tupla1
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    <ipython-input-15-9c021f243716> in <module>
    ----> 1 tupla1
    

    NameError: name 'tupla1' is not defined



```python
# Criando uma tupla
t2 = ('A', 'B', 'C')
```


```python
t2
```




    ('A', 'B', 'C')




```python
# Tuplas não suportam atribuição de item
t2[0] = 'D'
```


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    <ipython-input-18-f90994f4060e> in <module>
          1 # Tuplas não suportam atribuição de item
    ----> 2 t2[0] = 'D'
    

    TypeError: 'tuple' object does not support item assignment



```python
# Usando a função list() para converter uma tupla para lista
lista_t2 = list(t2)
```


```python
lista_t2
```




    ['A', 'B', 'C']




```python
lista_t2.append('D')
```


```python
# Usando a função tuple() para converter uma lista para tupla
t2 = tuple(lista_t2)
```


```python
t2
```




    ('A', 'B', 'C', 'D')



**Quando usar tuplas?**

Armazenar coordenadas: (x, y, z)
Representar datas: (ano, mês, dia)
Retornar múltiplos valores de uma função: (valor1, valor2, ...)
