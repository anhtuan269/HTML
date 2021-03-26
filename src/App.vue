<template>
  <Header />
  <Logo />
  <Menu />
  <Register />
  <Hosting />
  <services></services>
  <Plan />
  <Count />
  <Footer />

</template>

<script>
import Header from './components/Header.vue';
import Logo from  './components/Logo.vue';
import Menu from  './components/Menu.vue';
import Register from  './components/Register.vue';
import Hosting from  './components/Hosting.vue';
import Services from './components/Ser.vue';
import Plan from './components/Plan.vue';
import Count from './components/Count.vue';
import Footer from './components/Footer.vue';
export default {
  name: 'App',
  components : {
    Header,Logo,Menu,Register,Hosting,Services,Plan,Count,Footer
  }
 
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
*, ul {
  margin: 0;
  padding:0;
  font-family:sans-serif;
  font-size: 16px;
  color: #222;
}
p {
  margin: 0;
  padding:0
}
.border {
    border-color: #46af00!important;
    background-color: #fff;
    transition: all 0.3s linaer;
}
.border:hover {
background-color: #46af00;
color:#fff;
}
input:focus, select:focus {
  border: none;
}


</style>
