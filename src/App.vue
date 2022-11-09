<script>
import JumbotronComponent from './components/JumbotronComponent.vue';

export default {
  components: {

    JumbotronComponent,
  },
  data() {
    return {
      message: 'hello world'
    }
  },
  methods: {

  }
}
</script>

<template>

  <JumbotronComponent />
</template>

<style>
* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}
</style>
