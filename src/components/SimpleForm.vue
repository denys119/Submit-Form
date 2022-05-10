<template>
  <div class="form-container">
  </div>
</template>

<script>
import BaseInput from './BaseInput';
import BaseCheckbox from './BaseCheckbox';
import BaseTextarea from './BaseTextarea';
import BaseSelect from './BaseSelect';
import BaseRadio from './BaseRadio';
  export default {
    name: 'SimpleForm',
    components: {
      BaseCheckbox,
      BaseInput,
      BaseTextarea,
      BaseSelect,
      BaseRadio,
      Form,
      Field,
      ErrorMessage
    },
  }
</script>

<style scoped>
  .form-container {
    height: 750px;
    max-height: 700px;
    overflow: auto;
    border: 1px solid rgb(249, 229, 186);
    padding: 20px;
    box-shadow: 2px 1px 1px 1px;
    display: flex;
    align-items: center;
    flex-direction: column;
    justify-content: center;
  }

  .form-container h1 {
    text-align: center;
    font-size: 50px;
    font-weight: 400;
  }

  .form-container form {
    display: flex;
    width: 400px;
    flex-direction: column;
    align-items: center;
  }

  .form-container form div {
    width: 100%;
    display: flex;
    flex-direction: column;
  }

  .form-container form div h4 {
    font-size: 20px;
    color: rgb(74, 76, 77);
  }

  .job-title {
    font-size: 20px;
    font-weight: normal;
  }

  button {
    display: flex;
    align-items: center;
    justify-content: center;
    height: 50px;
    font-weight: bold;
    font-size: 20px;
    cursor: pointer;
    background: rgb(249, 229, 186);
    border: 1px solid rgb(249, 217, 149);
    width: 100%;
  }

  span {
    color: red;
  }

  #radio-buttons {
    display: flex;
    flex-direction: row;
  }

  #terms {
    display: flex;
    flex-direction: row;
  }
</style>