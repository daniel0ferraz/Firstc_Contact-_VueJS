<template>
  <h1>Olá mundo!</h1>
  <h2>Primeiro componente com VUE 3 ;(</h2>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'OlaMundo',
});
</script>

<style>
h1 {
  color: green;
}
</style>
