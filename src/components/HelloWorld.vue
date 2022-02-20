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

      <v-col class="mb-4">
        <h1 class="display-2 font-weight-bold mb-3">
          Welcome to Mark checker!
        </h1>

        <p class="subheading font-weight-regular">
          Check here your marks:
          <br />
          <a id="check-anchor" href="/checker" target="_blank"
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
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "HelloWorld",

  data: () => ({
    //
  }),
};
</script>

<style lang="scss">
#check-link-btn {
  margin: 5vh;
}
#check-anchor {
  text-decoration: none;
}
</style>