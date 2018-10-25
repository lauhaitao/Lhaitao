<template>
    <div class="wrap">
      <div class="toubu">
      </div>
      <div class="zuo">
        <img src="/static/img/zuo.png" alt="">
      </div>
      <p class="p1">头像</p>
      <div class="dd">
        <img src="/static/img/gengduo.png" alt="">
      </div>
      <div class="dayuan">
         <div class="tp">
           <img src="/static/img/11.jpg" alt="">
         </div>
      </div>
    </div>
</template>

<script>
    export default {
        name: "Touxiang"
    }
</script>

<style scoped>
  .wrap{
    margin: 0;
    padding: 0;
    width:72rem;
    height: 128rem;
    background-color:rgb(242,242,242) ;
    position: relative;
  }
  .toubu{
    position: absolute;
    border: 1px solid rgb(229,62,66);
    width: 72rem;
    height: 9.6rem;
    background-color: rgb(229,62,66);
  }
  .zuo img{
    position: absolute;
    left:3rem;
    top: 3rem;
    width: 2.3rem;
    height: 3.8rem;
  }
  .p1{
    position: absolute;
    font-size: 3.6rem;
    color: white;
    left: 30rem;
    top: 3rem;
  }
  .dd img{
    position: absolute;
    width: 3.4rem;
    height: 0.9rem;
    top: 5rem;
    left: 65rem;
  }
  .dayuan{
    position: absolute;
    width: 49.8rem;
    height: 49.8rem;
    border: 1px solid rgb(255,255,255);
    border-radius: 50rem;
    background-color: rgb(255,255,255);
    top: 20rem;
    left: 10rem;
  }
  .tp img{
    position: absolute;
    font-size: 3.6rem;
    top: -0.1rem;
    left: 0.1rem;
    width: 49.8rem;
    height: 49.8rem;
    border-radius: 50rem;
  }

</style>
