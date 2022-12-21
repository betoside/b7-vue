<template>
    <div>
        <span>Página do User</span>
        <!-- <span>ID User: {{ id }} </span> -->
        <br>
        <span>ID User: {{ $route.params.id }} </span>

        <br>
        <router-view></router-view>
    </div>
</template>

<script>
export default{
    data() {
        return {

        }
    }
}
</script>

<style>
span{
    color: #00f;
}
</style>