<div class="base">
	<div class= 'top'>
   		<div class="pie a"></div>
    	<div class="pie b"></div>
    </div>
	<div class='pie c'></div>
</div>

<style>
  .base {
    transform: translate(-8px, -8px);
    position: absolute;
    width: 400px;
    height: 300px;
    background: #E3516E;
  }
  .top{
    margin-top:50px; 
   	margin-left:92px;
    display:flex
  }
  .a {
    background: #51B5A9;
  }
  .b {
    background: #FADE8B;
    transform:rotate(90deg)
  }
  .c {
   	margin-left:92px;
    background: #F7F3D7;
    transform:rotate(270deg) 
  }
   .pie {
    width: 100px;
    height: 100px;
    border-radius: 120px 0px 0px 0px
  }
</style>
