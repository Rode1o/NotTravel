<template>
  <v-card
    class="mx-auto my-12"
    max-width="350"
  >
    <v-img
      :src="urlimg"
      height="200px"
    />

    <v-card-title>
      {{username}}
    </v-card-title>

    <v-card-subtitle>
      {{description}}
    </v-card-subtitle>
  </v-card>
</template>

<script>
export default {
 props: ['username', 'urlimg', 'description']
}
</script>