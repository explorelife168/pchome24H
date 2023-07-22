<template>
  <div class="home">
    <NavComponent />
    <inputComponent />
    <MainComponent />
    <Main2Component />
    <Main3Component />
    <Main4Component />
  </div>
</template>

<script>
import NavComponent from "@/components/NavComponent.vue";
import inputComponent from "@/components/inputComponent.vue";
import MainComponent from "@/components/MainComponent.vue";
import Main2Component from "@/components/Main2Component.vue";
import Main3Component from "@/components/Main3Component.vue";
import Main4Component from "@/components/Main4Component.vue";

export default {
  name: "HomeView",
  components: {
    NavComponent,
    inputComponent,
    MainComponent,
    Main2Component,
    Main3Component,
    Main4Component,
  },
};
</script>

<style lang="scss" scoped>
* {
  padding: 0;
  box-sizing: border-box;
  margin: 0;
}
</style>
