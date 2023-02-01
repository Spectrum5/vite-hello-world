<script>
import AppTitle from "./components/AppTitle.vue"
export default {
  components: {
    AppTitle,
  },

  data() {
    return {
      count: 0
    }
  }
}
</script>

<template>
  <button @click="count++">Count is: {{ count }}</button>
  <AppTitle/>
</template>

<style scoped>
button {
  font-weight: bold;
}
</style>