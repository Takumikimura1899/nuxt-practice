<template>
  <div>
    <nav>
      <nuxt-link to="/" no-prefetch>Home</nuxt-link>
      <nuxt-link to="/about" no-prefetch>About</nuxt-link>
      <nuxt-link :to="{ name: 'users-list' }">User LIst</nuxt-link>
    </nav>
  </div>
</template>
