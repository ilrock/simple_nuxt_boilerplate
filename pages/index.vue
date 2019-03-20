<template>
  <v-container grid-list-xs>
    <h1> Hello Nuxt! </h1>
  </v-container>
</template>

<script>
export default {
  middleware: 'authGuard'
}
</script>
