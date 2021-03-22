<template>
  <v-app-bar color="transparent" flat absolute elevate-on-scroll class="header">
    <v-toolbar-title class="header-item">Trivia</v-toolbar-title>

    <v-spacer></v-spacer>

    <nuxt-link class="header-item" to="/"><div>Home</div></nuxt-link>
    <nuxt-link class="header-item" to="/"><div>Our Product</div></nuxt-link>
    <nuxt-link class="header-item" to="/"><div>Pricing</div></nuxt-link>
    <nuxt-link class="header-item" to="/"><div>Contact</div></nuxt-link>
  </v-app-bar>
</template>

<script>
export default {
  name: 'Header',
}
</script>

<style lang="scss">
.header {
  padding: 1rem 4rem;
  .header-item {
    text-decoration: none;
    margin-right: 3rem;
    color: var(--base-color);
    &:last-child {
      margin-right: 0;
    }
  }
}
</style>
