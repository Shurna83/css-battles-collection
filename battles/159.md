# Battle n.26 - Target n.159 - Portal

[Here's the challenge](https://cssbattle.dev/play/159)

Just a grid.

```html
<div class="grid">
  <div></div>
  <div></div>
  <div class="red"></div>
  <div></div>
  <div></div>

  <div></div>
  <div class="red"></div>
  <div class="red"></div>
  <div class="red"></div>
  <div></div>

  <div class="red"></div>
  <div class="red"></div>
  <div class="red"></div>
  <div class="red"></div>
  <div class="red"></div>

  <div></div>
  <div class="red"></div>
  <div class="red"></div>
  <div class="red"></div>
  <div></div>

  <div></div>
  <div></div>
  <div class="red"></div>
  <div></div>
  <div></div>

  <div class="red"></div>
  <div class="red"></div>
  <div class="red"></div>
  <div class="red"></div>
  <div class="red"></div>
</div>
<style>
  body {
    background: #F5D6B4;
    height: 100%;
    margin: 0;
    display: flex;
    place-content: center;
    place-items: center;
  }
  .grid {
    display: grid;
    grid-template: repeat(5, 50px) / repeat(5, 50px);
  }
  .red {
    background: #D86F45;
  }
</style>
```
