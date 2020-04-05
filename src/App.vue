<template>
  <div class="">
    <NavBar/>
    <MainScreen/>
    <Banner/>
    <Footer/>
</div>

</template>
<style>

</style>


<script>
import NavBar from './components/NavBar'
import MainScreen from './components/MainScreen'
import Banner from './components/Banner'
import Footer from './components/Footer'

export default {
  name: 'App',
  components: {
    NavBar,
    MainScreen,
    Banner,
    Footer,
  }
}
</script>



