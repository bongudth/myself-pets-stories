<template>
  <div id="contact-us">
    <div class="background-gray">
      <div class="background-pink">
        <div class="info">
          <div class="block">
            <div class="title">
              <i class="fas fa-phone-alt"></i>
              <h5>Call Us</h5>
            </div>
            <p>1 (234) 567-891, 1 (234) 987-654</p>
          </div>
          <div class="block">
            <div class="title">
              <i class="fas fa-map-marker-alt"></i>
              <h5>Location</h5>
            </div>
            <p>121 Rock Sreet, 21 Avenue, New York, NY 92103-9000</p>
          </div>
          <div class="block">
            <div class="title">
              <i class="fas fa-hourglass"></i>
              <h5>Business Hours</h5>
            </div>
            <p>Mon – Fri …… 10 am – 8 pm, Sat, Sun ....… Closed</p>
          </div>
        </div>
        <div class="background-white">
          <h2>Contact Us</h2>
          <div class="form">
            <input type="text" placeholder="Enter your Name" />
            <input type="email" placeholder="Enter a valid email address" />
            <textarea name="message" id="message" cols="50" rows="4"></textarea>
            <input type="submit" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ContactUs",
};
</script>

<style lang="scss" scoped>
#contact-us {
  .background-gray {
    background-color: #e5e5e5;
    height: 751px;
    display: flex;
    align-items: center;

    .background-pink {
      background-color: #df046f;
      height: 459px;
      width: 100%;
      display: flex;
      align-items: center;

      .info {
        height: 387px;
        width: 409px;
        color: #fff;
        margin: 100px auto 100px 190px;

        .block {
          padding: 15px 30px 10px;

          .title {
            display: flex;

            i {
              font-size: 22px;
            }

            h5 {
              font-family: "PT Sans", sans-serif;
              font-size: 1.25rem;
              font-weight: 700;
              line-height: 1.2;
              text-transform: uppercase;
              margin-left: 20px;
            }
          }

          p {
            font-size: 1.125rem;
            font-weight: 400;
            line-height: 1.8;
            margin-top: 10px;
          }
        }
      }

      .background-white {
        background-color: #fff;
        color: #111111;
        height: 561px;
        width: 597px;
        border: 1px solid #999999;
        box-shadow: 5px 5px 20px 0 rgba(0, 0, 0, 0.4);
        margin: 0 calc(((100% - 1140px) / 2)) 0 auto;
        padding: 30px 50px;

        h2 {
          font-family: "PT Sans", sans-serif;
          font-size: 3.75rem;
          font-weight: 700;
          line-height: 1.1;
          text-transform: uppercase;
          margin: 28px 0 0 0;
        }

        .form {
          display: flex;
          flex-direction: column;
          margin-top: 20px;

          input,
          textarea {
            border: none;
            border-bottom: 2px solid #000;
            padding: 10px 12px;
            margin-bottom: 28px;
          }

          input[type="submit"] {
            background-color: #fff;
            color: #000;
            font-weight: 700;
            text-transform: uppercase;
            letter-spacing: 1px;
            width: fit-content;
            border: 2px solid #000;
            padding: 10px 30px;

            &:hover {
              background-color: #000;
              color: #fff;
            }
          }
        }
      }
    }
  }
}
</style>
