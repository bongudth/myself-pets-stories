<template>
  <div id="dog-training">
    <div class="title">
      <h4>dog training</h4>
      <h2>The importance of dog training</h2>
      <i class="fas fa-angle-double-right"></i>
    </div>
    <div class="content">
      <p>
        Positive Dog Training is a rewards-based approach to teaching pet
        parents how dogs think, learn and communicate. We focus on rewarding the
        behaviors we like to encourage appropriate dog behavior in the real
        world.
      </p>
      <div class="icon">
        <i class="fab fa-facebook-f"></i>
        <i class="fab fa-twitter"></i>
        <i class="fab fa-instagram"></i>
        <i class="fab fa-youtube"></i>
      </div>
    </div>
    <img
      src="../assets/closeup-photo-of-short-coated-white-and-gray-dog-825947.jpg"
      alt="con-cho-xau-xi"
    />
  </div>
</template>

<script>
export default {
  name: "DogTraining",
};
</script>

<style lang="scss" scoped>
#dog-training {
  position: absolute;
  display: flex;
  height: 583px;
  width: 100%;
  margin-top: 500px;

  .title {
    display: flex;
    flex-direction: column;
    justify-content: center;
    width: 38.33333333%;
    background-color: #df046f;
    color: #fff;
    font-family: "PT Sans", sans-serif;
    padding: 60px 30px;

    h4 {
      font-weight: 400;
      font-size: 1.5rem;
      line-height: 1.2;
      text-transform: uppercase;
    }

    h2 {
      font-size: 3.75rem;
      font-weight: 700;
      margin-top: 20px;
    }

    i {
      font-size: 64px;
      margin-top: 30px;
    }
  }

  .content {
    display: flex;
    flex-direction: column;
    justify-content: center;
    width: 23.33333333%;
    padding: 60px 30px;

    p {
      color: #111111;
      font-size: 1.125rem;
      font-weight: 400;
      line-height: 1.8;
    }

    .icon {
      font-size: 25px;
      margin-top: 30px;

      i {
        margin-right: 23px;
      }
    }
  }

  img {
    height: auto;
    width: 38.33333333%;
    object-fit: cover;
  }
}
</style>
