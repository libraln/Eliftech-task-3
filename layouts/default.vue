<template>
  <div class="container">
    <div class="content">
      <header-component />
      <nuxt class="wrapper" />
    </div>
    <footer-component />
  </div>
</template>

<script>
import { Component, Vue } from 'nuxt-property-decorator';
import HeaderComponent from '~/components/HeaderComponent';
import FooterComponent from '~/components/FooterComponent';

export default @Component({
  name: 'default',
  components: { HeaderComponent, FooterComponent }
})

class Default extends Vue {}
</script>
