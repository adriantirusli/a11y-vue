<template>
  <v-app>
    <Header/>
    
    <Layout/>
    
    <Footer/>
  </v-app>
</template>

<script>
import Header from './components/Header';
import Footer from './components/Footer';
import Layout from './components/Layout'

export default {
  name: 'App',
  components: {
    Header,
    Layout,
    Footer
  },
};
</script>
