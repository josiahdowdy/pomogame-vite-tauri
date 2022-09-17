<script setup>

/* template specific */

import Counter from './modules/counter/mod.vue';
import Fetcher from './modules/fetcher/mod.vue';
import Pomodoro from './modules/pomodoro_button/pomodoro.vue';
import BottomBar from './modules/navigation/bottomBar.vue';

</script>

<template>
  <v-app>
    <v-main class="bg-grey-lighten-4">
      <v-container class="mx-auto" style="max-width: 768px;">

        <!-- <counter /> -->
        <!-- <fetcher class="mt-3" /> -->

        <pomodoro />
      </v-container>
      <BottomBar />
    </v-main>
      




    
  </v-app>
</template>
