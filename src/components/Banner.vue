<template>
    <div class="w-full mt-16 gradientBlue flex-col text-center justify-center pt-32 pb-20" >
      <span class="block text-6xl  text-white font-serif font-semibold">Make the most of your business</span>
      <span class="block text-lg px-4 py-5 text-white font-medium font-medium">Every step of the way can be hard. A simple way to be successful is to make great products,<br> and give them amazing marketing. When faced with uncertainty in the markets, charge head on.</span>
      <div class="block flex-wrap mt-4">
        <a href="#" class="inline-flex bg-white py-5 px-4 text-blue font-bold rounded hover:bg-blue hover:text-white my-3 mx-4">Analyze your business</a>    
        <a href="#" class="inline-flex bg-transparent border border-white py-5 px-4 text-white font-bold rounded hover:bg-white hover:text-blue mx-4">Talk to our experts</a>    
      </div>
    </div>
</template>

<style>
.gradientBlue {
 background: #4662d8;
    /* fallback for old browsers */
    background: -webkit-linear-gradient(135deg, #19ceb0, #4662d8);
    /* Chrome 10-25, Safari 5.1-6 */
    background: linear-gradient(45deg, #649dff, #4662d8);
    /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
}
</style>

<script>
export default {
    name: 'banner',
}
</script>