<template>
  <div class="info-container">
    <h4>Info about available timeslots :</h4>
    <div class="info">
      <h5>Regular slots</h5>
      <p>Free</p>
    </div>
    <div class="info">
      <h5 :style="{ color: colorie1 }">Premium slots</h5>
      <p>INR 134</p>
    </div>
    <div class="info">
      <h5 :style="{ color: colorie2 }">Prime slots</h5>
      <p>INR 254</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Info",
  props: {
    msg: String,
  },
  data() {
    return {
      colorie1: "#8BE71A", //vert
      colorie2: "#6F26C1", //violet
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.info-container {
    border-radius: 10px;
    display: flex;
    justify-content: space-evenly;
    margin-top: 20px;
    background-color: #6ff9fdb3;
}
</style>