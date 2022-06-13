<template>
  <div>
    <h2>Third Component</h2>
    <p>
      Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
      tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim
      veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea
      commodo consequat. <br>Duis aute irure dolor in reprehenderit in
      voluptate velit esse cillum dolore eu fugiat nulla pariatur. Ut enim ad
      minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex
      ea commodo consequat.
    </p>
  </div>
</template>
<script>
import { Component, Vue } from 'nuxt-property-decorator';

export default @Component({
  name: 'ThirdComponent'
})

class ThirdComponent extends Vue {

}
</script>
