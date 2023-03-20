<script setup>
  import headerVue from './components/header.vue';
  import mainVue from './components/main.vue'
  import footerVue from './components/footer.vue'
 
  
</script>

<template>
 <div>
    <header>
         <headerVue></headerVue>
    </header>
    <main>
      <mainVue/>
    </main>
    <footer>
      <footerVue/>
    </footer>
 </div>
</template>

<style scoped>

</style>
