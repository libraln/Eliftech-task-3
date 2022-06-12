<template>
  <div>
    <h1>Home page</h1>
    <FirstComponent />
    <SecondComponent />
  </div>
</template>

<script>
import { Component, Vue } from 'nuxt-property-decorator';
import FirstComponent from '~/components/FirstComponent';
import SecondComponent from '~/components/SecondComponent';

export default @Component({
  name: 'indexPage',
  components: { FirstComponent, SecondComponent }
})

class indexPage extends Vue {}
</script>
