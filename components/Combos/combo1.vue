<template>
  <v-combobox dense filled hide-selected outlined solo></v-combobox>
</template>
<script>
export default {
  data() {
    return {
      select: [],
      items: ["Programming3", "221", "4432", "Vuetify"],
    };
  },
};
</script>