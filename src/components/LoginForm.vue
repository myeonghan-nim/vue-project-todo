<template>
  <div>
    <form action="">
      ID: <input type="text" v-model="userId">
      PW: <input type="text">
      <input type="submit" value="Login">
    </form>
  </div>
</template>

<script>
export default {
  data: function() {
    return {
      userId: '',
    }
  }
}
</script>

<style>
</style>
