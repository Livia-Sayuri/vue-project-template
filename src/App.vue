<template>
  <v-app>

  <v-system-bar app>
      <v-spacer></v-spacer>
      <span>v-system-bar</span>
            <v-spacer></v-spacer>
            </v-system-bar>

    <v-app-bar app permanent fixed >
          <v-spacer></v-spacer>
      <span>v-app-bar</span>
       <v-spacer></v-spacer>
    </v-app-bar>

<v-row align="center">

    <v-row justify="space-around">
      <v-navigation-drawer app permanent clipped class="mt-100">
      <span>v-navigation-drawer</span>
    </v-navigation-drawer>
  </v-row>

    <v-row justify="space-around">
    <v-content >
      <span>v-content</span>
    </v-content>
    </v-row>
</v-row>

    <v-footer class="mt-5">
      <v-spacer></v-spacer>
      <span>v-footer</span>
    <v-spacer></v-spacer>
    </v-footer>

<v-bottom-navigation>
  <v-spacer></v-spacer>
  <span>v-bottom-navigation</span>
  <v-spacer></v-spacer>
</v-bottom-navigation>

  </v-app>
</template>