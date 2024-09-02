#Introdução ao HTML
___

### Aula 1

<div align="center">
<h1>Introdução à construção de páginas web</h1>
</div>
###  
19/08/2024


Instruções:

1. Acesse o site  e veja a matéria <a href="https://www.esportelandia.com.br/olimpiadas/melhores-atletas-brasileiros-da-atualidade/" target="_blank">esportelandia.com</a> **42 melhores atletas brasileiros da atualidade**.
2. Escolha um entre os 42 que estão na lista e crie uma página web com informações sobre atleta escolhido. 
3. Após a escolha, crie um projeto web novo no __vscode__. A página deverá conter os seguintes elementos:
   - Um título h1 com o nome do atleta homenageado
   - Uma imagem do atleta escolhido (usar imagem do site do item 1)
   - As seguintes informações;
     - Nome completo do atleta;
     - Cidade de Nascimento;
     - Esporte do Atleta;
     - Data de nascimento;
     - Idade atual;
     - Informações que considerar relevante sobre sua prática esportiva. Ex. medalhista, campeonatos, recordes.
     - Fatos que considerar relevante.

**Um exemplo será demonstrado em sala! 😊.**


Nesta aula usaremos vamos utilizar estrear as seguintes tags:

````
  <strong> Realce semântico </strong> 
  <ul> lista não ordenada </ul>
  <li> lista de item </li>
````
Boa prática 💪

___
### Aula 2

<div align="center">
<h1>Introdução à construção de páginas web - parte 2</h1>
</div>
26/08/2024

Checkout ⚠️
- Terminar de inserir as informações sobre o atleta na página;

Instruções:

1. Concluir a página anterior inserindo as informações básicas sobre o atleta escolhido;
   caso já tenha concluído esta etapa, escolha um novo atleta e use a tag ``div``para englobar todo o conteúdo do texto que irá inserir.
2. Observe com atenção a demonstração de como o CSS funciona e seus tipos:
   Existem três tipos de CSS diferentes: ==inline, interno e externo==: 

- CSS inline: Serve para dar estilo a um elemento HTML específico. 
    
- CSS interno: Requer que você adicione a tag ``<style>`` no seu documento HTML, sendo efetivo para dar estilo a uma única página. 
    
- CSS externo: Opera linkando suas páginas a um arquivo .css externo.
3.  Aprenda a usar a quebra de linha no ``vscode``

Arquivo de código fonte a ser construído em sala:

````
<style>

        body{
            font-family: Arial;
            background-color: aliceblue
        }

        h1{
            text-align: center;
            color: rgb(79, 42, 165);
        }

        h2 {
            text-align: left;
            color: rgb(79, 42, 165);
        }

        p {
            text-wrap: balance;
        }


        img {
            display: block;
            margin-left: auto;
            margin-right: auto;
        }

        </style>
````

Boa prática 💪


