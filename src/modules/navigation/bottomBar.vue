<template>

<v-bottom-navigation
      v-model="value"
      app
    >
      <v-btn
        value="timer"
        height="100%"
      >
        <v-icon>mdi-clock-time-five-outline</v-icon>
      </v-btn>

      <v-btn
        value="todo"
        height="100%"
      >
        <v-icon>mdi-format-list-checks</v-icon>
      </v-btn>

      <v-btn
        value="stats"
        height="100%"
      >
        <v-icon>mdi-chart-areaspline</v-icon>
      </v-btn>

      <v-btn
        value="play"
        height="100%"
      >
        <v-icon>mdi-controller-classic</v-icon>
      </v-btn>
    </v-bottom-navigation>
</template>