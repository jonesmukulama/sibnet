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
 <div class="min-h-screen">
  <div class="h-[540px] bg-slate-300 overflow-hidden flex"></div>
 </div>
 <div class="h-72 bg-slate-800"></div>
 <div class="h-14 bg-slate-900"></div>
</template>

<style scoped>
 nuxt-link:hover, router-link-active-exact {
  color: rgb(234 88 12);
 }
</style>