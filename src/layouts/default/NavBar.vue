<template>
  <!-- <v-app-bar flat class="bg-surface-variant"> -->    
  <v-app-bar flat class="pt-3">
    <!-- <v-app-bar-title>
      <v-icon icon="mdi-circle-slice-4" />

      Palnte
    </v-app-bar-title> -->
    <v-spacer></v-spacer>
    <v-img 
      contain
      height="300"
      src="@/assets/Plante.png">

    </v-img>
    <v-spacer></v-spacer>
    <ul class="nav d-flex font-weight-medium text-capitalize">
      <li class="mx-4 px-4 pt-2">Home</li>
      <li class="mx-4 px-4 pt-2">Guides</li>
      <li class="mx-4 px-4 pt-2">About</li>
      <li class="mx-4 px-4 pt-2">Shop</li>
      <li class="mx-4 px-4 pt-2">Contact Us</li>
      <li class="mx-4 px-4">
        <v-btn variant="flat" color="green-darken-3" class="font-weight-medium text-capitalize" text-white>
          SignIn
        </v-btn>
      </li>
    </ul>
    <v-spacer></v-spacer>
  </v-app-bar>
  
</template>

<script setup>
  //
</script>

<style scoped>
  .nav{
    list-style-type: none;
  }
</style>
