<template>
  <v-container class="fill-height d-flex flex-column align-center justify-center text-center">
    <v-icon size="64" color="primary">mdi-home</v-icon>
    <h1 class="mt-4">Kezdőlap</h1>
    <p class="text-medium-emphasis">
      Üdvözöllek a Vuetify + Vue Router demo projektben! 🚀
    </p>
    <v-btn color="primary" class="mt-4" to="/about">
      Ugrás az About oldalra
    </v-btn>
  </v-container>
</template>

<script setup>
// nincs most szükség logikára
</script>
