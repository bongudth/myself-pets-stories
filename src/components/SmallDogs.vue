<template>
  <div id="small-dogs" class="container">
    <div class="background"></div>
    <img src="../assets/fghh-min.jpg" />
    <svg width="236" height="236" viewBox="0 0 160 160" class="pink">
      <path
        d="M114.3,152.3l38-38C144.4,130.9,130.9,144.4,114.3,152.3z M117.1,9.1l-108,108c0.8,1.6,1.7,3.2,2.7,4.8l110-110
	C120.3,10.9,118.7,10,117.1,9.1z M97.5,2L2,97.5c0.4,2,1,4,1.5,5.9l99.9-99.9C101.5,2.9,99.5,2.4,97.5,2z M80,160c2,0,4-0.1,5.9-0.2
	l73.9-73.9c0.1-2,0.2-3.9,0.2-5.9c0-0.6,0-1.2,0-1.9L78.1,160C78.8,160,79.4,160,80,160z M34.9,146.1c1.5,1,3,2,4.6,2.9L149,39.5
	c-0.9-1.6-1.9-3.1-2.9-4.6L34.9,146.1z M132.7,19.8L19.8,132.7c1.2,1.3,2.3,2.6,3.6,3.9L136.6,23.4C135.3,22.2,134,21,132.7,19.8z
	 M59.6,157.4l97.8-97.8c-0.5-1.9-1.1-3.8-1.7-5.7L53.9,155.6C55.8,156.3,57.7,156.9,59.6,157.4z M7.6,45.9L45.9,7.6
	C29.1,15.5,15.5,29.1,7.6,45.9z M80,0c-2.6,0-5.1,0.1-7.6,0.4l-72,72C0.1,74.9,0,77.4,0,80c0,0.1,0,0.2,0,0.2L80.2,0
	C80.2,0,80.1,0,80,0z"
      ></path>
    </svg>
    <svg width="228" height="228" class="orange">
      <circle cx="114" cy="114" r="114" />
    </svg>
    <div class="small">
      <h1>Small Dogs</h1>
      <p>
        Elit ut aliquam purus sit amet luctus venenatis. Ridiculus mus mauris
        vitae ultricies leo integer malesuada. Massa enim nec dui nunc mattis
        enim. Sagittis vitae et leo duis ut. Lacus suspendisse faucibus
        interdum.
      </p>
      <span>Images from </span>
      <a href="https://www.freepik.com/photos/dog" class="freepik">Freepik</a>
      <a href="https://nicepage.com/" class="more">Learn more</a>
    </div>
  </div>
</template>

<script>
export default {
  name: "SmallDogs",
};
</script>

<style lang="scss" scoped>
#small-dogs {
  .background {
    position: relative;
    background-color: #a552d6;
    height: 334px;
    width: 662px;
    margin: 531px 22px 0 auto;
  }

  img {
    position: absolute;
    height: 659px;
    width: 583px;
    object-fit: cover;
    margin: -722px auto 0 76px;
  }

  .pink {
    position: relative;
    fill: #df046f;
    margin: -189px auto 0 0;
  }

  .orange {
    fill: #f17c0e;
    margin: -1400px 0 auto 890px;
  }

  .small {
    position: relative;
    background-color: #fff;
    color: #111111;
    width: 440px;
    margin: -730px 80px -229px auto;
    padding: 30px 40px 55px 35px;

    h1 {
      font-family: "Montserrat", sans-serif;
      font-size: 2.25rem;
      font-weight: 700;
      line-height: 1.1;
      margin-top: 20px;
    }

    p,
    span,
    a {
      font-size: 1.125rem;
      font-weight: 300;
      line-height: 1.8;
      margin-top: 20px;
    }

    .freepik {
      color: #111111;
      border-bottom: 1px solid #000;
      font-weight: 700;
      cursor: pointer;

      &:hover {
        text-decoration: none;
      }
    }

    .more {
      display: block;
      color: #000;
      border: 2px solid #000;
      text-transform: uppercase;
      font-size: 1.125rem;
      font-weight: 700;
      margin: 35px 190px 0 0;
      padding: 10px 30px;
      cursor: pointer;

      &:hover {
        background-color: #000;
        color: #fff;
        text-decoration: none;
      }
    }
  }
}
</style>
