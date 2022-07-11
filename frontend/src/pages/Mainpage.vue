<template>
  <section class="container main">
      <Navbar></Navbar>
      <Search></Search>
      <Clubcard v-for = "item in items" :key = "item" :item = "item"></Clubcard>
      <Footer></Footer>
    </section>
</template>

<script>
import Navbar from '../components/Navbar.vue'
import Search from '../components/Search.vue'
import Clubcard from '../components/Clubcard.vue'
import Footer from '../components/Footer.vue'

export default {
  name: 'Mainpage',
  components: {
    Navbar,
    Search,
    Clubcard,
    Footer
  },
  data() {
    return {
      items: [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.main {
    display: flex;
    flex-direction: column;
    align-items: center;
}
</style>
