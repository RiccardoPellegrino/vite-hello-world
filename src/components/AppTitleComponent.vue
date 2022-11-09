<template>

    <h1><img src="favicon.ico" alt="icona" class="logo">{{ titolo }}</h1>

</template>

<script>
export default {
    name: 'AppTitleComponent',
    data() {
        return {
            titolo: 'La mia prima app con Vite!'
        }
    }
}
</script>

<style lang="css">
h1 {
    text-align: center;
    color: orange;
    font-family: cursive;
}

.logo {
    margin-right: 20px;
}
</style>