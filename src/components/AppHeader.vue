<template>
    <nav class="d-flex justify-content-around align-items-center">
        <img src="../../public/Cinema Grotta.png" alt="logo.png">
        <ul class="d-flex">
            <li>Home</li>
            <li>Orari Spettacoli</li>
            <li>Eventi</li>
            <li>Prossimamente</li>
            <li>Visita Guidata</li>
            <li>Il Ristorante</li>
            <li>Dove siamo</li>
        </ul>
    </nav>
</template>
<script>
export default {
    name: 'AppHeader'
}
</script>
<style lang="scss">
img{
    width: 300px;
    height: 300px;
}
li{
    list-style: none;
    padding-right: 5px;
    }
</style>