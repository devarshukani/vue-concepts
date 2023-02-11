<template>
    <div class="home">
  
      <!-- One way binding  -->
      <h1>Hello {{ myname }}</h1>
    
      <!-- Two way binding -->
      <input type="text" v-model="user" >
      <h1>Hello {{ user }}</h1>
      
    </div>
  </template>
  
  <script>
  
  export default {
    data() {
      return {
        myname: "Devarsh",
        user: "Ukani"
      }
    },
  
  }
  </script>