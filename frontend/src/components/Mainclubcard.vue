<template>
    <div class="main__card__container">

            <div class="main__card">
                <h3>club name {{ item }}</h3>
                <div class="main__club__ducks">
                    <img :src = "require('@/assets/profile.png')">
                </div>
            </div>
        </div>
</template>

<script>
export default {
    name: 'Maincardclub'
}
</script>

<style scoped>


.main__card__container {
    width: 90%;
    display: flex;
    flex-direction: column;
    align-items: center;
}

.main__card__container .main__card {
    background: var(--cardbackground);

    width: 80%;
    margin: 10px;

    display: flex;
    flex-direction: column;
    align-items: flex-start;
    border-radius: 10px;
}

.main__card__container .main__card h3 {
    font-size: 2em;
    margin: 10px ;
    color: var(--text_color);
}

.main__card__container .main__card .main__club__ducks {
    margin:  10px;
}

.main__card__container .main__card .main__club__ducks img {
    width: 50px;
    border-radius: 40em;
    object-fit: contain;
    margin: 5px;
    border: 5px solid #000;
}
</style>
