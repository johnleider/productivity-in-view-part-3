<template>
  <v-app>
    <core-toolbar />

    <core-view />
  </v-app>
</template>

<script>
  import CoreToolbar from '@/components/core/Toolbar'
  import CoreView from '@/components/core/View'

  export default {
    components: {
      CoreToolbar,
      CoreView
    }
  }
</script>
