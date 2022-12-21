<script setup lang="ts">
import Logo from "@/assets/logo.svg";
</script>
<template>
  <v-app-bar>
    <v-container class="pa-0">
      <div class="px-4">
        <v-row class="ma-0">
          <v-col class="pa-0" cols="2">
            <v-img :src="Logo" max-height="46"></v-img>
          </v-col>
          <v-col class="pa-0" cols="8" align="center" align-self="center">
            <span style="font-size: 30px">
              <strong>Vue3 Prototype</strong>
            </span>
          </v-col>
          <v-col class="pa-0" cols="2" align-self="center">
            <v-icon>mdi-account-circle</v-icon>
          </v-col>
        </v-row>
      </div>
    </v-container>
  </v-app-bar>
</template>

<style scoped></style>
