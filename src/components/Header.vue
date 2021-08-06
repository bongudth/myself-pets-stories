<template>
  <div id="header" class="container">
    <div class="logo">Pets Stories</div>
    <i class="fas fa-bars"></i>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style lang="scss" scoped>
#header {
  background-color: #fff;
  height: 74px;
  display: flex;
  align-items: center;
  justify-content: space-between;

  .logo {
    font-family: "PT Sans", sans-serif;
    color: #a552d6;
    font-size: 30px;
    font-weight: 900;
  }

  .fas {
    font-size: 24px;
  }
}
</style>
