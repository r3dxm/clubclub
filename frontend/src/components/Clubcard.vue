<template>
    <div class="club__box">
                    <h3 class="club__box__name">club name</h3>
                    <div class="club__box__info">
                        <span class="club__box__persional" style="background-color: #b03c3c;"></span>
                        <span class="club__box__persional" style="background-color: #5d0a53;"></span>
                        <span class="club__box__persional" style="background-color: #ef5350;"></span>
                        <span class="club__box__persional" style="background-color: #ab47bc;"></span>
                        <span class="club__box__persional" style="background-color: #6a1b9a;"></span>
                        <span class="club__box__persional" style="background-color: #4527a0;"></span>
                        <span class="club__box__persional" style="background-color: #81d4fa;"></span>
                        <span class="club__box__persional" style="background-color: #7c4dff;"></span>
                        <span class="club__box__persional" style="background-color: #4db606;"></span>
                        <span class="club__box__persional" style="background-color: #e9c00a;"></span>
                        <span class="club__box__persional" style="background-color: #d70d5488;"></span>
                        <span class="club__box__persional" style="background-color: #0b4b248a;"></span>
                        <span class="club__box__persional" style="background-color: #7d00f290;"></span>
                        <span class="club__box__persional" style="background-color: #d21470;"></span>
                        <span class="club__box__persional" style="background-color: #00dec836;"></span>
                        <span class="club__box__persional" style="background-color: #98e30ce5;"></span>
                        <span class="club__box__persional" style="background-color: #8a0cf296;"></span>
                        <span class="club__box__persional" style="background-color: #ffffff;"></span>
                        <span class="club__box__persional" style="background-color: #81d4fa;"></span>
                        <span class="club__box__persional" style="background-color: #7c4dff;"></span>
                        <span class="club__box__persional" style="background-color: #4db606;"></span>
                        <span class="club__box__persional" style="background-color: #e9c00a;"></span>
                        <span class="club__box__persional" style="background-color: #d70d5488;"></span>
                    </div>
                </div>
</template>

<script>
export default {
    name: 'Clubcard'
}
</script>

<style scoped>
.clubs_list{
    margin: 20px 0;
    width: 500px;
}
.club__box {
    width: 100%;
    background-color: var(--color_light);
    padding: 10px;
    border-radius: 5px;
    margin: 25px 0;
    -webkit-border-radius: 5px;
    -moz-border-radius: 5px;
    -ms-border-radius: 5px;
    -o-border-radius: 5px;
}
.club__box .club__box__name {
    color: var(--color_dark);
    font-weight: 900;
}
.club__box .club__box__info {
    padding: 10px 0;

    display: flex;
    flex-wrap: wrap;
}
.club__box .club__box__info .club__box__persional {
    display: block;
    background-color: red;
    width: 20px;
    height: 20px;
    margin: 5px;
    border-radius: 4em;
    -webkit-border-radius: 4em;
    -moz-border-radius: 4em;
    -ms-border-radius: 4em;
    -o-border-radius: 4em;
}

.btn {
    background: var(--color_dark);
    border: none;
    color: var(--color_light);
    border-radius: 3px;
    padding: 5px 10px;
    -webkit-border-radius: 3px;
    -moz-border-radius: 3px;
    -ms-border-radius: 3px;
    -o-border-radius: 3px;
}
</style>