# Boas vindas ao repositório do projeto de CSS Responsivo!

# Sumário

- [O que vamos aprender?](#-o-que-vamos-aprender)
- [Você será capaz de](#voce-sera-capaz-de)
- [Porque isso é importante?](#porque-isso-e-importante)
- [Conteúdos](#conteudos)
  - [Unidades absolutas e relativas](#unidade-absolutas-e-relativas)
    - [Introdução](#introducao-grid)
    - [Mão na massa](#mao-na-massa-grid)
  - [CSS Grid](#css-grid)
    - [Introdução](#introducao-grid)
    - [Mão na massa](#mao-na-massa-grid)
- [Vamos praticar!](#vamos-praticar)
- [Recursos Adicionais](#recursos-adicionais)

* * *

## O que vamos aprender?

Nesse projeto iremos desenvolver a capacidade de construir layouts utilizando a ténica que é disponibilizada através do modo de grade(grid), aprender sobre posicionamentos, e com a utilização das media queries para criarmos layouts que sejam complexos porém com facilidade e consistência entre os navegadores.

Siga as instruções indicadas nos arquivos junto com o material de referência para entendimento do conteúdo.

### Antes de começar a desenvolver:

Você possui duas opções: 
- Realizar um clone do repositório e realizar um `push`.
- Realizar um `fork` deste repositório. (Caso queira consigo acompanhar mais facilmente caso tenha alguma dificuldade.)

* * *

### Você será capaz de:

- Utilizar unidades corretas e fluidas para facilitar layouts responsivos.
- Utilizar técnica mobile-first.
- Utilizar `CSS Grid` para realizar layouts complexos.
- Utilizar a propriedade e entender `position` com `absolute` e `relative`.
- Utilizar media queries para se adaptar com dispositivos gerais.
- Utilizar o devtools como complemento para estilizar o layout.

* * *

## Conteudos

Vamos nos aprofundar na mágia do CSS \o/.
É muito importante praticar cada tópico para entendimento pois a junção de todos garante a melhor flexibilidade para o CSS responsivo acontecer.

### Unidades absolutas e relativas

Você já deve ter percebido que no desenvolvimento web, trabalhamos com bastante unidade de medidas. O príncipio na responsividade é trabalharmos com unidades relativas, pois elas oferecem melhor flexibilidade para construir nosso layout. Mas vamos entender cada uma que podemos utilizar em nossa aplicação.

#### Unidades absolutas

> cm, mm, Q, in, pc, pt, px

Unidades absolutas não mudam pois não são relativas ao qualquer elemento pré-definido, e sempre serão o mesmo tamanho ao qual foi definido. A opção mais comum será a unidade `px`.

#### Unidades relativas

> em, ex, ch, rem, lh, vw, vh, vmin, vmax

Unidades relativas dependem de algo pré-definido, seja um elemento pai ou largura/altura disponível do dispositivo que a aplicação está sendo utilizada. 
Iremos nos aprofundar sobre `em`, `rem`, `vw` e `vh`.

#### Introdução <a id="introducao-medidas"></a>

Medidas responsivas são nada

### CSS Grid

#### Introdução <a id="introducao-grid"></a>

Antigamente um dos maiores desafios relacionado ao desenvolvimento web se tratava na construção de layouts, conforme o tempo foi avançado várias abordagens (~~hoje isso se chama gambiarra~~) foram sendo utilizadas, tendo métodos desde da utilização com [tabelas](hhttps://www.tutorialrepublic.com/codelab.php?topic=html&file=table-layout), [floats](https://www.tutorialrepublic.com/codelab.php?topic=html5&file=semantic-website-layout), com a propriedade `position` e `display block`, `inline-block` e assim por diante. 
Agora imagine o trabalho não só para construir mas para quando quisesse fazer alguma alteração no layout, a responsabilidade poderia estar no elemento HTML ou divido em várias seções no CSS, com isso tudo foi gerado a grande fama de dificuldade que se tem como trabalhar com CSS.

<div align="center">

[<img src="./assets/meme-css-center.jpg" width="500"/>](assets/meme-css-center.jpg 'Meme CSS')

</div>

Mas queremos aqui, que você venha dar uma chance para nossas aplicações estarem bonitas (~~e com isso você não perder nenhum fio de cabelo~~). 
Hoje em dia já possuímos o método de layout através [flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/), que foi um divisor na web em relação aos métodos passados com criação de layout, mas algo em relação a diferença do grid está no seguinte fator:
- Flexbox: **Unidirecional**, *tratamos somente um eixo, somente horizontal ou vertical, ele é baseado no conteúdo dos itens* (a definição do tamanho do item, é definido no próprio item)
- Grid: **Bidrecional**, *conseguimos tratar os dois eixos horizontal e vertical, ele é baseado na definição do container* (a definição do tamanho dos itens, é feito no elemento pai)

> [Exemplo sobre a explicação acima](https://x-team.com/blog/css-grid-vs-flexbox/)

Caso tenha dúvida, lembre-se:
- Quero tratar somente linha ou coluna: Utilize `display: flex`
- Quero controlar linha e coluna: Utilize `display: grid` 

Nada te impede de utilzar o grid caso queira tratar somente linha ou coluna (_priorize sempre em simplificar seu código_ :)), mas o conteúdo abordado será focado exclusivamente na utilização do `display: grid`

#### Mão na massa! <a id="mao-na-massa-grid"></a>

### Referências

- [CSS values and units](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Values_and_units)

- [CSS Grid - Responsive Trash Course](https://www.youtube.com/watch?v=SPFDLHNm5KQ)
- [Desvendando o CSS Grid na prática | Mayk Brito](https://www.youtube.com/watch?v=HN1UjzRSdBk)
- [Responsividade na Prática | Masterclass #08](https://www.youtube.com/watch?v=H91DhKPjhPk)
- [The FR unit — Fractional units in CSS grid](https://www.youtube.com/watch?v=Dp7kOWhAjuo)
- [Media Queries e Breakpoints: o Básico e Fundamental](https://www.youtube.com/watch?v=gYak6y7rbRw)
- [Entendendo sobre position no CSS](https://www.youtube.com/watch?v=Y7NeqpwLM2g)
- [CSS Grid Layout e Flexbox - Quando Utilizar](https://www.youtube.com/watch?v=x-4z_u8LcGc&)
- [A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [Layout com tabela e float](https://www.tutorialrepublic.com/html-tutorial/html-layout.php)
- [CSS Grid vs Flexbox](https://x-team.com/blog/css-grid-vs-flexbox/)