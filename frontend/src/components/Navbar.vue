<template>
    <header>
        <div class="logo">
            <a href="">
                <img :src = "require('@/assets/logo.png')" alt="..." />
            </a>
        </div>
        <nav>
            <a href="" class="avatar">
                <img width = "40" :src = "require('@/assets/avatar.png')"  alt="...">
            </a>
        </nav>
    </header>
</template>

<script>
export default {
    name: 'Navbar'
}
</script>

<style scoped>
header {
    padding: 10px  30px;
    display: flex;
    justify-content: space-between;
    position: sticky;
    background-color: var(--background);
    z-index: 100;
    top: 0;
    box-shadow: 0px 5px 8px -9px rgba(0,0,0,0.75);
    width: 99vw;
}
.logo img {
    width: 50px;
}
header a {
    text-decoration: none;
    text-transform: capitalize;
    font-size: 1.1rem;
    color: var(--primary);
}
header nav {
    display: flex;
    align-items: center;
}
.avatar img {
    border-radius: 4em;
    border: 3px solid var(--primary);
    -webkit-border-radius: 4em;
    -moz-border-radius: 4em;
    -ms-border-radius: 4em;
    -o-border-radius: 4em;
}
</style>
