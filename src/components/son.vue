<template>
    <div>
        <span><slot :user="user"></slot></span>
        
    </div>
  </template>
  
  <script>
  
  
  export default {
    name: 'son',
    components: {
          
    },
    data(){
      return {
       user:{
        name:'黎明'
       }
      }
    }
  }
  </script>
  
  <style>
  li{
    list-style: none;
  }
  </style>
  