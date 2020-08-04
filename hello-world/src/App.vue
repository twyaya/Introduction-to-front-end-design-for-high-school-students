<template>
  <div id="app">
    <h1>{{ title }}</h1>
    <input type="text" v-model="myname" value="myname">
    <p>大家好！我叫 {{ myname }}</p>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        myname:'請輸入姓名'
      }
    }
  }
</script>

<style></style>