<div class="base">
  <div class="container">
    <div class="half-circle"></div>
  </div>
</div>
<style>
  .base {
    width: 400px;
    height: 300px;
    display: flex;
    direction: column;
    justify-content: center;
    align-items: center;
    transform: translate(-8px,-8px);
    background: #6592CF;
  }
  .container {
    display:flex;
    width:110px;
    height:240px;
    background:#6592CF;
    overflow:hidden;
  }
  .half-circle {
    width: 200px;
    height: 100px; /* as the half of the width */
    border-top-left-radius: 100px;
    border-bottom-right-radius: 100px;
    border: 10px solid #243D83;
    border-bottom: 0;
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    box-sizing: border-box;
}

</style>