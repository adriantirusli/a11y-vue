<template>
  <aside>
    <v-container>
      <v-row class="text-center">
        <v-col cols="12">
          <v-img
            :src="require('../assets/logo.png')"
            class="my-3"
            contain
            height="200"
          />
        </v-col>

        <v-col class="mb-4">
          <p class="subheading font-weight-regular">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
            <br>incididunt ut labore et dolore magna 
            <a
              href="#"
              target="_blank"
            >Link</a>
          </p>
        </v-col>

        <v-col
          class="mb-5"
          cols="12"
        >
          <h2 class="headline font-weight-bold mb-3">
            Important Links
          </h2>

          <v-row justify="center">
            <a
              v-for="(link, i) in importantLinks"
              :key="i"
              class="subheading mx-3"
              target="_blank"
            >
              {{ link.text }}
            </a>
          </v-row>
        </v-col>
      </v-row>
    </v-container>
  </aside>
</template>

<script>
  export default {
    name: 'Aside',

    data: () => ({
      importantLinks: [
        {
          text: 'Link',
        },
        {
          text: 'Link',
        },
        {
          text: 'Link',
        },
        {
          text: 'Link',
        },
        {
          text: 'Link',
        },
      ],
    }),
  }
</script>
