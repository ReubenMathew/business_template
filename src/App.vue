<template>
  <div class="">
    <NavBar/>
    <MainScreen/>
</div>


</template>

<script>
import NavBar from './components/NavBar'
import MainScreen from './components/MainScreen'

export default {
  name: 'App',
  components: {
    NavBar,
    MainScreen,
  }
}
</script>

