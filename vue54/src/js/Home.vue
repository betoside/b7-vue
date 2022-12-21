<template>
    <div>
        <span>Página Homepage: {{ t }} </span>

        <ul>
            <li>
                <router-link to="/user/1">User 1</router-link>
                <router-link to="/user/1/perfil"> - perfil</router-link>
                <router-link to="/user/1/posts"> - posts</router-link>
            </li>
            <li>
                <router-link to="/user/2">User 2</router-link>
                <router-link to="/user/2/perfil"> - perfil</router-link>
                <router-link to="/user/2/posts"> - posts</router-link>
            </li>
            <li>
                <router-link to="/contato">Contato (not found)</router-link>
            </li>
        </ul>

    </div>
</template>

<script>
export default{
    data() {
        return {
            t:'Skateboard Hitech'
        }
    }
}
</script>

<style>
span{
    color: #f00;
}
</style>