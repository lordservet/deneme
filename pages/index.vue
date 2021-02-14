<template>
  <section>
    <div>
      <v-row justify="center" align="center">
        <v-col cols="12" sm="3" md="6">
          <combo1 />
        </v-col>
        <v-col cols="12" sm="3" md="6">
          <combo2 />
        </v-col> </v-row
      ><v-row justify="center" align="center">
        <v-col cols="12" sm="12" md="12">
          <Datatablo />
        </v-col>
      </v-row>
    </div>
  </section>
</template>

<script>
import Datatablo from "~/components/Datatablo.vue";
import combo1 from "~/components/Combos/combo1.vue";
import combo2 from "~/components/Combos/combo2.vue";

export default {
  components: {
    Datatablo,
    combo1,
    combo2,
  },
};
</script>
