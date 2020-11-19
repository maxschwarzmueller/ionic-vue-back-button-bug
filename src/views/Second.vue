<template>
  <base-layout title="Second">
    <div id="container">
      <ion-button @click="goBack">Go Back (replace)</ion-button>
    </div>
  </base-layout>
</template>

<script>
import { IonButton } from "@ionic/vue";

export default {
  components: {
    IonButton,
  },
  methods: {
    goBack() {
      this.$router.replace("/home");
    },
  },
};
</script>