<script setup>
import { useHead } from 'unhead'

useHead({
  title: 'Inance',
  meta: [
    { charset: 'utf-8' },
    { name: 'viewport', content: 'width=device-width, initial-scale=1, shrink-to-fit=no' },
    { httpEquiv: 'X-UA-Compatible', content: 'IE=edge' },
    { name: 'keywords', content: '' },
    { name: 'description', content: '' },
    { name: 'author', content: '' }
  ],
  link: [
    { rel: 'stylesheet', href: 'https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/assets/owl.carousel.min.css' },
    { rel: 'stylesheet', href: '/css/bootstrap.css' },
    { rel: 'stylesheet', href: '/css/font-awesome.min.css' },
    { rel: 'stylesheet', href: '/css/style.css' },
    { rel: 'stylesheet', href: '/css/responsive.css' }
  ]
})
</script>

<template>
  <NuxtPage />
</template>
