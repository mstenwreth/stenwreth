<template>
  <v-container>
    <h1>Login</h1>
    <v-form
      ref="form"
      v-model="valid"
      lazy-validation>
      <v-text-field
        v-model="name"
        :counter="10"
        :rules="nameRules"
        label="Name"
        required
      ></v-text-field>
    </v-form>
  </v-container>
</template>

<script>
export default {
  name: 'Login'
}
</script>
