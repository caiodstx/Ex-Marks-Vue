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

      <p class="title font-weight-regular">
        Check here your marks:
        <br />
        <a id="check-anchor" href="#" target="_blank"
          ><v-btn
            id="check-link-btn"
            class="mx-2"
            fab
            dark
            large
            color="purple"
          >
            <v-icon dark> mdi-check </v-icon>
          </v-btn></a
        >
      </p>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "Checker",
  data: () => ({
    //
  }),
};
</script>

<style>
</style>