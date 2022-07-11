<template>
    <footer>
        <div class="logo">
            <a href="">
                <img :src = "require('@/assets/logo.png')" alt="..." />
            </a>
        </div>
        <div class="link_box">
            <a href="">Privacy Policy</a>
            <a href="">Terms and Conditions</a>
            <a href="">Help</a>
        </div>
        <p>blah &copy; blahclub.com</p>
    </footer>
</template>

<script>
export default {
    name: 'footer'
}
</script>

<style scoped>
footer {
    display: flex;
    flex-direction: column;

    align-items: center;
    margin: 20px 0;
}

footer .link_box {
    margin: 10px 0;
    text-align: center;
}
footer .link_box a {
    text-decoration: none;
    color: var(--primary);
    margin:  10px;
    font-weight: 600;
}
footer p {
    color: var(--primary);

}
</style>