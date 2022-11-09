<template>
    <div class="jumbotron">
        <AppTitleComponent />
    </div>

</template>

<script>
import AppTitleComponent from './AppTitleComponent.vue';
export default {
    components: {
        AppTitleComponent,
    },
    name: 'JumbotronComponent',
    data() {
        return {

        }
    }
}
</script>

<style lang="css">
.jumbotron {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100vw;
    height: 60vh;
    background-image: url("https://picsum.photos/1920/600?random=1");
    background-position: center;
    background-size: cover;


}
</style>