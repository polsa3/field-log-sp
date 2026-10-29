<script setup>
import { ref } from 'vue'
const nazivOpazanja = ref('')
const opisOpazanja = ref('')
</script>

<template>
  <h1>Novo opažanje</h1>
  <br />
  <q-input outlined v-model="nazivOpazanja" label="Naziv opažanja" />
  <br />
  <q-input outlined v-model="opisOpazanja" type="textarea" label="Opis opažanja" />
  <br />
  <p>Naziv: {{ nazivOpazanja }}</p>
  <br />
  <p>Opis: {{ opisOpazanja }}</p>
  <br />
  <q-btn to="/" color="purple" label="Povratak" />
</template>

<style>
.naslov {
  color: red;
  font-weight: bold;
}
</style>
