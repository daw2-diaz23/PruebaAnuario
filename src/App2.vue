<script setup>
  import Footer from './components/footer.vue';
import headerVue from './components/header.vue';
  import main2Vue from './components/main2.vue';
</script>

<template>
 <div>
    <header>
        <headerVue/>
    </header>
    <main>
       <main2Vue/>
    </main>
    <footer>
        <Footer></Footer>
    </footer>
 </div>
</template>

<style scoped>

</style>
