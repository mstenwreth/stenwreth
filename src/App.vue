<template>
  <v-app id="app">
    <router-view/>
  </v-app>
</template>

<script>
export default {
  name: 'App',
  data: () => ({
    links: [
      'Dashboard',
      'Messages',
      'Profile',
      'Updates'
    ]
  })
}
</script>
