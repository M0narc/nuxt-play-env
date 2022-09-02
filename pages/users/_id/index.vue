<template>
    <h1>A single user, with ID: {{ $route.params.id }}</h1>
</template>

<script>
    export default {
        validate (data){
            console.log(data)
            return /[0-9]/.test(data.params.id)
        },
        layout: 'users'
    }
</script>