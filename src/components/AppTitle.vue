<script>

    export default {
        data() {
            return { title: 'La mia prima app con Vite!' }
        },
    }

</script>

<template>

    <div>
        <h1 class="main-title">
            {{ title }}
        </h1>
    </div>
  
</template>

<style scoped>

.main-title{
    color: red;
}

</style>
