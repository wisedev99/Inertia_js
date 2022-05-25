<template>
  <nav class="ml-6">
    <ul class="flex">
      <li>
        <NavLink href="/" :active="$page.component === 'Home'">Home</NavLink>
      </li>
      <li>
        <NavLink href="/users?bu=buff" :active="$page.url.startsWith('/users')"
          >Users</NavLink
        >
      </li>
      <li>
        <NavLink href="/settings" :active="$page.component === 'Settings'"
          >Settings</NavLink
        >
      </li>
    </ul>
  </nav>
</template>
<script setup>
import Navlink from '../Shared/NavLink.vue'
</script>