<template>
  <div>
    <article class="bg-primary -mt-8">
      <header class="max-w-screen-xl mx-auto text-center">
        <h3 class="text-white uppercase text-4xl">What we do</h3>
        <p class="text-purple-300 text-lg max-w-xl mx-auto">
          We build beautiful, performant websites that bring your business to
          the digital age so that you can focus on what matters to you.
        </p>
        <hr class="max-w-xs border border-purple-300 mx-auto my-2" />
      </header>
      <section class="flex wrap justify-evenly max-w-screen-lg mx-auto py-8">
        <Card v-for="n in 3" :key="n" :title="String(n)" />
      </section>
      <div class="max-w-screen-sm mx-auto flex justify-center py-8">
        <nuxt-link
          class="bg-white text-primary uppercase text-lg font-medium px-4 py-2 w-32 text-center rounded shadow hover:shadow-xl transition duration-300 transform hover:-translate-y-1"
          to="/contact"
          >See more</nuxt-link
        >
      </div>
    </article>
    <div class="-mt-8">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
        <path
          fill="#6417e3 "
          fill-opacity="1"
          d="M0,224L120,229.3C240,235,480,245,720,250.7C960,256,1200,256,1320,256L1440,256L1440,0L1320,0C1200,0,960,0,720,0C480,0,240,0,120,0L0,0Z"
        ></path>
      </svg>
    </div>
  </div>
</template>
