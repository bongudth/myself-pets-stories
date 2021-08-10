<template>
  <div id="pet-food">
    <div class="background"></div>
    <div class="content container">
      <img src="../assets/fdg-min.jpg" alt="fdg-min" />
      <div class="col col-2">
        <div class="block care">
          <span>
            <i class="fas fa-dog"></i>
          </span>
          <h4>dog care</h4>
          <p>
            Sample text. Click to select the text box. Click again or double
            click to start editing the text.
          </p>
        </div>
        <div class="block behavior">
          <span>
            <i class="fas fa-paw"></i>
          </span>
          <h4>behavior</h4>
          <p>
            Sample text. Click to select the text box. Click again or double
            click to start editing the text.
          </p>
        </div>
      </div>
      <div class="col col-3">
        <div class="empty"></div>
        <div class="block food">
          <span>
            <i class="fas fa-bone"></i>
          </span>
          <h4>pet food</h4>
          <p>
            Sample text. Click to select the text box. Click again or double
            click to start editing the text.
          </p>
        </div>
        <div class="credit">
          <p>
            Image from <a href="https://freepik.com/photos/people">Freepik</a>
          </p>
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
#pet-food {
  height: 890px;
  margin-top: 1083px;

  .background {
    background-color: #e5e5e5;
    height: 100%;
    width: calc(((100% - 1140px) / 2) + 491px);
    margin: 0 0 0 auto;
  }

  .content {
    display: flex;
    max-height: 756px;
    width: 1166px;
    margin: -810px auto 60px;

    img {
      border: 13px solid transparent;
      height: 730px;
      width: 480px;
      object-fit: cover;
    }

    .col-2 {
      min-width: 28.33333333%;
    }

    .col-3 {
      min-width: 33.33333333%;
    }

    .col {
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      border: 13px solid transparent;
      padding: 0;

      .care {
        background-color: #df046f;

        span {
          background-color: #ffe6f2;
        }

        i {
          color: #df046f;
        }
      }

      .behavior {
        background-color: #a552d6;

        span {
          background-color: #f5ebfb;
        }

        i {
          color: #a552d6;
        }
      }

      .food {
        background-color: #f17c0e;
        height: 441px;

        span {
          background-color: #f5ebfb;
        }

        i {
          color: #f17c0e;
        }
      }

      .block {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        text-align: center;
        color: #fff;
        padding: 30px;

        span {
          border-radius: 50%;
          height: 76px;
          width: 76px;
          padding: 16px;

          i {
            font-size: 44px;
          }
        }

        h4 {
          font-family: "PT Sans", sans-serif;
          font-size: 1.5rem;
          font-weight: 700;
          line-height: 1.2;
          letter-spacing: 2px;
          text-transform: uppercase;
          margin: 20px 0 0;
        }

        p {
          font-size: 1.125rem;
          font-style: italic;
          font-weight: 400;
          line-height: 1.8;
          margin: 20px 0 0;
        }
      }

      .empty {
        height: 142px;
      }

      .credit {
        height: 121px;
        color: #111111;
        font-size: 1.125rem;
        font-weight: 400;
        font-style: italic;
        line-height: 1.8;
        padding: 30px;

        a {
          color: #111111;
          font-weight: 600;
          border-bottom: 1px solid #000000;
        }
      }
    }
  }
}
</style>
