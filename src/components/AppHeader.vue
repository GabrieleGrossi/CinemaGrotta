<template>
    <nav class="d-flex justify-content-around align-items-center m-5">
        <img src="../../public/Cinema Grotta.png" alt="logo.png">
        <ul class="d-flex text-center">
            <li class="mx-2">Home</li>
            <li class="mx-2">Orari Spettacoli</li>
            <li class="mx-2">Eventi</li>
            <li class="mx-2">Prossimamente</li>
            <li class="mx-2">Visita Guidata</li>
            <li class="mx-2">Il Ristorante</li>
            <li class="mx-2">Dove siamo</li>
        </ul>
    </nav>
</template>
<script>
export default {
    name: 'AppHeader'
}
</script>
<style lang="scss" scoped>
img{
    width: 300px;
    height: 300px;
    border-radius: 50%;
}
li{
    list-style-type: none;
}
li:hover{
    border-bottom: 1px solid white;
}

</style>