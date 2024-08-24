<script>
import AppMainSC from "./subComponentMain/AppMainSC.vue";
export default {
  data() {
    return {
      title: "MAIN",
    };
  },

  // 	methods:{
  // 		myMethods(){
  // 			...
  // 		},
  // 	},

  components: {
    AppMainSC,
  },

  // 	props:{
  // 		passaggioInfo: stringa,
  //  	 },
};
</script>

<template>
  <h1 class="text-3xl font-bold">{{ title }}</h1>
  <AppMainSC />
</template>

<style lang="scss" scoped></style>
