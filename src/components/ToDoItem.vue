<template>
  <v-card pa-5>
    <v-checkbox
    v-model="done"
    ></v-checkbox>
    <v-card-text>My todo itme</v-card-text>
    
  </v-card>
</template>
<script>
export default {
  data(){
    return {
      done:true
    }
  }
}
</script>