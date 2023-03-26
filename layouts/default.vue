<template>
 <div class="flex justify-between items-center">
  <div class="ml-5">
   <nuxt-link to="/">
    <img src="" alt="logo" />
   </nuxt-link>
  </div>
  <div class="flex justify-between items-center w-[540px] h-16 pr-5 capitalize bg- font-bold">
   <nuxt-link to="/">home</nuxt-link>
   <nuxt-link to="/products">products</nuxt-link>
   <nuxt-link to="/services">services</nuxt-link>
   <nuxt-link to="/blog">blog</nuxt-link>
   <nuxt-link to="/about">about us</nuxt-link>
   <nuxt-link to="/contact">contact us</nuxt-link>
  </div>
 </div>
 <slot />
 <div class="flex justify-center items-center h-72 bg-neutral-800">
  <div class="flex justify-between items-center w-10/12">
   <div class="w-1/4 text-orange-400">
    Lorem ipsum dolor sit amet consectetur, adipisicing elit. Cupiditate expedita laborum non! Suscipit atque officia explicabo? Illo, perferendis animi voluptate rem placeat facere molestias cumque minus quas. Deleniti, dolores nisi!
   </div>
   <div class="flex flex-col w-1/4 text-orange-400">
    <nuxt-link to="">home</nuxt-link>
    <nuxt-link to="">products</nuxt-link>
    <nuxt-link to="">services</nuxt-link>
    <nuxt-link to="">about us</nuxt-link>
    <nuxt-link to="">contact us</nuxt-link>
    <nuxt-link to="">news</nuxt-link>
    <nuxt-link to="">site map</nuxt-link>
   </div>
   <div class="w-1/4 text-orange-400">
    <input class="bg-neutral-700 h-12 px-5 focus:outline-none" type="email" placeholder="johnsmith@example.com" />
    <button class="w-24 h-12 bg-orange-500">Subscribe</button>
   </div>
  </div>
 </div>
 <div class="flex justify-center items-center h-14 mb-0 bg-neutral-900 text-orange-400">&copy; copyright 2023. <nuxt-link to="/">sibnet limited</nuxt-link></div>
</template>

<style scoped>
 .router-link-active-exact {
  color: rgb(234 88 12);
 }
</style>