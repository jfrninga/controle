<template>
  <div class="date">
    <p>Select a day </p>
    <input id="date" type="date" value="2021-11-29" required />
  </div>
</template>

<script>
export default {
  name: "DateInput",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.date {
    margin-bottom: 15px;
}
</style>