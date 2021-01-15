
<div class="base">
  <div class="banner"></div>
  <div class="square">
    <div class="inner">
    	<div class="circle"></div>
    </div>
  </div>
</div>

<style>
  .base {
    display: flex;
    justify-content: center;
  	align-items: center;
    width: 400px;
    height: 300px;
    background: #222730;
  }
  .square {
    transform: rotate(45deg);
    position: absolute;
    width: 250px;
    height: 250px;
    background: #222730;
  }
  .inner {
    transform: translate(50px, 50px);
    width: 150px;
    height: 150px;
    background: #4CAAB3;
  }
  .circle {
  	transform: translate(50px, 50px);
    width: 50px;
    height: 50px;
    background:#393E46;
    border-radius: 50%;
  }
  .banner {
    display: flex;
    justify-content: center;
    background: #4CAAB3;
    width: 100%;
    height:150px;
  }
</style>