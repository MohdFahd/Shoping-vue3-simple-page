<template>
  <main class="relative">
    <Nav />
    <section class="xl:padding-1 wide:padding-r padding-b"><Hero /></section>

    <section class="padding"><PopularProducts /></section>

    <section class="padding"><SuperQuality /></section>

    <section class="padding-x py-10"><Services /></section>

    <section class="padding"><SpacialOffer /></section>

    <section class="bg-pale-blue padding"><CustomerReviews /></section>

    <section class="padding-x sm:py-32 py-16 w-full"><Subscribe /></section>

    <section class="bg-black padding-x padding-t pb-8"><Footer /></section>
  </main>
</template>

<script setup>
import { RouterLink, RouterView } from "vue-router";
import {
  Nav,
  Hero,
  CustomerReviews,
  Footer,
  PopularProducts,
  Services,
  SpacialOffer,
  Subscribe,
  SuperQuality,
} from "@/components";
</script>
