<template>
  <v-toolbar
    app
    color="white"
    prominent
  >
    <v-avatar
      color="grey"
      class="mr-3"
    />

    <v-btn
      v-for="n in 4"
      :key="n"
      flat
    >
      Item {{ n }}
    </v-btn>

    <v-spacer />

    <v-flex xs4>
      <v-text-field
        solo-inverted
        flat
        hide-details
      />
    </v-flex>
  </v-toolbar>
</template>
