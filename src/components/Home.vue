<template>
  <div class="main">
    <top-banner></top-banner>
  </div>
</template>
<script>
import TopBanner from '../components/TopBanner'
export default {
  name: 'Home',
  data () {
    return {
      name: 'home'
    }
  },
  methods: {},
  components: {
    TopBanner
  }
}
</script>
<style scope>

</style>
