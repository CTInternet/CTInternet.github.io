# Projeto Super Útil - Seu canivete suiço

O Projeto Super Útil tem como objetivo o desenvolvimento de um site que oferece uma variedade de pequenas ferramentas práticas para o uso cotidiano. Ao longo do desenvolvimento, novos conceitos serão gradualmente introduzidos, promovendo o aprofundamento no aprendizado dos conteúdos da disciplina de Desenvolvimento WEB I.

## Aula 1 : Avançando nos conceitos de CSS

### O que são identificadores CSS 🆔

Os identificadores CSS (também conhecidos como IDs) são seletores usados para aplicar estilos específicos a um único elemento em uma página HTML. Eles são definidos utilizando o caractere "hash" (#) seguido de um nome que você define. O ID é exclusivo dentro do documento HTML, ou seja, cada ID deve ser usado apenas uma vez em uma página, diferentemente das classes, que podem ser aplicadas a múltiplos elementos.

No HTML, o identificador é atribuído a um elemento através do atributo id:

````html
    <h1 id="titulo-principal">Título</h1>

````

No CSS, você faz referência ao identificador usando o símbolo #:

````css

    #titulo-principal {
        color: blue;
        font-size: 24px;
    }

````

#### Características

**Exclusividade**: Cada ID é único dentro de uma página HTML, o que significa que um mesmo identificador não deve ser repetido em diferentes elementos na mesma página.

**Especificidade alta**: IDs têm maior prioridade de estilo em comparação a classes ou seletores de tipo (tags). Isso significa que, em caso de conflito entre regras CSS, o estilo definido para um ID será aplicado, mesmo que outro estilo tenha sido atribuído por uma classe ou tag.

**Aplicação**: IDs são ideais para situações em que um elemento específico precisa de um estilo próprio, mas não são recomendados para a aplicação em vários elementos. Para isso, as classes são mais indicadas.

### Usando fontes externas 🔡🔠

O uso de **fontes externas** no desenvolvimento web permite incorporar tipografias que não estão instaladas no dispositivo do usuário, expandindo as opções além das fontes padrão. Uma das soluções mais populares é o **Google Fonts**, um repositório gratuito com diversas fontes.

#### Como utilizar Google Fonts:

**Escolha da fonte** : Acesse [Google Fonts](https://fonts.google.com) e escolha uma ou mais fontes. Após a escolha selecionar a fonte, o Google Fonts gera uma tag que será utilizada no arquivo CSS

```html
<link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">

```

### Resetar o CSS? 🤔

**Resetar o CSS** significa remover os estilos padrões aplicados pelos navegadores aos elementos HTML. Cada navegador possui uma folha de estilo padrão que define margens, espaçamentos, tamanhos de fonte, entre outros, para os elementos da página. Esses estilos variam entre navegadores, o que pode causar inconsistências no design.

O **reset de CSS** consiste em aplicar uma folha de estilo que redefine esses valores padrão, removendo ou normalizando margens, preenchimentos e outros atributos, para garantir que todos os elementos comecem com estilos neutros e iguais em todos os navegadores.

1. **Consistência** : Garante que o layout e a aparência sejam os mesmos em todos os navegadores.
2. **Controle** : Dá mais controle ao desenvolvedor sobre como os elementos são estilizados, partindo de uma base uniforme.
3. **Personalização** : Facilita a personalização dos estilos, evitando conflitos com os estilos padrão do navegador.

#### Métodos comuns para resetar o CSS:

1. **CSS Reset** : Um conjunto de regras que zera ou remove todos os estilos básicos de um navegador. Um exemplo clássico é o CSS Reset de Eric Meyer.

```css
/* Reset básico */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

```

Arquivo a ser utilizado em sala no início do projeto:
Baixe inicial do <a href="https://github.com/CTInternet/arquivos/blob/main/Desenvolvimento%20WEB%20I/projeto-super-util.zip" target="_blank">Projeto Super Útil</a>