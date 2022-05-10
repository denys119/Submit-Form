<template>
  <div id="radio-button">
  </div>
</template>

<script>
  export default {
    name: 'BaseRadio',
  }
</script>

<style scoped>
  #radio-button {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
  }

  #radio-button input {
    width: 30px;
    height: 30px;
    cursor: pointer;
  }
</style>