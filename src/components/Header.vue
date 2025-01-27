<script setup>
import cartIcon from "/assets/img/icons/cart.svg";
import favoriteIcon from "/assets/img/icons/favorite-outline.svg";
</script>

<template>
  <header class="border-gray-light flex items-center justify-between gap-4 border-b p-10">
    <img src="/assets/img/logo.svg" alt="Greenshop" />
    <div class="flex items-center gap-4">
      <button class="group inline-flex cursor-pointer items-center gap-2 outline-hidden">
        <img :src="cartIcon" :width="18" :height="18" alt="Cart" />
        <span class="group-focus-visible:text-gray group-active:text-gray group-hover:text-gray">0</span>
      </button>
      <button class="group inline-flex cursor-pointer items-center gap-2 outline-hidden">
        <img :src="favoriteIcon" :width="18" :height="18" alt="Cart" />
        <span class="group-focus-visible:text-gray group-active:text-gray group-hover:text-gray">
          Favorite
        </span>
      </button>
    </div>
  </header>
</template>
