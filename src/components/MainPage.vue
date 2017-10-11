<template>
  <div style="position: relative;">
    <custom-parallax></custom-parallax>
    <div style="height: 30vw">
      <custom-profile-pic></custom-profile-pic>
    </div>
    <div class="center">
      <h3>Mi nombre es Carlos</h3>
    </div>
  </div>
</template>

<script>
import CustomParallax from './CustomParallax'
import CustomProfilePic from './CustomProfilePic'

export default {
  components: {
    CustomParallax,
    CustomProfilePic
  },
  data () {
    return {
      lang: 0
    }
  }
}
</script>

<style lang="scss">
.center{
  margin: 0 auto;
  text-align: center;
}
</style>
