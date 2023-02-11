<template>
    <div>
      
      <button @click="sayHello()">Click to call function</button>
      <h1>Button pressed Count : {{ counter }}</h1>
    </div>
  </template>
  
  <script>
    export default{
  
      // vdata keyword to create data block
      data() {
        return {
          counter: 0
        }
      },
  
      // create functions inside this block
      // vmethod shortcut to create method block
      methods: {
        sayHello(){
          console.log("Method Called ");
          this.counter++;
        }
      },
  
    }
  </script>