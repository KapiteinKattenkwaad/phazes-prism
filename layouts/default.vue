<template>
  <div>
    <Header />
    <nuxt />
    <footer-prismic/>
  </div>
</template>

<script>
import FooterPrismic from '~/components/FooterPrismic.vue'
import Header from '~/components/Header.vue'

export default {
  components: {
    Header,
    FooterPrismic
  },
  head () {
    return {
      title: 'Prismic Nuxt.js Blog',
    }
  }
}
</script>
