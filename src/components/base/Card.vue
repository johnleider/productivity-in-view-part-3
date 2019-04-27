<template>
  <div>
    <v-card
      class="mb-2"
      height="300"
      v-bind="$attrs"
      v-on="$listeners"
    />

    <h2
      v-if="title"
      class="title mb-2"
      v-text="title"
    />

    <div
      v-if="text"
      v-text="text"
    />
  </div>
</template>

<script>
  export default {
    inheritAttrs: false,

    props: {
      title: {
        type: String,
        default: undefined
      },
      text: {
        type: String,
        default: undefined
      }
    }
  }
</script>
