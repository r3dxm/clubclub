<template>
    <div class="main__card__container__profile">
        <div class="main__card__profile">
            <h3>club name</h3>
            <div class="main__club__ducks">
                <h4>8 members</h4>
                <button>View</button>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Profileclubcard'
}
</script>

<style scoped>
.main__card__container__profile {
    width: 100%;
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center;
}

.main__card__container__profile .main__card__profile {
    background: var(--cardbackground);

    width: 45%;
    margin: 10px;

    display: flex;
    flex-direction: column;
    align-items: flex-start;
    border-radius: 10px;
}


.main__card__container__profile .main__card__profile h3 {
    font-size: 2em;
    margin: 10px ;
    color: var(--text_color);
}

.main__card__container__profile .main__card__profile .main__club__ducks {
    margin:  10px;
}

.main__card__container__profile .main__card__profile .main__club__ducks img {
    width: 50px;
    border-radius: 40em;
    object-fit: contain;
    margin: 5px;
    border: 5px solid #000;
}

.main__card__container__profile .main__card__profile button {
    background-color: var(--cardbackground);
    color: var(--text_color);
    border-radius: 10px;
    height: 70%;
    width: 100%;
}
</style>