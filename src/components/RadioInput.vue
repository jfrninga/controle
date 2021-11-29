<template>
  <div class="radio">
      <p>Choose one of the available timeslots : </p>
    <div class="heure">
      <label for="">12:00</label>
      <input type="radio" id="heure" name="heure" value="12:00" checked required />
    </div>
    <div class="heure">
      <label for="">12:30</label>
      <input type="radio" id="heure" name="heure" value="12:30" checked required />
    </div>
    <div class="heure">
      <label for="">13:00</label>
      <input type="radio" id="heure" name="heure" value="13:00" checked required />
    </div>
    <div class="heure">
      <label for="">13:30</label>
      <input type="radio" id="heure" name="heure" value="13:30" checked required />
    </div>
    <div class="heure">
      <label for="" :style="{ color: colorie2 }">14:00</label>
      <input type="radio" id="heure" name="heure" value="14:00" checked required />
    </div>
    <div class="heure">
      <label for="" :style="{ color: colorie2 }">14:30</label>
      <input type="radio" id="heure" name="heure" value="14:30" checked required />
    </div>
    <div class="heure">
      <label for="" :style="{ color: colorie2 }">15:00</label>
      <input type="radio" id="heure" name="heure" value="15:00" checked required />
    </div>
    <div class="heure">
      <label for="">15:30</label>
      <input type="radio" id="heure" name="heure" value="15:30" checked required />
    </div>
    <div class="heure">
      <label for="">16:00</label>
      <input type="radio" id="heure" name="heure" value="16:00" checked required />
    </div>
    <div class="heure">
      <label for="" :style="{ color: colorie1 }">18:00</label>
      <input type="radio" id="heure" name="heure" value="18:00" checked required />
    </div>
    <div class="heure">
      <label for="" :style="{ color: colorie1 }">18:30</label>
      <input type="radio" id="heure" name="heure" value="18:30" checked required />
    </div>
    <div class="heure">
      <label for="" :style="{ color: colorie1 }">19:00</label>
      <input type="radio" id="heure" name="heure" value="19:00" checked required />
    </div>
    <div class="heure">
      <label for="" :style="{ color: colorie1 }">19:30</label>
      <input type="radio" id="heure" name="heure" value="19:30" checked required />
    </div>
  </div>
</template>

<script>
export default {
  name: "RadioInput",
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
.heure {
    /* margin-bottom: 20px; */
    padding: 5px;
}
</style>








