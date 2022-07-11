<template>
    <section class = "container main">

        <Navbar></Navbar>

        <div class="main__header__container">
            <div class="header__top">
                <h3>A person</h3>
                <h5>Clubs</h5>
                <h5>Friends</h5>
            </div>
            <div class="header__bottom">
                <h3>@uniqueusername</h3>
                <h5>5</h5>
                <h5>142</h5>
            </div>
        </div>

        <Search></Search>

        <Clubcard v-for = "item in 10" :key = "item"></Clubcard>

        <Footer></Footer>
    </section>
</template>

<script>
import Navbar from '../components/Navbar.vue'
import Search from '../components/Search.vue'
import Clubcard from '../components/Clubcard.vue'
import Footer from '../components/Footer.vue'

export default {
    name: 'Privateprofile',
    components: {
        Navbar,
        Search,
        Clubcard,
        Footer
    }
}
</script>

<style scoped>
.main {
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 100%;
}

.main__header__container {
    display: flex;
    flex-direction: column;
    width: 100%;
    padding: 40px;
}

.header__top, .header__bottom {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
}
</style>
