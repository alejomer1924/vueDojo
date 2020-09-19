<template>
  <v-container>
    <v-row>
      <v-col>
        <v-text-field label="Search" v-model="word"></v-text-field>
      </v-col>
      <v-col>
        <v-btn class="mx-2" fab dark color="blue lighten-34" @click = "searchItem">
          <v-icon>mdi-magnify</v-icon>
        </v-btn>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "Search",
};
</script>