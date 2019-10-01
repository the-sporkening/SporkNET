<template>
  <div class="container">
    <div>
      <h1 class="title">
        SporkBot
      </h1>
      <h2 class="subtitle">
        Spork Discord Bot
      </h2>
      <div class="justify-between">
        <a
          href="https://discord.getsporked.lol"
          target="_blank"
          class="button--green"
        >
          Discord
        </a>
        <a
          href="https://snipey.dev"
          target="_blank"
          class="button--green"
        >
          SnipeyDev
        </a>
        <a
          href="https://github.com/snipey/sporkbot"
          target="_blank"
          class="button--grey"
        >
          GitHub
        </a>
      </div>
      <div class="w-full mt-10 mx-auto">
        <iframe src="https://discordapp.com/widget?id=128797258287153152&theme=dark" width="350" height="500" allowtransparency="true" frameborder="0"></iframe>
      </div>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
  @apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
