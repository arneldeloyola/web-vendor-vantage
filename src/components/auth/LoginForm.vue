<template>
  <v-form fast-fail @submit.prevent>
    <br />
    <v-text-field label="Email" variant="outlined" prepend-icon="mdi-email"></v-text-field>

    <v-text-field
      label="Password"
      type="password"
      variant="outlined"
      prepend-icon="mdi-lock"
    ></v-text-field>

    <v-btn
      class="mt-2"
      type="submit"
      block
      color="blue-lighten-1"
      elevation="5"
      prepend-icon="mdi-login"
      >Login</v-btn
    >
  </v-form>
</template>
