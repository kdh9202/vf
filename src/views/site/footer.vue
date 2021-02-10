<template>
<v-footer padless color="secondary" dark :footer="footer">
  <v-col
    class="text-center"
    cols="12"
  >
    {{ new Date().getFullYear() }} — <strong>Vuetify</strong>{{footer}}
  </v-col>
</v-footer>
</template>
<script>
export default {
  props: ['footer']
}
</script>
