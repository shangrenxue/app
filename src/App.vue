<template>
  <div id="app">
    <h1>歌词收敛</h1>
    <son>
    <template v-slot:default="slotProps">
    {{ slotProps.user.name }}
    </template>
    </son>
    <bb/>
  </div>
</template>

<script>
import son from './components/son.vue'
import bb from './components/bb.vue'

export default {
  name: 'App',
  components: {
     son,
     bb
  },
  data(){
    return {
     
    }
  }
}
</script>

<style>

</style>
