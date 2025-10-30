<script setup>
import { ref, computed } from 'vue'

const nom = ref('Silvia')
const majus= computed(()=> nom.value.toUpperCase())
</script>

<template>
  <h1>{{ nom }}</h1>
  <h2>Nom en majus computed: {{majus}}</h2>
</template>
