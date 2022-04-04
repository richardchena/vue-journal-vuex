<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">

    <h1>HOLA MUNDO</h1>
    <button @click="goToDaybook" class="btn btn-primary">PRIMARY</button>
    <button @click="goToDaybook" class="btn btn-secondary">SECONDARY</button>
    <button @click="goToDaybook" class="btn btn-success">SUCCESS</button>
  </div>
</template>

<script>
export default {
  methods:{
    goToDaybook(){
      this.$router.push({name: 'no-entry'})
    }
  }
}
</script>