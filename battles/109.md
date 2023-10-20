# Battle n.19 - Target n.109 - Curtain

[Here's the challenge](https://cssbattle.dev/play/109)

Just a grid.

```html
<div g>
  <div c></div>
  <div c></div>
  <div c></div>
  <div c></div>

  <div c></div>
  <div c></div>
  <div c></div>
  <div></div>

  <div c></div>
  <div c></div>
  <div></div>
  <div></div>

  <div c></div>
  <div></div>
  <div></div>
  <div></div>
</div>
<style>
  body {
    background: #191919;
    height: 100%;
    margin: 20;
  }

  [g] {
    
    display: grid;
    grid-template: repeat(4, 40px) / repeat(4, 40px);
    gap: 20px;
  }

  [c] {
    background: #F6E59C;
    border-radius: 50%
  }
</style>
```
