<template>
  <NavBar />
  <main class="container-fluid">
  
    <router-view />
  </main>

 <Footer />
</template>

<script>
import Footer from "./components/Footer.vue"
import NavBar from './components/NavBar.vue';



export default{
  components:{
    NavBar,Footer
    
}
}
</script>


<style src="@/assets/css/style.css">
</style>
