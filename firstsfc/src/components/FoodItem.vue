<template>
  <div>
    <h2>{{ name }}</h2>
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: 'Apples',
      message: 'I like apples'
    }
  }
};
</script>

<style>
  #app > div {
    border: dashed rgb(16, 16, 44) 1px;
    display: inline-block;
    margin: 10px;
    padding: 10px;
    background-color: rgb(144, 146, 238);
  }
</style>