<template>
  <nav class="px-8 flex justify-between items-end">
    <nuxt-link to="/">
      <img src="/logo.svg" width="50px" class="block" />
    </nuxt-link>
    <div class="flex justify-end">
      <nuxt-link
        class="p-4 uppercase text-lg text-gray-700 hover:text-primary"
        active-class="text-primary underline"
        exact
        to="/"
        >Home</nuxt-link
      >
      <nuxt-link
        class="p-4 uppercase text-lg text-gray-700 hover:text-primary"
        active-class="text-primary underline"
        to="/portfolio"
        >Portfolio</nuxt-link
      >
      <nuxt-link
        class="p-4 uppercase text-lg text-gray-700 hover:text-primary"
        active-class="text-primary underline"
        to="/contact"
        >Contact</nuxt-link
      >
      <nuxt-link
        class="p-4 uppercase text-lg text-gray-700 hover:text-primary"
        active-class="text-primary underline"
        to="/blog"
        >Blog</nuxt-link
      >
    </div>
  </nav>
</template>

<style scoped>
.underline {
  position: relative;
  text-decoration-color: #6417e3;
  text-decoration-thickness: 2px;
  text-underline-offset: 0.3rem;
}
</style>
