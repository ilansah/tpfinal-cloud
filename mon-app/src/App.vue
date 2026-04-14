<script setup>
const buildId = import.meta.env.VITE_BUILD_ID ?? 'local'
const today = new Date().toLocaleDateString('fr-FR')
</script>
<template>
<header>
<h1>Nom : SAHRAOUI ILAN</h1>
<p>Date : {{ today }}</p>
<p>Build : {{ buildId }}</p>
</header>
</template>

<style>

h1 {
  color: magenta;
}
</style>