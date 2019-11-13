<template>
  <div class="mb-10 text-orange-300">
    <header class="lg:px-16 px-6 flex flex-wrap items-center pt-4 container mx-auto">
      <div class="flex-1 flex justify-between items-center">
        <nuxt-link to="/">
          <span>The Sporkening</span>
        </nuxt-link>
      </div>
      <!-- <label for="menu-toggle" class="pointer-cursor lg:hidden block"><svg class="fill-current text-gray-900" xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 20 20"><title>menu</title><path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z" /></svg></label>
      <input id="menu-toggle" class="hidden" type="checkbox">
      <div id="menu" class="hidden lg:flex lg:items-center lg:w-auto w-full">
        <nav>
          <ul class="lg:flex items-center justify-between text-base text-orange-300 lg:pt-0">
            <li>
              <nuxt-link class="lg:p-4 py-3 px-0 block border-b-2 border-transparent hover:border-orange-600" to="/auth/login">
                Login
              </nuxt-link>
            </li>
            <li>
              <nuxt-link class="lg:p-4 py-3 px-0 block border-b-2 border-transparent hover:border-orange-600" to="/auth/register">
                Register
              </nuxt-link>
            </li>
          </ul>
        </nav>
      </div> -->
    </header>
  </div>
</template>

<script>
// import PulseLogo from '../../public/logo.svg';
export default {
  name: 'Header'
}
</script>
