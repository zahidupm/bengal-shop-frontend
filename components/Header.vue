<script setup>
import Logo from "~/components/Logo.vue";
</script>

<template>
 <div>
   <div class="container">
     <div class="flex justify-between items-center py-6">
       <Logo></Logo>


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
         <nuxt-link to="/"><span class="bs-icon-box rounded-full hover:bg-gray-400 inline-block flex items-center justify-center"><img src="~/assets/img/heart.png" alt=""></span></nuxt-link>
         <nuxt-link to="/" class="relative"><span class="bs-icon-box rounded-full hover:bg-gray-400 inline-block flex items-center justify-center"><img src="~/assets/img/u_shopping-bag.png" alt=""></span><span class="absolute bg-red-600 px-1 h-4 top-0 right-0 rounded-full text-xs flex justify-center items-center text-white">0</span></nuxt-link>
         <nuxt-link to="/" class="flex items-center"><span class="bs-icon-box rounded-full hover:bg-gray-400 inline-block flex items-center justify-center"><img src="~/assets/img/user.png" alt=""></span><span>Account</span></nuxt-link>
       </div>
     </div>

     <div class="flex items-center">
       <div class="w-96">
          <div class="bs-dark-green-bg flex rounded-full px-4 py-2 cursor-pointer items-center">
            <div class="min-w-max"><img src="~/assets/img/menu-right.png" alt=""></div>
            <div class="w-full text-center text-white px-6">
              All Categories
            </div>
            <div class="min-w-max">
              <img src="~/assets/img/chevron-down.png" alt="">
            </div>
          </div>
       </div>
       <div class="w-full">
         <ul class="flex justify-center">
           <li><nuxt-link class="p-4" to="/">Home</nuxt-link></li>
           <li><nuxt-link class="p-4" to="/">Shop</nuxt-link></li>
           <li><nuxt-link class="p-4" to="/">Pages</nuxt-link></li>
           <li><nuxt-link class="p-4" to="/">Blog</nuxt-link></li>
           <li><nuxt-link class="p-4" to="/">Contact</nuxt-link></li>
           <li><nuxt-link class="p-4" to="/">Truck Order</nuxt-link></li>
         </ul>
       </div>
       <nuxt-link to="/" class="min-w-max bs-dark-orange-color flex">
         <img class="mr-3" src="~/assets/img/u_percentage.png" alt=""> Special Offers
       </nuxt-link>
     </div>
   </div>
 </div>
</template>

<style scoped>

</style>