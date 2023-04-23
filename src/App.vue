<template>
  <Qrcode/>
</template>

<script>
import Qrcode from './components/Qrcode.vue';

export default {
  name: 'App',
  components: { Qrcode },
}
</script>
<style>
  body{
    padding: 0;
    margin: 0;
    background-color: hsl(212, 45%, 89%);
  }

  #app{
    widows: 100vw;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
  }
</style>