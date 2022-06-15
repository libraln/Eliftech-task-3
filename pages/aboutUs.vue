<template>
  <div>
    <h1>About Us</h1>
    <third-component />
    <fourth-component />
  </div>
</template>

<script>
import { Component, Vue } from 'nuxt-property-decorator';
import ThirdComponent from '~/components/ThirdComponent';
import FourthComponent from '~/components/FourthComponent';

export default @Component({
  name: 'aboutUsPage',
  components: { ThirdComponent, FourthComponent }
})

class AboutUsPage extends Vue {
}
</script>
