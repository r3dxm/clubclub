<template>
    <section class = "main container">
        <div class="main__card">
            <input type="text" placeholder = "Username">
            <input type = "email" placeholder = "email">
            <input type="password" placeholder = "Password">
            <input type = "password" placeholder = "Confirm password">
            <button>Create account</button>
            <button>I already have an account</button>
            <Footer></Footer>
        </div>
    </section>
</template>

<script>
import Footer from '../components/Footer.vue'

export default {
    name: 'Login',
    components: {
        Footer
    }
}
</script>

<style scoped>
.main {
    display: flex;
    align-items: center;
    justify-content: center;
}

.main__card {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: 70%;
    height: 70%;
    box-shadow: 0 4px 8px 0 black;
    transition: 0.3s;
    background-color: var(--color_light);
    border-radius: 25px;
}

.main__card:hover {
    box-shadow: 0 8px 16px 0 black;
}

.main__card input , button{
    text-align: center;
    height: 7%;
    width: 70%;
    margin: 10px;
    border-radius: 25px;
    border: none;
    color: var(--color_dark);
    outline-width: 0;
}

.main__card button {
    background-color: var(--color_dark);
    color: white;
}

.main__card button:hover{
    box-shadow: 0 4px 8px 0 black;
    transition: 0.3s;
}

.main__card button:active {
    background-color: grey;
}
</style>