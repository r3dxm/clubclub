<template>
    <div class="search">
        <div class="search__box">
            <form>
                <input class="search__input" type="text" placeholder="filter clubs" />
            </form>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Search'
}
</script>


<style scoped>
.search__main form {
    display: flex;
    justify-content: center;
}
.search__input {
    width: 72vw;
    padding: 10px;
    border-radius: 3px  ;
    outline: none;
    border: none;
    margin-top: 30px;
    background-color: var(--color_light);
    color: var(--color_dark);
    font-weight: 600;
}
.search__input::placeholder {
    color: var(--primary);
    font-weight: 600;
}
</style>