<template>
  <div id="footer">
    <div class="content container">
      <div>
        <h6>Headline</h6>
        <p>Sample footer text</p>
      </div>
      <div>
        <h6>Headline</h6>
        <p>Sample footer text</p>
      </div>
      <div>
        <h6>Headline</h6>
        <p>Sample footer text</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style lang="scss" scoped>
#footer {
  background-color: #000;
  color: #fff;
  height: 209px;

  .content {
    display: flex;
    justify-content: space-around;
    align-content: center;
    padding-top: 70px;

    h6 {
      font-family: "PT Sans", sans-serif;
      color: #d9b4ef;
      font-weight: 400;
      font-size: 1.125rem;
      line-height: 1.2;
    }

    p {
      font-size: 0.875rem;
      line-height: 1.6;
      margin-top: 20px;
    }
  }
}
</style>
