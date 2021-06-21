<template>
  <div id="app">

    <Header />

    <Main />

    <Footer />
    
  </div>
</template>

<script>
import Header from './components/Header'
import Main from './components/Main'
import Footer from './components/Footer'




export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer
  }
}
</script>

<style lang="scss">
@import '~@fortawesome/fontawesome-free/css/all.min.css';

@import '~bootstrap/scss/bootstrap';

* {
  box-sizing: border-box;
  position: 0;
  margin: 0;
}
.wrapper_60 {
    width: 60%;
    margin: 0 auto;
}


</style>
