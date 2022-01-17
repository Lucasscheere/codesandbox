<template>
  <div class="lastnews">
    <div>
      <img
        src="https://media.istockphoto.com/photos/little-child-swinging-on-a-wooden-swing-picture-id1087409318"
      />
      <p>Cacildis</p>
    </div>
    <div>
      <img
        src="https://mundocultura.com.br/wp-content/uploads/2021/03/capas-1-1024x576.png"
      />
      <p>abertis</p>
    </div>
    <div>
      <img
        src="https://sfia-online.org/pt/assets/images-for-articles/bigstock-software-developer-freelancer-321565021.jpg/@@images/3c14b3dc-5812-42ce-b48d-e88c4d7aecce.jpeg"
      />
      <p>amistosis</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "LastNews",
};
</script>

<style scoped>
@media (min-width: 801px) {
  .lastnews {
    display: flex;
    justify-content: space-between;
  }
  .lastnews div {
    margin: 0 10px;
  }
}

div {
  position: relative;
}
img {
  max-width: 100%;
  height: 55vh;
  width: 100%;
  margin-top: 50px;
}

p {
  color: #ddd;
  width: 30%;
  padding: 5px;
  text-align: left;
  bottom: 10%;
  background-color: #E55440;
  position: absolute;
  text-transform: uppercase;
}
</style>