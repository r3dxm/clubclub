<template>
  <Privateprofile></Privateprofile>
</template>

<script>
import Privateprofile from './pages/Privateprofile.vue'

export default {
  name: 'App',
  components: {
    Privateprofile
  }
}
</script>
<style>
:root {
    --main_background: #e0d6c3;
    --cardbackground: #B4977B;
    --text_color: #563A3D;
}

* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    font-family: sans-serif;
}
.container {
    margin: 0 auto;
    max-width: 90%;
    min-width: 420px;
    height: 100vh;
}

body {
    background: var(--main_background);

}
</style>
