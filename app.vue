<template>
  <div class="bg-green-900 h-100vh p-6">
    <section
      class="
        relative
        flex flex-col
        items-center
        justify-between
        space-y-4
        shadow
        rounded-lg
        p-4
        bg-gray-100
      "
    >
      <p class="text-left">
        Nuxt offers a compelling solution and a great ecosystem to help you ship
        fullstack Vue apps that are performant and SEO friendly. The flexibility
        to choose between SSR and SSG is icing on the cake.
      </p>
      <div class="flex w-full justify-between items-center">
        <a href="https://twitter.com/youyuxi" target="_blank" rel="noopener">
          <img
            loading="lazy"
            src="https://nuxtjs.org/img/home/testimonials/evan.png"
            alt="Evan You"
            width="48"
            height="48"
            class="h-12 w-12"
          />
        </a>
        <a
          href="https://twitter.com/youyuxi"
          target="_blank"
          rel="noopener"
          class="flex flex-1 pl-4 text-left flex-col"
          ><span class="font-bold text-base">Evan You</span>
          <span class="text-sm text-cloud">Creator of Vue.js </span></a
        >
        <a href="https://vuejs.org" target="_blank" rel="noopener">
          <img
            loading="lazy"
            src="https://nuxtjs.org/img/home/testimonials/vue.svg"
            alt="vue"
            width="28"
            height="28"
            class=""
          />
        </a>
      </div>
    </section>
  </div>
</template>
