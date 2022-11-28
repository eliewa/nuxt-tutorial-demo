<template>
  <div>
      <header>
        <nav class="container mx-auto p-4">
          <NuxtLink to="/products" class="text-green-500 font-bold text-xl">Nuxt Dojo Merch</NuxtLink>
        </nav>
      </header>

    <div class="container mx-auto p-4 border-b-2">
      <slot></slot>
    </div>

    <footer class="flex justify-between container mx-auto p-4 bg-white">
      <ul class="flex gap-10">
            <li class="hover:border-b-2 hover:border-b-green-300 active:underline p-1"><NuxtLink to="/">Home</NuxtLink></li>
            <li class="hover:border-b-2 hover:border-b-green-300 active:underline p-1"><NuxtLink to="/about">About</NuxtLink></li>
            <li class="hover:border-b-2 hover:border-b-green-300 active:underline p-1"><NuxtLink to="/products">Products</NuxtLink></li>
      </ul>
    </footer>
  </div>    
</template>