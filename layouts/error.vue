<template>
  <div class="container mx-auto pt-16 w-2/3">
    <div class="flex justify-center">
      <img class="" src="~/assets/Spork_Main.png">
    </div>
    <div class="text-orange-300 container mx-auto mt-16 flex justify-center">
      <div class="">
        <p v-if="error.statusCode === 404" class="text-5xl font-semibold">
          Page not found
        </p>
        <p v-else>
          An error occurred
        </p>
        <nuxt-link to="/" class="inline-block rounded-sm py-3 px-6 font-semibold border bg-transparent border-orange-500 align-middle">
          Home page
        </nuxt-link>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: ['error']
  // layout: 'blog' // you can set a custom layout for the error page
}
</script>
