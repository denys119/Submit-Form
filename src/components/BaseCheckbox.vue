<template>
  <div id="checkbox-container">
  </div>
</template>

<script>
  export default {
    name: 'BaseCheckbox',
  }
</script>

<style scoped>
  #checkbox-container{
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    margin: 20px;
  }

  input {
    transform: scale(2);
    padding: 10px;
    cursor: pointer;
    margin-right: 10px;
  }
</style>