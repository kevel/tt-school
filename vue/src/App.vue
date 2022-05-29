<template>
  <v-app>
    <v-layout>
      <v-app-bar></v-app-bar>
      <v-main>
        <router-view/>
      </v-main>
    </v-layout>

  </v-app>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { VApp, VAppBar, VLayout, VMain } from 'vuetify/components'

export default defineComponent({
  name: 'App',
  components: {
    VApp,
    VAppBar,
    VLayout,
    VMain,
  },
  data () {
    return {
      //
    }
  },
})
</script>
