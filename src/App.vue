<template>
  <v-app>
    <v-app-bar app color="teal " dark>
      <v-app-bar-title>Madlibz</v-app-bar-title>
      <v-spacer></v-spacer>
      <router-link to="/create">
        <v-btn text> New MadLib </v-btn>
      </router-link>
      |
      <router-link to="/feed">
        <v-btn text> Community Libz </v-btn>
      </router-link>
    </v-app-bar>

    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script>
export default {};
</script>

<style scoped>
a {
  text-decoration: none;
}
.router-link-active .v-btn {
  color: rgb(255, 200, 100);
}
</style>
