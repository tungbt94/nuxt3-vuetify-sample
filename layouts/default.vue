<template>
  <v-app>
    <v-app-bar height="22" color="grey-darken-3" elevation="0"/>
    <v-navigation-drawer width="72" color="grey-darken-2" permanent/>
    <v-navigation-drawer width="150" color="grey-darken-1" permanent/>
    <v-app-bar height="48" color="grey" elevation="0"/>
    <v-navigation-drawer position="right" width="150" color="grey-lighten-1" permanent/>
    <v-app-bar position="bottom" height="48" color="grey-lighten-2" elevation="0"/>
    <v-main>
      <slot></slot>
    </v-main>
  </v-app>
</template>