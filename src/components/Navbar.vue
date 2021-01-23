<template>
  <header class=" shadow-xl bg-gray-800 p-3 text-gray-200 md:text-right">
    <a
      href="/"
      target="_blank"
      class="px-4 py-3 rounded-full hover:bg-blue-200 hover:text-gray-800"
      ><font-awesome-icon :icon="['fa', 'home']" /> Home
    </a>
    <a
      href="https://github.com/Federation-Interservices-D-informatique/"
      target="_blank"
      class="px-4 py-3 rounded-full hover:bg-blue-200 hover:text-gray-800"
      ><font-awesome-icon :icon="['fab', 'github']" /> GitHub
    </a>
  </header>
</template>

<script>
export default {
  name: "Navbar"
};
</script>

<style></style>
