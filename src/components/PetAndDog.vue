<template>
  <div id="pet-and-dog">
    <div class="background"></div>
    <img src="../assets/dfgg-min.jpg" alt="dfgg-min" />
    <div class="care">
      <h2>Pet and Dog Care</h2>
      <p>
        Auctor eu augue ut lectus arcu. Sit amet tellus cras adipiscing.
        Malesuada proin libero nunc consequat interdum. Urna porttitor rhoncus
        dolor purus non enim praesent elementum.
      </p>
      <span>Image from </span>
      <a href="https://freepik.com/photos/people" class="freepik">Freepik</a>
      <a href="https://nicepage.com/" class="more">learn more</a>
    </div>
    <div class="articles container">
      <h2>Articles and Stores</h2>
      <p>
        Read insightful stories, browse care tips, important information, and
        articles about dogs and cats, and your other favourite, four-legged
        furry friends.
      </p>
      <a href="https://nicepage.com/">learn more</a>
    </div>
  </div>
</template>

<script>
export default {
  name: "PetAndDog",
};
</script>

<style lang="scss" scoped>
#pet-and-dog {
  .background {
    position: relative;
    background-color: #e5e5e5;
    height: 383px;
    width: 100%;
  }

  img {
    position: absolute;
    height: 624px;
    width: 881px;
    object-fit: cover;
    margin: -315px auto 0 calc(((100% - 1140px) / 2) + 80px);
  }

  .care {
    position: relative;
    background-color: #df046f;
    min-height: 429px;
    width: 487px;
    margin: 135px calc((100% - 1140px) / 2) 0 auto;
    padding: 30px 50px;
    text-align: center;

    h2 {
      font-family: "PT Sans", sans-serif;
      color: #fff;
      font-size: 2.25rem;
      font-weight: 700;
      margin-top: 20px;
    }

    p,
    span,
    a {
      font-size: 1.125rem;
      font-weight: 400;
      line-height: 1.8;
      margin-top: 20px;
      color: #fff;
    }

    p {
      color: #fef1e6;
    }

    .freepik {
      border-bottom: 1px solid #e6e6e6;
      font-weight: 700;
      cursor: pointer;

      &:hover {
        color: #e6e6e6;
        text-decoration: none;
      }
    }

    .more {
      display: block;
      border: 2px solid #fff;
      text-transform: uppercase;
      font-size: 16px;
      font-weight: 700;
      letter-spacing: 1px;
      margin: 38px 80px 0;
      padding: 10px 54px;
      cursor: pointer;

      &:hover {
        background-color: #fff;
        color: #f17c0e;
        text-decoration: none;
      }
    }
  }

  .articles {
    min-height: 280px;
    width: 518px;
    margin: -200px auto 62px calc((100% - 1140px) / 2);

    h2 {
      font-family: "PT Sans", sans-serif;
      color: #df046f;
      font-size: 2.25rem;
      font-weight: bold;
      line-height: 1.1;
      margin: 16px 0 0;
      display: block;
      margin-block-start: 0.83em;
      margin-block-end: 0.83em;
      margin-inline-start: 0px;
      margin-inline-end: 0px;
    }

    p {
      color: #111111;
      font-size: 1.25rem;
      font-weight: 400;
      font-style: italic;
      line-height: 1.7;
      margin: 20px 0 0;
      display: block;
      margin-block-start: 1em;
      margin-block-end: 1em;
      margin-inline-start: 0px;
      margin-inline-end: 0px;
    }

    a {
      color: #111111;
      border-bottom: 1px solid #000000;
      font-weight: 600;
      text-transform: uppercase;
      letter-spacing: 1px;
      margin-top: 20px;
      margin-bottom: 20px;
      cursor: pointer;

      &:hover {
        text-decoration: none;
      }
    }
  }
}
</style>
