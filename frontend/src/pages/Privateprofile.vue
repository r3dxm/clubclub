<template>
    <section class = "container main">
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

        <Profileclubcard v-for = "item in 10" :key = "item"></Profileclubcard>
    </section>
</template>

<script>
import Search from '../components/Search.vue'
import Profileclubcard from '../components/Profileclubcard.vue'

export default {
    name: 'Privateprofile',
    components: {
        Search,
        Profileclubcard
    }
}
</script>

<style scoped>
.main {
    display: flex;
    flex-direction: column;
    align-items: center;
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
