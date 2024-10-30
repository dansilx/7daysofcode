O escopo do projeto é o seguinte: uma empresa de TI quer desenvolver uma página destinada a novas contratações e contratou você para desenvolvê-la.

Para isso, te enviaram um layout no Figma. O Figma é um software que muitos designers utilizam para criar protótipos. E a partir desse protótipo que eu vou disponibilizar, você vai transformá-lo em código e dar vida real ao projeto! Beleza?

https://www.figma.com/design/mm3MLozvUDGhDRTxSLlGL5/7daysOfCode-HTML-CSS?node-id=0-1&node-type=canvas

O desafio de hoje é desenvolver a primeira seção da sua página, que também pode ser chamada de "cabeçalho":

Para textos genéricos, recomenda-se o uso da tag <span>. Já para títulos, existem as tags relacionadas a títulos, que vão do <h1> até o <h6>. E por fim, existe um parágrafo nesta estrutura, para o qual você pode usar a tag <p>.

Você também vai perceber que terá que utilizar muitas cores parecidas nesse projeto, como por exemplo o uso do vermelho. Nesse caso, eu recomendo fortemente você criar uma variável no CSS para armazenar essa cor e referenciá-la toda vez que for utilizá-la. Veja o código abaixo:

:root {
  --text-color: #667085;
  --main-color: #8E2424;
}

E agora, para utilizar essa variável, basta chamar:

color: var(--text-color);