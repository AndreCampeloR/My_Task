<template>
  <div class="main-container">
    <Nav/>
    <main>
    <h1>Perfil de usuário</h1>
    <Config/>
    </main>
    <Footer/>
  </div>
</template>

<script>

import Config from '../components/ComponentesPrincipais/Config.vue';
import Nav from '../components/ComponentesPrincipais/Nav.vue';
import Footer from '../components/ComponentesPrincipais/Footer.vue'

export default {
    name: "ConfiguracoesView",
    components: {
      Config,
      Nav,
      Footer
    }
}
</script>

<style>
h1{
  font-size: 24px;
  font-weight: 700;
  margin: 15px;
 }

 button{
  background-color: #000;
  color: #fff;
  border-radius: 50px;
  width: 180px;
  height: 40px;
  margin: 15px;
  right: 500px;
  bottom:260px;
  cursor: pointer;
  font-size: 1.0rem;
}
</style>