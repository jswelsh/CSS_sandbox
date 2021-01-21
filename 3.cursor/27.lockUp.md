<div class="base">
  <div class="circle">
  	<div class="bar top"></div>
  	<div class="bar btm"> </div>
  </div>
<style>
  .base {
    display:flex;
    justify-content:center;
    align-items:center;
    width: 400px;
    height: 300px;
    transform: translate(-8px,-8px);
    background: #E38F66;
  }
  .bar {
    width:40px;
    height:40px;
    border-radius: 0px 80px 0px 0px;
    border: solid #F7EC7D 30px;
    border-bottom: transparent;
    border-left:transparent;
  }
  .top {
    align-self:flex-end;
    transform: translate(-30px,30px);
  }
  .btm {
    transform: rotate(180deg) translate(-30px,-30px);
  }
  .circle {
    display:flex;
    flex-direction:column;
    width:200px;
    height:200px;
    border-radius: 50%;
    background:#AA445F;
  }
</style>