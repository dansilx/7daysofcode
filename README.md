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

hoje você vai desenvolver uma parte bem legal e desafiadora: a seção de métricas e resultados da sua página. Ela é uma seção muito comum na maioria das landing pages que vemos por aí hoje em dia.

A empresa que te contratou pediu para você incluir 4 métricas diferentes, com um título, um subtítulo e um texto:

Veja que as métricas estão uma do lado da outra. Para chegar a esse resultado, sua estrutura do HTML pode seguir esse raciocínio:

<section class="metricas-container">
        <div>primeira métrica aqui..</div>
        <div>segunda métrica aqui..</div>
        <div>terceira métrica aqui..</div>
        <div>quarta métrica aqui..</div>
</section>

A tag <section> é uma tag semântica do HTML. Em termos de efeitos visuais, ela não difere em nada da <div>. Porém, a <div> é mais genérica, enquanto que a <section> passa mais esse significado de que aquilo é uma seção da sua página.

Para separar as métricas em 4 partes, você poderá utilizar o CSS Grid, ou até mesmo o Flexbox, você decide!

O que você vai fazer hoje é a seção de "Estamos procurando por talentos", mas sem a parte de divulgação de vagas ainda, apenas até a imagem!

Você pode exportar essa imagem das pessoas na sala de reunião diretamente daquele arquivo lá do Figma (para acessar esse arquivo é só clicar aqui). Daí, você pode criar uma pasta dentro do seu projeto para colocar a imagem e utilizar a tag:

<img src=""/>

no código, referenciando-a.

É sempre uma boa prática no CSS utilizar medidas responsivas como o rem, em, %, entre outras. Por isso, eu vou deixar um link aqui de um artigo muito completo da Alura, que fala exatamente sobre isso!