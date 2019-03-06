<template>
  <v-container
    class="pa-0"
    grid-list-xl
  >
    <v-layout wrap>
      <v-flex
        v-for="n in 12"
        :key="n"
        xs4
      >
        <base-card />
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
  export default {
    name: 'Home'
  }
</script>
