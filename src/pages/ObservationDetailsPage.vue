<template>
  <q-page class="q-pa-md">
    <h1 class="text-h5">Detalji opažanja</h1>
    <p>Ovdje će biti prikaz pojedinog opažanja.</p>
    <p>Na ovoj stranici će se po identifikatoru opažanja prikazivati njegovi detalju.
        Identifikator se uzima iz URL-a da bi se prikazalo željeno opažanje.
    </p>

    <p>ID opažanja: {{ route.params.id }}</p>
  </q-page>
</template>

<script setup>
import { useRoute } from 'vue-router';
const route = useRoute();
</script>
