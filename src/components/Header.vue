<template>
    <v-app-bar
      app
      dark
      role="banner"
    >
      <div class="d-flex align-center">
        <v-toolbar-title>Header</v-toolbar-title>
      </div>

      <v-spacer></v-spacer>

      <Navigation/>
    
    </v-app-bar>
</template>

<script>
import Navigation from './Navigation'
export default {
    name: 'Header',
    components: {
        Navigation
    }
}
</script>