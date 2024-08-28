# cssbattle-play-95

<div class='p'>
  <div class="s r"></div>
  <div class="s w"></div>
  <div class="c1"></div>
  <div class="c2"></div>
</div>
<style>
  body {
    display:flex;
    align-items:center;
    justify-content:center;
    background:#6CB3A9
  }
  .p {
    position:relative;
    width:180px;
    height:180px;
    border-radius:50%;
    background:#000
  }
  .s {
    position:absolute;
    left:-10px;
    top:-10px;
    width:200px;
    height:200px;
    border-radius:50%;
    clip-path:polygon(110px 0%,100% 0%,100% 100%,110px 100%)
  }
  .r {
    background:#D25B70;
    transform:rotate(270deg)
  }
  .w {
    background:#fff;
    transform:rotate(90deg)
  }
  .c1 {
    position:absolute;
    left:55px;
    top:55px;
    border-radius:50%;
    width:70px;
    height:70px;
    background:#000
  }
  .c2 {
    position:absolute;
    left:65px;
    top:65px;
    border-radius:50%;
    width:50px;
    height:50px;
    background:#F6DF96
  }
</style>
