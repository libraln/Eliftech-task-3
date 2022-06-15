<template>
  <header class="header">
    <div class="wrapper">
      <ul class="header-menu">
        <li>
          <nuxt-link to="/">
            Home
          </nuxt-link>
        </li>
        <li>
          <nuxt-link to="aboutUs">
            About Us
          </nuxt-link>
        </li>
      </ul>
    </div>
  </header>
</template>

<script>
import { Component, Vue } from 'nuxt-property-decorator';

export default @Component({
  name: 'Header'
})

class Header extends Vue {

}
</script>
