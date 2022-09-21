<template>
    <div>
        <h1>the users view</h1>
        <input type="text" v-model="userId">
        <button @click="onLoadUser">Load user id</button>
        <input type="radio" name="beds" value="1" />1+
        <nuxt-child />
    </div>
</template>

<script>
export default {
    data() {
        return {
            userId: ''
        }
    },
    methods: {
        onLoadUser() {
            this.$router.push('/users/' + this.userId)
        }
    },
    layout: 'users'
}
</script>


<style>
input[type="radio"] {
    margin-right: 0px;
}
</style>