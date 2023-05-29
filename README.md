# Projeto-jogodavelha-juju
![O venceu](https://github.com/marcosaureliosl/Projeto-jogodavelha-juju/assets/127764997/09d38119-def3-4f26-8528-6a305d76fca6)

## Responsivo
![responsivo](https://github.com/marcosaureliosl/Projeto-jogodavelha-juju/assets/127764997/c33b8d18-54d2-4d37-b0dd-fc8aa7c55301)


![x venceu](https://github.com/marcosaureliosl/Projeto-jogodavelha-juju/assets/127764997/7ce1fb90-3a6b-442d-9586-0ce2f8ae1cc4)

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

