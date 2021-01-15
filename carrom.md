![Carom](https://cssbattle.dev/targets/2.png)
<div class="base">
  <div class="top">
    <div class="square left"></div>
    <div class="square right"></div>
  </div>
  <div class="bottom">
    <div class="square left"></div>
    <div class="square right"></div>
  </div>
</div>
<style>
  .base {
    transform: translate(-8px, -8px);
    position: absolute;
    width: 400px;
    height: 300px;
    background: #62374e;
  }
  .square {
    width: 50px;
    height: 50px;
    background: #fdc57b;
  }
  .top {
    display:flex;
    transform: translate(0, 100%);
  }
  .bottom {
    display:flex;
    transform: translate(0, 300%);
  }
  .left {
    transform: translate(100%);
  }
  .right {
    transform: translate(500%);
  }
</style>
