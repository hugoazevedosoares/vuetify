<template>
  <v-chip
    color="#f6914d"
    class="pr-12 v-tidelift"
    href="https://tidelift.com/subscription/npm/vuetify?utm_source=vuetify&utm_medium=referral&utm_campaign=homepage"
    rel="noopener"
    target="_blank"
  >
    <v-img
      alt="Tidelift"
      left
      class="mr-4"
      src="https://cdn.vuetifyjs.com/images/affiliates/tidelift-small.png"
      width="24px"
    />
    <span class="body-2 text-uppercase font-weight-regular hidden-sm-and-down">
      Vuetify For Enterprise Available via Tidelift
    </span>
    <span class="body-2 text-uppercase font-weight-regular hidden-md-and-up">
      Get Enterprise Support
    </span>
  </v-chip>
</template>

<style lang="sass">
.v-tidelift
  position: absolute !important
  right: -24px
  text-decoration: none
  top: 0
</style>
