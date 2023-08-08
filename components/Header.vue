<script setup>

</script>

<template>
  <div class="container flex justify-between items-center py-6">
    <nuxt-link to="/" class="flex font-size-32 font-medium">
      <img  class="mr-3" src="~/assets/img/logo.png" alt=""> Bengal shop
    </nuxt-link>

    <div class="w-96">
      <div class="border rounded-full flex border-gray-50 p-1 items-center">
        <div class="min-w-max pl-3 pr-3">
          <img src="~/assets/img/search.png" alt="">
        </div>
        <input class="w-full py-1 outline-none" type="search" name="" id="" placeholder="Search here ...">

        <button class="bs-button-bg bg-gray px-6 rounded-full py-2 text-white" type="submit">Search</button>
      </div>
    </div>

    <div class="flex min-w-max">
      <nuxt-link to=""><span class="bs-icon-box rounded-full hover:bg-gray-400 inline-block flex items-center justify-center"><img src="~/assets/img/heart.png" alt=""></span></nuxt-link>
      <nuxt-link to="" class="relative"><span class="bs-icon-box rounded-full hover:bg-gray-400 inline-block flex items-center justify-center"><img src="~/assets/img/u_shopping-bag.png" alt=""></span><span class="absolute bg-red-600 px-1 h-4 top-0 right-0 rounded-full text-xs flex justify-center items-center text-white">0</span></nuxt-link>
      <nuxt-link to="" class="flex items-center"><span class="bs-icon-box rounded-full hover:bg-gray-400 inline-block flex items-center justify-center"><img src="~/assets/img/user.png" alt=""></span><span>Account</span></nuxt-link>
    </div>
  </div>
</template>

<style scoped>

</style>