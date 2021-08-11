<template>
  <div id="sweet-heart">
    <div class="container">
      <div class="content">
        <h2>Sweet Heart</h2>
        <h1>(111) 452 22 22</h1>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "SweetHeart",
};
</script>

<style lang="scss" scoped>
#sweet-heart {
  position: relative;
  background-image: url(../assets/ghhh-min.jpg);
  background-size: cover;
  height: 800px;
  font-family: "PT Sans", sans-serif;
  color: #fff;
  line-height: 1.1;

  .content {
    position: absolute;
    height: 100%;
    width: 70%;

    h2 {
      font-size: 3rem;
      font-weight: bold;
      margin: 39px auto 0 20px;
    }

    h1 {
      font-size: 3rem;
      font-weight: 900;
      text-align: right;
      margin: 616px 20px 40px auto;
    }
  }
}
</style>
