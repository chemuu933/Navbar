<!-- src/components/Navbar.vue -->
<template>
  <nav class="bg-gray-800 text-white p-4 flex justify-between items-center">
    <div class="text-2xl font-semibold">My Website</div>
    <ul class="flex space-x-6">
      <li><router-link to="/" class="hover:text-gray-400">Home</router-link></li>
      <li><router-link to="/about" class="hover:text-gray-400">About</router-link></li>
      <li><router-link to="/services" class="hover:text-gray-400">Services</router-link></li>
      <li><router-link to="/contact" class="hover:text-gray-400">Contact</router-link></li>
    </ul>
  </nav>
</template>

<script>

</script>
