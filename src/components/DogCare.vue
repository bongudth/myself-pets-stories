<template>
  <div id="dog-care">
    <h1>Dog Care</h1>
    <div class="line"></div>
    <p class="sub">
      Feugiat nisl pretium fusce id. In ornare quam viverra orci sagittis. Amet
      commodo nulla facilisi nullam vehicula ipsum.
    </p>
    <div class="background"></div>
    <div class="content container">
      <div class="col1">
        <img
          src="../assets/black-white-short-coated-dog_249578-9501.jpg"
          alt="black-white-short-coated-dog_249578-9501"
        />
        <h2>Welcome</h2>
        <p>
          Welcome to Dog Hotel with overnight boarding, daycare, grooming,
          training, self-service dog wash and more.
        </p>
        <span>Images from </span>
        <a href="https://www.freepik.com/photos/dog">Freepik</a>
      </div>
      <div class="col2">
        <div class="row">
          <div class="block">
            <h4>1. Day Care</h4>
            <p>
              Vel pharetra vel turpis nunc eget. Ut eu sem integer vitae justo
              eget magna fermentum iaculis. Amet cursus sit amet dictum sit.
              Nisl rhoncus mattis.
            </p>
            <a href="https://nicepage.com/">more</a>
          </div>
          <div class="block orange">
            <h4>2. Pet Boarding</h4>
            <p>
              Vel pharetra vel turpis nunc eget. Ut eu sem integer vitae justo
              eget magna fermentum iaculis. Amet cursus sit amet dictum sit.
              Nisl rhoncus mattis.
            </p>
            <a href="https://nicepage.com/">more</a>
          </div>
        </div>
        <div class="row">
          <div class="block">
            <h4>3. Private Suites</h4>
            <p>
              Vel pharetra vel turpis nunc eget. Ut eu sem integer vitae justo
              eget magna fermentum iaculis. Amet cursus sit amet dictum sit.
              Nisl rhoncus mattis.
            </p>
            <a href="https://nicepage.com/">more</a>
          </div>
          <img
            src="../assets/portrait-adorable-little-doggie_23-2148316293.jpg"
            alt="portrait-adorable-little-doggie_23-2148316293"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "DogCare",
};
</script>

<style lang="scss" scoped>
#dog-care {
  color: #111111;

  h1 {
    font-family: "PT Sans", sans-serif;
    width: 715px;
    font-size: 3.75rem;
    font-weight: 700;
    line-height: 1.1;
    text-align: center;
    margin: 70px auto 0;
  }

  .line {
    height: 3px;
    width: 121px;
    border-bottom: 3px solid #000000;
    transform-origin: right center;
    margin: 20px auto 0;
  }

  .sub {
    width: 682px;
    font-size: 1.125rem;
    font-style: italic;
    font-weight: 400;
    line-height: 1.8;
    text-align: center;
    margin: 20px auto 0;
  }

  .background {
    background-color: #e5e5e5;
    height: 396px;
    margin-top: 525px;
  }

  .content {
    display: flex;
    height: 778px;
    width: 75%;
    margin: -873px auto 60px;

    .col1 {
      background-color: #a552d6;
      color: #fff;
      width: 41.66666667%;
      padding: 30px;

      img {
        height: 451px;
        width: 100%;
        object-fit: cover;
      }

      h2,
      p,
      span {
        margin-top: 20px;
      }

      h2 {
        font-family: "PT Sans", sans-serif;
        font-size: 2.25rem;
        font-weight: 700;
        line-height: 1.1;
      }

      p,
      span,
      a {
        font-size: 1.125rem;
        font-weight: 400;
        line-height: 1.8;
      }

      a {
        color: #fff;
        border-bottom: 2px solid #e6e6e6;
        font-weight: 700;
        cursor: pointer;

        &:hover {
          color: #e6e6e6;
          text-decoration: none;
        }
      }
    }

    .col2 {
      display: flex;
      flex-direction: column;
      width: 58.33333333%;

      .row {
        display: flex;
        background-color: #fff;
        height: 50%;
        margin: 0;

        .block {
          width: 50%;
          padding: 30px;

          h4 {
            font-family: "PT Sans", sans-serif;
            font-size: 1.5rem;
            font-weight: 400;
            line-height: 1.2;
          }

          p {
            font-size: 1.125rem;
            font-weight: 400;
            font-style: italic;
            line-height: 1.8;
            margin-top: 20px;
          }

          a {
            color: #111111;
            font-weight: 600;
            border-bottom: 2px solid #000;
            text-transform: uppercase;
            letter-spacing: 3px;
            margin-top: 20px;
            cursor: pointer;

            &:hover {
              color: #4d4d4d;
              border-bottom: 2px solid #4d4d4d;
              text-decoration: none;
            }
          }
        }

        .orange {
          background-color: #f17c0e;
          color: #fff;

          a {
            color: #fff;
            border-bottom: 2px solid #fff;

            &:hover {
              text-decoration: none;
            }
          }
        }

        img {
          height: 100%;
          width: 50%;
          object-fit: cover;
          margin: 0;
        }
      }
    }
  }
}
</style>
