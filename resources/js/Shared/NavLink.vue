<template>
  <Link
    class="text-blue-500 hover:underline"
    :class="{ 'font-bold inderline': active }"
  >
  </Link>
  <slot />
</template>
<script setup>
import { Link } from "@inertiajs/inertia-vue3";
const props = defineProps({
  active: Boolean,
});
</script>