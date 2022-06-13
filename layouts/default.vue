<template>
  <div class="container">
    <div class="content">
      <Header />
      <Nuxt class="wrapper" />
    </div>
    <Footer />
  </div>
</template>

<script>
import { Component, Vue } from 'nuxt-property-decorator';
import Header from '~/components/Header';
import Footer from '~/components/Footer';

export default @Component({
  name: 'default',
  components: { Header, Footer }
})

class Default extends Vue {}
</script>
