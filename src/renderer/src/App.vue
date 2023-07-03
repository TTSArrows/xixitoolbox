<script>
export default {
  data() {
    return {
      drawer: true
    }
  }
}
</script>

<template>
  <v-app id="inspire">
    <v-navigation-drawer v-model="drawer" permanent>
      <v-list density="compact" nav>
        <v-list-item prepend-icon="mdi-home" title="Home" value="home"></v-list-item>
        <v-list-item prepend-icon="mdi-account" title="My Account" value="account"></v-list-item>
        <v-list-item
          prepend-icon="mdi-account-group-outline"
          title="Users"
          value="users"
        ></v-list-item>
      </v-list>
    </v-navigation-drawer>
    <v-main style="height: 250px">
      <v-card>123</v-card>
      <v-card>123</v-card>
      <v-card>123</v-card>
    </v-main>
  </v-app>
</template>
