<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
  </div>
  <h1 @click="goToDaybook" class="btn btn-primary">Primary</h1>
</template>

<script>
export default {

  methods: {
    goToDaybook() {
      this.$router.push({ name:'no-entry' })
    }
  }

}
</script>


