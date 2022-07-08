<template>
    <section class = "main container">
        <div class="main__card">
            <input type="text" placeholder = "Username">
            <input type="password" placeholder = "Password">
            <button>Login</button>
        </div>
    </section>
</template>

<script>
export default {
    name: 'Login'
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
    width: 50%;
    height: 50%;
    box-shadow: 0 4px 8px 0 black;
    transition: 0.3s;
    background-color: var(--cardbackground);
    border-radius: 25px;
}

.main__card:hover {
    box-shadow: 0 8px 16px 0 black;
}

.main__card input , button{
    text-align: center;
    height: 8%;
    width: 50%;
    margin: 10px;
    width: 50%;
    border-radius: 25px;
    border: none;
    color: var(--text_color);
    outline-width: 0;
}

.main__card button {
    background-color: var(--text_color);
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
