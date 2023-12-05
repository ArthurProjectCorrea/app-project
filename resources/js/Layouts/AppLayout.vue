<script setup>
import { Link } from '@inertiajs/vue3'
</script>

<template>
  <main>
    <header class="">
      <Link href="/">Home</Link>
      <Link href="/about">About</Link>
      <Link href="/contact">Contact</Link>
    </header>
    <article>
      <slot />
    </article>
  </main>
</template>