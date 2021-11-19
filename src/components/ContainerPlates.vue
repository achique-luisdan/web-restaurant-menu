<template>
  <div class="container-plates">
    <div class="row">
      <article class="three columns">

        <header>
          <div class="row-circle">
          <div class="circle-price">
           <h5>5 $</h5>
          </div>
          </div>
          <img src="../assets/imgs/01.png" alt="">
          <h3>Lorem ipsum</h3>
        </header>
        <section>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam.
          </p>
        </section>
      </article>
        <article class="three columns">

        <header>
          <div class="row-circle">
          <div class="circle-price">
           <h5>5 $</h5>
          </div>
          </div>
          <img src="../assets/imgs/02.png" alt="">
          <h3>Lorem ipsum</h3>
        </header>
        <section>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam.
          </p>
        </section>
      </article>
        <article class="three columns">

        <header>
          <div class="row-circle">
          <div class="circle-price">
           <h5>5 $</h5>
          </div>
          </div>
          <img src="../assets/imgs/03.png" alt="">
          <h3>Lorem ipsum</h3>
        </header>
        <section>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam.
          </p>
        </section>
      </article>

        <article class="three columns">

        <header>
          <div class="row-circle">
          <div class="circle-price">
           <h5>5 $</h5>
          </div>
          </div>
          <img src="../assets/imgs/01.png" alt="">
          <h3>Lorem ipsum</h3>
        </header>
        <section>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam.
          </p>
        </section>
      </article>
      
    </div>
  </div>
</template>

<script>
export default {
  name: "ContainerPlates",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
header, article {
  text-align: center;
}
img {
  width: 70%;
  border: white solid 8px;
}
h3, h5 {
  margin: 0px;
  padding: 0px;
}

.container-plates {
  padding: 2%;
  padding-top: 6%;
}

h3 {
  font-size: 30px;
  font-weight: bold;
  margin-bottom: 5px;
  font-family: 'Oleo Script Swash Caps', cursive;
}
h3, h5, p {
  color: white
}

.circle-price {
  border-radius:45%;
  width: 60%;
  max-width: 100px;
  margin: auto;
  border: white solid 2.5px;
  padding: 6px;
  margin-bottom: 5px;
  margin-top: -25px;
  position: absolute;
  float: right;
  background: rgb(61, 60, 59);
}

.circle-price h5 {
  border-radius:45%;
  margin: auto;
  border: white dotted 2px;
  background: rgb(94, 93, 93);
  font-family: 'Oleo Script Swash Caps', cursive;
}

.row-circle {
  text-align: center;
  margin: auto;
  display: table;
}
</style>
