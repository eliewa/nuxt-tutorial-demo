<template>
  <div>
      <header class="bg-white p-4 border-b-2">
        <nav class="flex justify-between container mx-auto">
          <NuxtLink to="/" class=" text-green-500 font-bold text-xl">Nuxt Dojo</NuxtLink>
          <ul class="flex gap-10">
            <li class="hover:border-b-2 hover:border-b-green-300 active:underline"><NuxtLink to="/">Home</NuxtLink></li>
            <li class="hover:border-b-2 hover:border-b-green-300 active:underline"><NuxtLink to="/about">About</NuxtLink></li>
            <li class="hover:border-b-2 hover:border-b-green-300 active:underline"><NuxtLink to="/products">Products</NuxtLink></li>
          </ul>
        </nav>
      </header>
    </div>

    <div class="container mx-auto">
      <slot></slot>
    </div>
</template>