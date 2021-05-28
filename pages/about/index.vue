<template>
  <div>
    <h1>About</h1>
    <Carousel />
    <v-btn
      class="ma-2"
      outlined
      color="primary"
      :to="'/inspire'"
      @click="goToMainPage"
    >
      Kliknij
    </v-btn>
  </div>
</template>

<script>
export default {
  methods: {
    goToMainPage(evt) {
      console.log('goToMainPage', evt)
      // this.$router.push('/')
    },
  },
}
</script>
