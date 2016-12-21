<template>
  <div  class="container" :class="outerClass">
      <img class="img" :class="imgClass" :src="imgUrl">
  </div>
</template>

<script type="text/babel">

    export default {

        props: {
            imgUrl: {
                type: String,
                default: 'http://i0.hdslb.com/bfs/face/487740f4a60f972162992e4ff79d576bcf51a8bd.jpg'
            },
            outerClass: {
                type: String,
                default: ''
            },
            imgClass: {
                type: String,
                default: ''
            },

        },
    };
</script>

<style scoped>
    .container{
       width: 4.03571429rem;/* 113px */
       height: 4.03571429rem;/* 113px */
       border: 1px solid #ddd;
       border-radius: 50%;
       padding: 3px;
   }
   .img{
       border-radius: 50%;
       width: 100%;
       height: 100%;
   }
</style>
