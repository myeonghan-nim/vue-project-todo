<template>
  <div>

    <form action="">
      ID : <input type="text" v-model="userId">
      Password : <input type="text">
      <input type="submit" value="login">
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