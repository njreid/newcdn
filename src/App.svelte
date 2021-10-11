<script lang="ts">
  import { onMount } from "svelte"

  onMount(()=> {
    console.log(window.Amplify)
  })

</script>

<template lang="pug">
h1 Testing

</template>

<style lang="stylus">

:global(body) 
  padding 10px 20px

</style>
