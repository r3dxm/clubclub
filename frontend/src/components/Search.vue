<template>
    <div class="main__search__container">
        <input type="text">
    </div>
</template>

<script>
export default {
    name: 'Search'
}
</script>


<style scoped>

.main__search__container {
    background-color: var(--cardbackground);
    width: 90%;
    margin: 20px;
    border-radius:  5px;
    display: flex;
    justify-content: center;
}
.main__search__container input {
    display: block;
    margin: 20px;
    width: 90%;
    height: 30px;
    border-radius: 5px;
    border: none;
    background-color: white;
    font-size: 1.2em;
    text-align: center;
 }
</style>