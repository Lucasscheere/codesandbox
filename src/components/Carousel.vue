<template>
  <div class="divcarousel">
    <carousel
      :per-page="1"
      :mouse-drag="false"
      :autoplay="true"
      :loop="true"
      :speed="2000"
    >
      <slide>
        <img class="img" src="https://source.unsplash.com/random " />
        <p>Cacilds vidis litro abertis</p>
        <h2 class="titulo">Manduma pindureta quium dia nois paga</h2>
      </slide>
      <slide>
        <img class="img" src="https://source.unsplash.com/user/erondu" />
        <p>Cacilds vidis litro abertis</p>
        <h2 class="titulo">Manduma pindureta quium dia nois paga</h2>
      </slide>
    </carousel>
  </div>
</template>

<script>
import { Carousel, Slide } from "vue-carousel";
export default {
  components: {
    Carousel,
    Slide,
  },
};
</script>

<style>
.divcarousel {
  position: relative;
}

.img {
  max-width: 100%;
  height: 55vh;
  width: 100%;
  margin-top: 50px;
}

div h2 {
  text-align: left;
  margin-left: auto;
  margin-right: auto;
}

p {
  color: #ddd;
  width: 60%;
  padding: 5px;
  text-align: left;
  bottom: 20%;
  background-color: #3199DC;
  position: absolute;
  text-transform: uppercase;
}

.titulo {
  color: #283c4f;
}

@media (min-width: 801px) {
  p {
    width: 20%;
    bottom: 30%;
  }

  div h2 {
    bottom: 50%;
  }
}
</style>