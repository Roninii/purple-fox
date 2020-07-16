<template>
  <nav class="px-8 flex justify-between items-end">
    <img src="/logo.svg" width="50px" class="block" />
    <div class="flex justify-end">
      <nuxt-link
        class="p-4 uppercase text-lg text-gray-700 hover:text-primary"
        exact
        to="/"
        >Home</nuxt-link
      >
      <nuxt-link
        class="p-4 uppercase text-lg text-gray-700 hover:text-primary"
        to="/portfolio"
        >Portfolio</nuxt-link
      >
      <nuxt-link
        class="p-4 uppercase text-lg text-gray-700 hover:text-primary"
        to="/about"
        >About</nuxt-link
      >
      <nuxt-link
        class="p-4 uppercase text-lg text-gray-700 hover:text-primary"
        to="/contact"
        >Contact</nuxt-link
      >
      <nuxt-link
        class="p-4 uppercase text-lg text-gray-700 hover:text-primary"
        to="/blog"
        >Blog</nuxt-link
      >
    </div>
  </nav>
</template>
