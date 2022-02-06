<template>
<div>
  <header-component />
  
    <nuxt/>
    <footer-component />
</div>
</template>

<script>
import HeaderComponent from "~/components/headerComponent.vue";
import footerComponent from "~/components/footerComponent.vue";

export default {
    components: {
        HeaderComponent,
        footerComponent
    },
}
</script>

<style>
</style>
