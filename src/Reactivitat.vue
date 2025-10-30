<script setup>
import { ref } from "vue";
const msg = ref("Benvingut/da visitant!");
const count = ref(0);
</script>

<template>
    <div class="container">
  <div>
    <img src="https://laviladelpingui.es/images/logo_laviladelpingui_arale.png" alt="arale">
    <h1>Bon dia al dematí a la vil·la del pingüí!</h1>
    <p>{{ msg }}</p>
  </div>
  <div>
    <h2> Compta les visites a la vil·la:</h2>
  </div>
  <div>
    <h4>Has visitat la vil·la: </h4>
      <button @click="count++">
        {{ count }} vegades.
      </button>
  </div>
  <img class="kk" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRLQ6lx6OsWn1FLc6Z3aonj2Vu2i2l-PN03yQ&s" alt="kk">
  </div>
</template>

<style scoped>

h1 {
  color: rgb(189, 28, 122);
}
.kk {
  width: 150px;
  margin-top: 20px;
}

.container {
  text-align: center;
  font-family: 'Arial', sans-serif;
  margin-top: 50px;
}
</style>
