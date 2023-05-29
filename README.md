
## Esse projeto fiz em especial para minha filhinha que amo!!! Por que ela adora jogar esse jogo da velha !!! foi legal criar algo para ela brincar. 

## O que é o projeto!

Jogo da velha

Ferramentas
Origem: Wikipédia, a enciclopédia livre.

Imagem animada de um jogo em que o xis (X) ganha.
O jogo da velha (português brasileiro) ou jogo do galo (português europeu) ou três em linha é um jogo e/ou passatempo popular. É um jogo de regras extremamente simples, que não traz grandes dificuldades para seus jogadores e é facilmente aprendido. A origem é desconhecida, com indicações de que pode ter começado no antigo Egito, onde foram encontrados tabuleiros esculpidos na rocha, que teriam mais de 3.500 anos.[1] De alguma forma, é um jogo "aparentado" dos "Merels" (ver Marel).

Algumas lendas urbanas contam que o jogo terá nascido em Portugal, na cidade de Almada no ano 545. No entanto, só foi popularizado no ano 1500, pelo descobridor Pedro Álvares Cabral, que adorava jogar este jogo durante as suas viagens. Álvares Cabral terá decidido que este jogo seria o primeiro a ser ensinado ao povo indígena no Brasil.
 
 ### fonte
 Visite o site em <https://pt.wikipedia.org/wiki/Jogo_da_velha>.

## Projeto-jogodavelha-juju
![O venceu](https://github.com/marcosaureliosl/Projeto-jogodavelha-juju/assets/127764997/09d38119-def3-4f26-8528-6a305d76fca6)

## Responsivo
![responsivo](https://github.com/marcosaureliosl/Projeto-jogodavelha-juju/assets/127764997/c33b8d18-54d2-4d37-b0dd-fc8aa7c55301)



## Acesse Meu localhost


[Clique aqui](https://marcosaureliosl.github.io/Projeto-jogodavelha-juju/) para visualizar o Projeto.



### Built with

- HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Javascript

### What I learned


To see how you can add code snippets, see below:

```html
<h1> essa aprte de usar a data- no html </h1>
 <div class="winning-message" data-winning-message>
        <P class="winning-message-text" data-winning-message-text >Parabéns,você venceu! </P>
        <button class="winning-message-button" data-restart-button >Reiniciar!</button>
    </div>
```
```css
.cell:nth-child(1),
.cell:nth-child(2),
.cell:nth-child(3) {
    border-top: none;
}
.cell:nth-child(1),
.cell:nth-child(4),
.cell:nth-child(7) {
    border-left: none;
}
.cell:nth-child(7),
.cell:nth-child(8),
.cell:nth-child(9) {
    border-bottom: none;
}

.cell:nth-child(3),
.cell:nth-child(6),
.cell:nth-child(9) {
    border-right: none;
}
/* x */
.cell.x::before,
.cell.x::after,
.board.x .cell:not(.x):not(.circle):hover::after, 
.board.x .cell:not(.x):not(.circle):hover::before {
```
```js
const startGame = () => {
  isCircleTurn = false;

  for (const cell of cellElements) {
    cell.classList.remove("circle");
    cell.classList.remove("x");
    cell.removeEventListener("click", handleClick);
    cell.addEventListener("click", handleClick, { once: true });
  }
}
```

## Minhas dificuldades e aprendizados

Maior dificuldade foi na questao do JavaScript, a logica foi bem complexa para mim, e no Css tive uma pequena dificuldade em motar o X.

O aprendizado maior foi no JavaScript, ainda com um pouco de dificuldade de enteder a logíca, mais a cada porjeto feito a um aprendizado sendo adquirido.

## Agradecimentos 


Agradecer a todos que sempre estão contribuindo, com ideias e sugestões, e estao sempre me acompanhando nesta jornada

## Meus contatos


Você pode saber mais sobre mim e entrar em contato através do meu site pessoal: [Linkendin](https://www.linkedin.com/in/marcosaureliosl/).

Fique à vontade para entrar em contato comigo através do Twitter: [@MarcosA168484](https://twitter.com/MarcosA168484).



