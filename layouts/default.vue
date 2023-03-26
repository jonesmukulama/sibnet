<template>
 <div class="flex justify-between w-full fixed items-center">
  <div class="ml-5">
   <nuxt-link to="/">
    <img src="" alt="logo" />
   </nuxt-link>
  </div>
  <div class="flex justify-between items-center w-[540px] h-16 pr-5 capitalize text-white font-bold">
   <nuxt-link to="/">home</nuxt-link>
   <nuxt-link to="/products">products</nuxt-link>
   <nuxt-link to="/services">services</nuxt-link>
   <nuxt-link to="/blog">blog</nuxt-link>
   <nuxt-link to="/about">about us</nuxt-link>
   <nuxt-link to="/contact">contact us</nuxt-link>
  </div>
 </div>
 <slot />
 <div class="flex items-center h-80 bg-neutral-800">
  <div class="flex justify-between w-10/12 mx-auto">
   <div class="flex flex-col w-1/5 text-orange-400 capitalize">
    <h1 class="text-2xl mb-5 capitalize">navigation</h1>
    <nuxt-link to="/">home</nuxt-link>
    <nuxt-link to="/products">products</nuxt-link>
    <nuxt-link to="/services">services</nuxt-link>
    <nuxt-link to="/about">about us</nuxt-link>
    <nuxt-link to="/contact">contact us</nuxt-link>
    <nuxt-link to="/news">news</nuxt-link>
    <nuxt-link to="/sitemap">site map</nuxt-link>
   </div>
   <div class="w-1/5 text-orange-400">
    <h1 class="text-2xl mb-5 capitalize">contact us</h1>
    <div class="mb-5">
     email: sibnet1@gmail.com <br />
     phone: 097777777 / 096666666 <br />
     address: sibnet1@gmail.com <br />
    </div>
    <h1 class="text-2xl mb-5 capitalize">social media</h1>
    <div>
      <a href="">f</a>
      <a href="">t</a>
     </div>
   </div>
   <div class="w-1/5 text-orange-400">
    <h1 class="text-2xl mb-5 capitalize">about us</h1>
    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Cupiditate expedita laborum non! Suscipit atque officia explicabo? Illo, perferendis animi voluptate rem placeat facere molestias cumque minus quas. Deleniti, dolores nisi!</p> 
   </div>
   <div class="flex flex-col justify-between w-1/4 text-orange-400">
    <div>
     <h1 class=" mb-5 text-2xl capitalize">our newsletter</h1>
     <div class="flex mb-10">
      <input class="bg-neutral-700 h-12 px-5 focus:outline-none" type="email" placeholder="johnsmith@example.com" />
      <button class="w-24 h-12 bg-orange-500 text-white font-semibold">subscribe</button>
     </div>
    </div>
   </div>
  </div>
 </div>
 <div class="bg-neutral-900 text-orange-400">
  <div class="flex justify-between items-center w-10/12 h-14 mx-auto">
   <span>&copy; copyright 2023. <nuxt-link to="/">sibnet limited</nuxt-link></span>
   <div>
    <nuxt-link to="/privacy">privacy policy</nuxt-link> | <nuxt-link to="/terms">terms and conditions</nuxt-link>
   </div> 
  </div>
 </div>
</template>

<style>
 h1 {
  margin-top: 2rem;
  margin-bottom: 2rem;
 }
 .router-link-active {
  color: rgb(234 88 12);
 }
</style>