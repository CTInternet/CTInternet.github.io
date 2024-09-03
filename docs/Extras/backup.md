CSS (Cascading Style Sheets) é uma linguagem usada para descrever a aparência e o layout de uma página web. 

``background-color: rgb(117, 213, 112);``

O que faz: Define a cor de fundo do ``<div>``.
Detalhe: Usamos o formato rgb, que significa "Red, Green, Blue" (Vermelho, Verde, Azul). Os números (117, 213, 112) são as intensidades dessas cores. Essa cor específica será um tom de verde.


``padding: 20px;``

O que faz: Cria um espaço interno ao redor do conteúdo dentro do ``<div>``
Detalhe: Imagine que o conteúdo do ``<div>`` está em uma caixa; padding é o espaço entre o conteúdo e a borda da caixa. Aqui, estamos definindo um espaço de 20 pixels em todas as direções.


``border-radius: 8px;``

O que faz: Arredonda os cantos do ``<div>``.
Detalhe: Em vez de cantos retos, esse código faz com que os cantos da caixa sejam suavemente arredondados.


``max-width: 600px;``

O que faz: Limita a largura máxima do ``<div>`` a 600 pixels.
Detalhe: Isso significa que, mesmo que a tela seja maior, o ``<div>`` não ficará maior que 600 pixels. Se a tela for menor, o ``<div>`` se ajusta para caber.


``margin: auto;``

O que faz: Centraliza o ``<div>`` na tela.
Detalhe: auto ajusta automaticamente as margens esquerda e direita para que o ``<div>`` fique centralizado.

O resultado deverá ser semelhante a este:

![Alison](img/alison_page2.png)
```css
        div {
            background-color: rgb(117, 213, 112);
            padding: 20px;
            border-radius: 8px;
            max-width: 600px;
            margin: auto;
        }
```