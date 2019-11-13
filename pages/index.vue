<template>
  <div class="container mx-auto pt-16 w-2/3">
    <div class="flex justify-center">
      <img class="" src="~/assets/Spork_Main.png">
    </div>
    <div class="container mx-auto mt-16">
      <div class="flex justify-center">
        <nuxt-link to="/teams">
          <div class="inline-block bg-transparent mx-4 text-orange-300 font-semibold hover:text-white py-4 px-12 border border-orange-500 hover:border-orange-900 rounded">
            Teams
          </div>
        </nuxt-link>
        <a href="//discord.getsporked.lol">
          <div class="inline-block bg-transparent mx-4 text-orange-300 font-semibold hover:text-white py-4 px-12 border border-orange-500 hover:border-orange-900 rounded">
            Discord
          </div>
        </a>
        <nuxt-link to="/invite">
          <div class="inline-block bg-transparent mx-4 text-orange-300 font-semibold hover:text-white py-4 px-12 border border-orange-500 hover:border-orange-900 rounded">
            SporkBot
          </div>
        </nuxt-link>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  components: {
  }
}
</script>
