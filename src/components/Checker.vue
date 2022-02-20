<template>
  <v-container>
    <v-row class="text-center">
      <v-col cols="12">
        <v-img
          :src="require('../assets/birrete-white.png')"
          class="my-3"
          contain
          height="200"
        />
      </v-col>

      <v-col>
        <v-text-field
          :v-model="mark"
          label="Enter your mark"
          :rules="rules"
          hide-details="auto"
        ></v-text-field>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "Checker",
  data: () => ({
    mark: "",
  }),
  methods: {
    markChecker() {
       
    },
  },
};
</script>

<style>
</style>