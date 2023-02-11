<template>
    <div>
      
      <input type="text" v-model="text">
      <br>
      <br>
      <button @click="sayHello()">Find Text length</button>
      <h1>length of text : {{ len }}</h1>
    </div>
  </template>
  
  <script>
    export default{
  
      // vdata keyword to create data block
      data() {
        return {
          len: 0,
          text: ""
        }
      },
  
      
  
      // create functions inside this block
      // vmethod shortcut to create method block
      methods: {
        sayHello(){
          this.len = this.text.length
        }
      },
  
    }
  </script>