
<template>
  <v-ons-toolbar>
    <div class="left">
      <v-ons-toolbar-button>
        <v-ons-icon icon="ion-navicon, material:md-menu"></v-ons-icon>
      </v-ons-toolbar-button>
    </div>
    <div class="center">{{ title }}</div>
  </v-ons-toolbar>
</template>

<!-- // // // //  -->

<script>
export default {
  name: 'device_list',
  props: ['title']
}
</script>


