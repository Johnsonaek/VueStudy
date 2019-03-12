<template>
  <html>
  <body>
  <div class="a">
    <input >
    <button class="btn">
      排列
    </button>
  </div>
  </body>
  </html>
</template>

<script>
    export default {
      name:'quicksort',

    }
</script>

<style >
  html,body{
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .a{
    display: flex;
    align-items: center;
    justify-content: center;
    background: grey;
    height: 100px;
    width: 400px;
  }
  .a input{
    --lineheight:lineheight;
  }
  .a .btn{
    height: var(--lineheight);
    width: calc(var(--lineheight)*2);
  }
</style>
