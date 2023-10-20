# Battle n.25 - Target n.153 - Checkers

[Here's the challenge](https://cssbattle.dev/play/153)

Played a bit with `:after`.

```html
<body bgcolor=#E3516E>
<div class="wrap">
  <div class="yellow"></div>
  <div class="dot"></div>
  <div class="yellow"></div>
  <div class="dot"></div>
  <div class="yellow"></div>

  <div class="dot"></div>
  <div class="yellow"></div>
  <div class="dot"></div>
  <div class="yellow"></div>
  <div class="dot"></div>

  <div class="yellow"></div>
  <div></div>
  <div class="yellow"></div>
  <div></div>
  <div class="yellow"></div>

  <div class="dot"></div>
  <div class="yellow"></div>
  <div class="dot"></div>
  <div class="yellow"></div>
  <div class="dot"></div>

  <div class="yellow"></div>
  <div class="dot"></div>
  <div class="yellow"></div>
  <div class="dot"></div>
  <div class="yellow"></div>
</div>
<style>
  :root {
    --cell: 40px;
  }
  .wrap {
    width: 100%;
    height: 100%;
    display: grid;
    grid-template-columns: repeat(5, var(--cell));
    place-content: center;
  }
  .yellow {
    aspect-ratio: 1;
    background: #FADE8B;
  }
  .dot {
    width: var(--cell);
    aspect-ratio: 1;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .dot:after {
    content: "";
    width: 20px;
    aspect-ratio: 1;
    background: #FADE8B;
    border-radius: 50%
  }
</style>

```
