<template>
  <section class="container main">
        <Search></Search>
        <Mainclubcard v-for = "item in items" :key = "item" :item = "item"></Mainclubcard>
    </section>
</template>

<script>
import Search from '../components/Search.vue'
import Mainclubcard from '../components/Mainclubcard.vue'

export default {
  name: 'Mainpage',
  components: {
    Search,
    Mainclubcard
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
