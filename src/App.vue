<template>
  <div class="app wrapper">
    <Header />
    <router-view />
    <Footer />
  </div>
</template>

<script>
import Header from './components/common/Header'
import Footer from './components/common/Footer'

export default {
  components: {
    Header,
    Footer
  }
}
</script>

<style>
@import 'https://use.fontawesome.com/releases/v5.5.0/css/all.css';
@import './assets/css/roboto.css';
@import './assets/css/reset.css';
@import './assets/css/common.css';
</style>