<template>
  <section
    id="get-in-touch"
    class="overflow-hidden"
  >
    <v-row
      class="info white--text"
      no-gutters
    >
      <v-col
        class="hidden-sm-and-down"
        md="6"
      >
        <v-img
          :src="require('@/assets/contact.png')"
          height="100%"
        />
      </v-col>

      <v-col
        class="pa-5"
        cols="12"
        md="6"
      >
        <base-bubble-1 />

        <base-heading class="mb-5">
          Get In Touch
        </base-heading>

        <v-sheet
          color="transparent"
          max-width="600"
        >

          <v-btn
            fab
            class="ma-2"
            href="https://www.instagram.com/jgaleas7"
            link
            target="_blank"
          >
            <v-icon
              dark
            >mdi-instagram</v-icon>
          </v-btn>

          <v-btn
            fab
            class="ma-2"
            href="https://github.com/Jgaleas7"
            link
            target="_blank"
          >
          Github
          </v-btn>

          <v-alert
            border="right"
            dark
          >
            Email: juangaleassantos@gmail.com
          </v-alert>

        </v-sheet>
      </v-col>
    </v-row>
  </section>
</template>

<script>
  export default {
    name: 'GetInTouch',
  }
</script>
