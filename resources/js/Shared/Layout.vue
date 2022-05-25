<template>
  <section class="p-6 bg-gray-200">
    <header class="flex">
      <h1 class="font-bold text-lg">My app</h1>
      <Nav></Nav>
    </header>
  </section>

  <!-- <section class="p-6">
      <div>
        <slot />
      </div>
  </section> -->
</template>

<script setup>
import Nav from "../Shared/Nav.vue";
</script>