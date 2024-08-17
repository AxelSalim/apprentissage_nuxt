<script lang="ts" setup>
  const nuxtApp = useNuxtApp()
  
  console.log(nuxtApp);
  
</script>


<template>
  <h1>event id : {{ $route.params.id }} </h1>
</template>


<style>

</style>