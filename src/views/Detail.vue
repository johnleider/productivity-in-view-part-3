<template>
  <v-container
    grid-list-xl
    pa-0
  >
    <v-layout wrap>
      <v-flex
        tag="h1"
        display-2
        mb-3
        xs12
      >
        Title
      </v-flex>

      <v-flex
        xs12
        md3
      >
        <v-list>
          <v-list-tile>
            <v-list-tile-content>
              <v-list-tile-title>Preview</v-list-tile-title>
            </v-list-tile-content>
          </v-list-tile>
        </v-list>
      </v-flex>

      <v-flex
        xs12
        md9
      >
        <v-card height="400" />
      </v-flex>
    </v-layout>
  </v-container>
</template>
