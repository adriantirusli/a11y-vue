<template>
  <v-app>
    <Header/>
    <Navigation/>

    <v-content>
      <div class="d-flex align-center">
        <Main/>

        <v-spacer></v-spacer>

        <HelloWorld/>
      </div>
    </v-content>

    <Footer/>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';
import Header from './components/Header';
import Navigation from './components/Navigation'
import Main from './components/Main';
import Footer from './components/Footer';

export default {
  name: 'App',

  components: {
    HelloWorld,
    Header,
    Navigation,
    Main,
    Footer
  },

  data: () => ({
    //
  }),
};
</script>
