<template>
  <section class="body">
    <Nav/>

    <main>
      <nuxt/>
    </main>

    <Footer/>
  </section>
</template>

<script>
import Nav from '~/components/Nav.vue'
import Footer from '~/components/Footer.vue'

export default {
  components: {
    Nav,
    Footer
  }
}
</script>