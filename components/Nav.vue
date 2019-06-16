<template>
  <nav class="main-nav">
    <nuxt-link to="/" tag="div" class="logo">
      <img src="img/Logo.png" alt="Teelonis logo">
    </nuxt-link>
    <ul>
      <nuxt-link tag="li" to="/about" exact-active-class="active-link">About</nuxt-link>
      <nuxt-link tag="li" to="/stories" exact-active-class="active-link">Shared Stories</nuxt-link>
      <nuxt-link tag="li" to="/experience" exact-active-class="active-link">Experience Us</nuxt-link>
    </ul>
  </nav>
</template>
