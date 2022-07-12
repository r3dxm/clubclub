<template>
  <Login></Login>
</template>

<script>
import Login from './pages/Login.vue'

export default {
  name: 'App',
  components: {
    Login
  }
}
</script>
<style>
:root {
    --primary: #835858;
    --background: #FFF0F0;
    --color_dark: #463333;
    --color_light: #EBD4D4;
    --smoother: #f1f1f1;
}
* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    font-family: 'Varela Round', sans-serif;
}
.container {
    margin: 0 auto;
    max-width: 90%;
    min-width: 420px;
    height: 100vh;
}

body {
    background: var(--background);

}

/* _____scroll bar */
::-webkit-scrollbar {
    width: 10px;
}
::-webkit-scrollbar-track {
    background-color: transparent;
    padding: initial 5px;
}
::-webkit-scrollbar-thumb {
    background: var(--primary);
    border-radius: 4em ;
    -webkit-border-radius: 4em ;
    -moz-border-radius: 4em ;
    -ms-border-radius: 4em ;
    -o-border-radius: 4em ;
}
/* ___end of scroll bar */
.container {
    width: 100%;
    padding-right: 15px;
    padding-left: 15px;
    margin-right: auto;
    margin-left: auto;
} 
@media (min-width: 576px) {
    .container {
        width: 540px;
    }
}
@media (min-width: 768px) {
    .container {
        width: 720px;
    }
}
@media (min-width: 992px) {
    .container {
        width: 960px;
    }
}
@media (min-width: 1200px) {
    .container {
        width: 1140px;
    }
}
</style>
