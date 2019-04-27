<template>
  <v-container
    pa-0
    grid-list-xl
  >
    <v-layout wrap>
      <v-flex
        v-for="n in 12"
        :key="n"
        xs4
      >
        <base-card
          :to="`/detail/${n}`"
          title="I'm a text title"
          text="Mauris turpis nunc, blandit et, volutpat molestie congue nunc, vitae euismod ligula urna in dolor."
        />
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
  export default {
    name: 'Home'
  }
</script>
