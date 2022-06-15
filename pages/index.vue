<template>
  <div>
    <h1>Home page</h1>
    <first-component :text="text" />
    <second-component />
  </div>
</template>

<script>
import { Component, Vue } from 'nuxt-property-decorator';
import FirstComponent from '~/components/FirstComponent';
import SecondComponent from '~/components/SecondComponent';

export default @Component({
  name: 'IndexPage',
  components: { FirstComponent, SecondComponent }
})

class IndexPage extends Vue {
  text= 'Duis aute irure dolor in reprehen derit involuptate velit esse cillum dolore eu fugiat nulla pariatur.'
}
</script>
