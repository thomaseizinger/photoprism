<template>
  <v-card flat tile class="ma-0 pa-0 application p-about-footer">
    <v-card-actions class="px-4 py-2">
      <v-layout wrap align-top>
        <v-flex xs12 sm6 class="px-0 pb-2 body-1">
          <router-link to="/about">
            PhotoPrism®
            {{ $config.get("version") }}
            <br>© 2018-2020 Michael Mayer
          </router-link>
        </v-flex>

        <v-flex xs12 sm6 class="px-0 pb-2 body-1 text-xs-left text-sm-right">
          <a href="https://docs.photoprism.org/credits/" class="primary--text text--darken-4"
             target="_blank">Thank you</a> to everyone who made this possible!
          <br>
          <a href="https://raw.githubusercontent.com/photoprism/photoprism/develop/NOTICE"
             class="primary--text text--darken-4" target="_blank">
            3rd-party software packages</a>
        </v-flex>
      </v-layout>
    </v-card-actions>
  </v-card>
</template>

<script>
export default {
  name: 'p-about-footer',
  data() {
    return {};
  },
  methods: {},
};
</script>
