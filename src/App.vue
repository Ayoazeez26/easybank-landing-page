<template>
  <div id="app">
    <Header />
    <FirstSection />
    <SecondSection />
    <ThirdSection />
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import FirstSection from './components/FirstSection.vue'
import SecondSection from './components/SecondSection.vue'
import ThirdSection from './components/ThirdSection.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    FirstSection,
    SecondSection,
    ThirdSection,
    Footer
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Public+Sans:wght@300;400;500;600;700&display=swap');
#app {
  font-family: 'Public Sans', Helvetica, Arial, sans-serif;
  box-sizing: content-box;
}
</style>
