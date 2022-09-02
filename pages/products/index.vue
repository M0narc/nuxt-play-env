<template>
    <div>
        <h1>The products view</h1>
        <input type="text" v-model="productId">
        <button @click="onLoadProduct">Load product Id</button>
    </div>
</template>

<script>
    export default {
        data(){
            return{
                productId:''
            }
        },
        methods: {
            onLoadProduct(){
                this.$router.push('/products/' + this.productId)
            }
        },
        layout: 'users'
    }
</script>
