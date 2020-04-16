<template>
  <div class="app">
    <NavBar/>
    <MainScreen/>
    <Banner/>
    <InfoContainer/>

    <div class="container bg-gray-100 max-w-full mx-auto px-6 py-12">
      <div class="max-w-lg mx-auto px-6">
          <div class="font-serif font-thin text-center text-black text-5xl">Contact Us</div>
          <div class="max-w-xl shadow-md">
            <form class=" bg-white rounded-lg px-8 pt-3 pb-8" action="https://formspree.io/xlewvwne" method="POST">
              <div class="mb-4 mt-2">
                <label class="block w-full text-gray-700 text-sm font-bold mb-2" for="username">
                  Name
                </label>
                <input type="text" name="name" class="shadow-sm appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" placeholder="Your Name">
              </div>
              <div class="mb-4">
                <label class="block w-full text-gray-700 text-sm font-bold mb-2" for="username">
                  Email
                </label>
                <input type="email" name="_replyto" class="shadow-sm appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" placeholder="Your Email">
              </div>
              <div class="mb-4">
                <label class="block w-full text-gray-700 text-sm font-bold mb-2" for="username">
                  Your Message
                </label>
                <textarea class="w-full h-32 resize-none focus:outline-none focus:shadow-outline border rounded text-gray-700 py-2 px-3" name="message" placeholder="Your Message"></textarea>
              </div>
              <div class="">
                <input type="submit" value="Send" class="transition ease-in-out duration-200 bg-blue hover:bg-white hover:text-blue text-white font-bold py-2 px-4 rounded focus:outline-none focus:shadow-outline">
              </div>
            </form>
          </div>
      </div>
    </div>

    <Footer/>

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



