<template>
  <DateInput msg=""/>
  <RadioInput msg=""/>
  <Info msg=""/>
  <ButtonInput msg="" v-on:validation="message='you have registered your appointment'" />
</template>

<script>
import DateInput from './components/DateInput.vue'
import RadioInput from './components/RadioInput.vue'
import Info from './components/Info.vue'
import ButtonInput from './components/ButtonInput.vue'

export default {
  name: 'App',
  components: {
    DateInput,
    RadioInput,
    Info,
    ButtonInput
  },
   data() {
    return{
     message:'you have registered your appointment' 
    }
    
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
