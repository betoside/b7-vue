<!-- 
recomendacao da biblioteca
agora, dividir o codigo em 3 areas

js
template
css
-->

<script>
export default{
    data() {
        return {
            msg:'Olá Mundo!'
        }
    }
}
</script>

<template>
    <div id="app">
        <h1> {{ msg }} </h1>
        <hr>
        <router-link to="/">Home</router-link>
        <router-link to="/sobre">Sobre</router-link>
        <hr>

        <router-view></router-view>
    </div>
</template>

<style>
h1{
    background: #f00;
    color: #fff;
}
</style>