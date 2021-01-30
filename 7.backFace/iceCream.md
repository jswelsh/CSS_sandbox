![Ice Cream](https://cssbattle.dev/targets/35.png)

<div class="base">
  <div class="ice">
    <div class="stick"></div>
  </div>
</div>
<style>
  .base {
    width: 400px;
    height: 300px;
    display:flex;
    flex-direction: column;
    justify-content:space-evenly;
    align-items: center;
    transform: translate(-8px, -8px);
    background: #293462;
  }
  .ice {
    display:flex;
    justify-content:center;
    width:100px;
    height:150px;
    transform: translate(0px, -25px);
    border-radius: 75px 75px 30px 30px;
    background: #FFF1C1;
  }
  .stick {
    align-self:flex-end;
    width:30px;
    height:40px;
    background:#FE5F55;
    transform: translate(0px, 50px);
    border-radius: 0px 0px 10px 10px;
    box-shadow: 0px -10px  #A64942;
  }
</style>