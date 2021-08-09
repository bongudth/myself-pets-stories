<template>
  <div id="app">
    <Header />
    <PetAndDog />
    <SmallDogs />
    <DogTraining />
    <DogCare />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import PetAndDog from "./components/PetAndDog.vue";
import SmallDogs from "./components/SmallDogs.vue";
import DogTraining from "./components/DogTraining.vue";
import DogCare from "./components/DogCare.vue";

export default {
  name: "App",
  components: {
    Header,
    PetAndDog,
    SmallDogs,
    DogTraining,
    DogCare,
  },
};
</script>

<style lang="scss">
#app {
  font-family: "Open Sans", sans-serif;
  // font-family: "Montserrat", sans-serif;
  // font-family: 'PT Sans', sans-serif;
  // font-family: 'Roboto', sans-serif;
}
</style>
