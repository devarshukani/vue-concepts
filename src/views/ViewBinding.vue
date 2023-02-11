<template>
  <div>

  </div>
</template>

<script>
  export default {
    beforeCreate () {
      console.log("Hi from before created");
    },

    created() {
      console.log("Hi from created");
    },

    beforeMount () {
      console.log("Hi form before mounted");
    },

    mounted() {
        console.log("Hi from mounted");
    },

    beforeDestroy () {
      console.log("Hi from before destroyed");
    },

    destroyed() {
        console.log("Hi from destroyed");
    }
  }
</script>

<style lang="scss" scoped>

</style>