<template>
  <div id="app">
        <Title/>
        <Contact/>
  </div>
</template>

<script>
import Title from '@/components/Title.vue'
import Contact from '@/components/Contact.vue'
export default {
  name: 'App',
  components: {
      Title,
      Contact
    }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
