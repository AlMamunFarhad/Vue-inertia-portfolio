<template>
  <div class="bg-slate-200 dark:bg-slate-900">
    <!-- Header -->
    <Header />
    <!-- Hero -->
     <!-- Page Content -->
     <main class="min-h-screen">
        <slot />
     </main>
    <!-- Footer -->
    <Footer />
  </div>
</template>

<script setup>
import Header from '../Components/Frontend/Header.vue';
import Footer from '../Components/Frontend/Footer.vue';

</script>
