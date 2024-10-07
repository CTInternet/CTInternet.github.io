## Dicionários

**Dicionários**

Em Python, dicionários são estruturas de dados que armazenam pares chave-valor. Imagine um dicionário físico: você encontra uma palavra (a chave) e, ao lado dela, seu significado (o valor). Em Python, funciona de forma similar, mas de forma muito mais versátil.

Características:

**Não ordenados** Diferentemente de listas, os itens em um dicionário não possuem uma ordem específica.

**Mutáveis** Você pode adicionar, remover ou modificar elementos após a criação do dicionário.
Chaves únicas: 

Cada chave em um dicionário deve ser única e imutável (como strings ou números).
Valores diversos: Os valores podem ser de qualquer tipo de dado, inclusive outros dicionários, listas ou até mesmo funções.


```python
# Isso é uma lista
estudantes_lst = ["Mateus", 24, "Fernanda", 22, "Tamires", 26, "Cristiano", 25]   
```


```python
estudantes_lst
```




    ['Mateus', 24, 'Fernanda', 22, 'Tamires', 26, 'Cristiano', 25]




```python
# Isso é um dicionário
estudantes_dict = {"Mateus":24, "Fernanda":22, "Tamires":26, "Cristiano":25}
```


```python
estudantes_dict 
```




    {'Mateus': 24, 'Fernanda': 22, 'Tamires': 26, 'Cristiano': 25}




```python
estudantes_dict["Mateus"]
```




    24




```python
estudantes_dict["Pedro"] = 23
```


```python
estudantes_dict["Pedro"]
```




    23




```python
estudantes_dict["Tamires"]
```




    26




```python
estudantes_dict.clear()
```


```python
estudantes_dict
```




    {}




```python
del estudantes_dict
```


```python
estudantes_dict
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    Cell In[57], line 1
    ----> 1 estudantes_dict
    

    NameError: name 'estudantes_dict' is not defined



```python
estudantes = {"Mateus":24, "Fernanda":22, "Tamires":26, "Cristiano":25}
```


```python
estudantes
```




    {'Mateus': 24, 'Fernanda': 22, 'Tamires': 26, 'Cristiano': 25}




```python
len(estudantes)
```




    4




```python
estudantes.keys()
```




    dict_keys(['Mateus', 'Fernanda', 'Tamires', 'Cristiano'])




```python
estudantes.values()
```




    dict_values([24, 22, 26, 25])




```python
estudantes.items()
```




    dict_items([('Mateus', 24), ('Fernanda', 22), ('Tamires', 26), ('Cristiano', 25)])




```python
estudantes2 = {"Maria":27, "Erika":28, "Milton":26}
```


```python
estudantes2
```




    {'Maria': 27, 'Erika': 28, 'Milton': 26}




```python
estudantes.update(estudantes2)
```


```python
estudantes
```




    {'Mateus': 24,
     'Fernanda': 22,
     'Tamires': 26,
     'Cristiano': 25,
     'Maria': 27,
     'Erika': 28,
     'Milton': 26}




```python
estudantes["Mateus"]
```




    24


