<template>
  <div class="app">
    <NavBar/>
    <MainScreen/>
    <Banner/>
    <InfoContainer/>
    <Footer class="mt-10"/>
</div>

</template>
<style>

.bgimg1 {
    background-image: url('./assets/svg/investment.svg');
}


</style>


<script>
import NavBar from './components/NavBar'
import MainScreen from './components/MainScreen'
import Banner from './components/Banner'
import Footer from './components/Footer'
import InfoContainer from './components/InfoContainer'

export default {
  name: 'App',
  components: {
    NavBar,
    MainScreen,
    Banner,
    InfoContainer,
    Footer,
  }
}
</script>



