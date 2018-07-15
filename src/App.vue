<template>
  <app-header></app-header>
</template>

<script>
import Header from './components/AppHeader';
export default {
  name: 'app',
  components: {
    appHeader: Header
  },
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>
