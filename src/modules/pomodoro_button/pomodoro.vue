<script setup>
    import { ref } from 'vue';
 
    const time = ref(0);
</script>

<template>

  <!-- <v-divider>v-divider</v-divider> -->
  <v-card
    elevation="2"
  >
  <v-btn
    elevation="5"
    fab
    x-large
  ></v-btn>

  <div class="text-center pa-4 pt-0">

  <v-btn color="success" prepend-icon="mdi-plus" class="d-inline-flex" @click="count++">
    Start
  </v-btn>

  </div>

  </v-card>
</template>