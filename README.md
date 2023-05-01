# hello-world
=============

Hi Humans!

Hubot here, I like Nods.js and Coffeescript(that's what I'm made of!).
I've had tacos on the moon and find then far superior to Earth tacos.



# Introdução 

## O que significa CSS?

* cascading Style Seet;
* Código para criar estilo no HTML;
* html é a estrutura, e o CSS a beleza;
* Não é uma linguagem de programação;
* É uma linguagem style sheet;

## Vamos ao exemplo


> h1 {
>    color: blue;
> }



# Comentários

* Não irá afetaro o seu código
* Ajuda a lembrar blocos de códigos
* Deixa dicas para leitura
* Ajuda outros a entenderem
* Numca esqueça de fechar um comentário aberto

Comentários começam com `/*` e terminam `*/`


```css

/**Básico */
/* ---------------------------------------------- */

body {
    font: 1em/150% Helvetica, Arial, sans-serif;
    padding: 1em;
    margin: 0 auto;
    max-width: 33em;
}

@media (min-witdh: 70em) {
    /** Let's especial case the global font size. On large screen or window, we increase the font size for better readability */
    body {
        font-size: 130%;
    }
}

h1 {font-size: 1.5em;}
/* Elementos específicos */
/* ---------------------------------------------- */
div p, #id:first-line {
    background-color: red;
    border-radius: 3px;
}
div p {
    margin: 0;
    padding: 1em
}
