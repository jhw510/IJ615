<template>
    <div id="app">
        <Layout>
            <template >
            <img src="https://verdict4u.files.wordpress.com/2016/11/macbook-pro-2016_macbook-pro-2016-wallpapers-01.png" alt="Avatar" class="avatar"  >
            <h1>헤오니</h1>
            <router-link to="/join"><h1 id="join">회원가입</h1></router-link>
            <a target="login" mkt-analytics="login">로그인</a>
            </template>
            <template #sidebar>

            </template>
        </Layout>
    </div>

</template>

<script>
    export default {
        name: "Home"
    }
</script>

<style scoped>

</style>