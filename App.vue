<template>
  <div>
    <app-header></app-header>
    <app-Ninjas></app-Ninjas>
    <app-footer></app-footer>
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Footer from './components/Footer.vue';
import Ninjas from './components/Ninjas.vue';
export default {
  components: {
    'app-header': Header,
    'app-footer': Footer,
    'app-Ninjas': Ninjas
  },
  data () {
    return {
    }
  }
}
</script>

<style scoped>

</style>
