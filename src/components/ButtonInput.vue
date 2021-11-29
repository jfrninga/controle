<template>
  <button v-on:click="$emit('validation')">Save and continue</button>
</template>

<script>
export default {
  name: "ButtonInput",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    button {
    background-color: #ff7800;
    color: white;
    border: none;
    width: 30%;
    padding: 5px;
    border-radius: 5px;
    margin-top: 40px;
    cursor: pointer;
    margin-bottom: 40px;
    }
</style>
