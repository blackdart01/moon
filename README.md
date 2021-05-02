# moon
moon html css pattern

code******

<div></div>
<style>
  body
  {
    background: #F3AC3C;
  }
  div {
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-50%);
    width: 100px;
    height: 100px;
    border-radius:100px;
    background: #1A4341;
  }
   div::after {
    content:'';
    position:absolute;
    top:0%;
    left:0%;
    transform:translate(-50%,-50%);
    width: 200;
    height: 200;
    border-radius:100px;
    background: #F3aC3C;
    box-shadow:200px 0px #F3AC3C,200px 200px #F3AC3C,00px 200px #F3AC3C; 
  }
</style>

