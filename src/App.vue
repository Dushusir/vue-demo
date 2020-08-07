<template>
  <div id="app">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'


export default {
  name: 'App',
  components: {
    HelloWorld
  },
  data: ()=> {
    return {
      pen: null
    }
  },
  created(){
    
  },
  mounted() {
  },
  methods: {
  }
}
</script>

<style>
</style>
