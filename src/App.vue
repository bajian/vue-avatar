<template>
  <div id="app">
  default avatar:
  <avatar></avatar>
  <hr/>

  use img-url avatar:
  <avatar img-url="http://mhfm3.tel.cdndm5.com/32/31393/20160811232318_130x174_14.jpg"></avatar>
  <hr/>


  use outer-class avatar:
  <avatar 
  outer-class="oc"
  img-url="http://mhfm3.tel.cdndm5.com/32/31393/20160811232318_130x174_14.jpg"></avatar>
  <hr/>


  use img-class avatar:
  <avatar img-class="ic"></avatar>
  <hr/>


  </div>
</template>

<script>
import avatar from './components/avatar'

export default {
  name: 'app',
  components: {
    avatar
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 10px;
}


.oc{
       width: 10.71428571rem !important;/* 300px */
       height: 10.71428571rem !important;/* 300px */
       border: 1px solid blue !important;
       border-radius: 50%;
       padding: 0px !important;
}

.ic{
    filter: grayscale(100%);
    -webkit-filter: grayscale(100%);

    -webkit-animation:anime 1s ; /* Firefox */
    animation:anime 1s ; 
}

@-webkit-keyframes anime
{
  0% {
    width: 0px;
    height: 0px;
  }
  100% {
    width: 100% !important;
    height: 100% !important;
  }
}


@keyframes anime
{
  0% {
    width: 0px;
    height: 0px;
  }
  100% {
    width: 100% !important;
    height: 100% !important;
  }
}

</style>
