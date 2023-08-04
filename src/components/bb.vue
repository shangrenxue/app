<template>
    <div>
        <input type="text" v-focus>
    </div>
  </template>
  
  <script>
  
  
  export default {
    name: 'bb',
    components: {
          
    },
    data(){
      return {
       
      }
    },
    directives:{
        focus:{
            bind(el){
                el.focus()
            },
            inserted(el){
                el.focus()
            }
        }
    }
  }
  </script>
  
  <style>
  
  </style>
  