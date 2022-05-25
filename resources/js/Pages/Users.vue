<template>
  <div>

    <h1>Users</h1>

    <Nav></Nav>

    <p>The current time {{ time }}</p>

    <Link 
    href="/users" 
    class="text-blue-500" 
    preserve-scroll>
    Refresh
    </Link>
    
  </div>
</template>

<script setup>
import { Link } from "@inertiajs/inertia-vue3";
import Nav from "../Shared/Nav.vue";

const props = defineProps({
  time: String,
});
</script>