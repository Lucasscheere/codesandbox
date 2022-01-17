<template>
  <header id="header">
    <div class="icone" id="icone">
      <a href="/"><i class="fas fa-bars"></i></a>
    </div>

    <div class="marca">
      <a href="/"><span class="titulo">_Falha</span></a>
      <span class="label"
        >O site de testes para <strong>novos devs</strong></span
      >
    </div>

    <div class="sociais">
      <button name="facebook" id="facebook">
        <i class="fab fa-facebook-f"></i><span>Curtir</span>
      </button>
      <button name="twitter" id="twitter">
        <i class="fab fa-twitter"></i><span>Seguir</span>
      </button>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style scoped>
header {
  background-color: #3199DC;
  height: 90px;
  margin-bottom: 5px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

/*===========ÍCONE MENU SVG=========*/
.icone a {
  font-size: 2em;
  margin-left: 20px;
  text-decoration: none;
  color: #283c4f;
}

/*==============DIV HEADER (MARCA E DESCRIÇÃO=================*/
.marca a {
  display: flex;
  justify-content: center;
  align-items: center;
}

/*=============MARCA DA EMPRESA NO HEADER================*/
.titulo {
  background-color: #283c4f;
  color: #ddd;
  text-align: center;
  font-size: 2em;
  padding: 20px;
  width: 150px;
  border-radius: 5px;
  transform: rotate(5deg);
  font-weight: 600;
}

/*===========DESCRIÇÃO NO HEADER==============*/
.label {
  color: #ddd;
  display: none;
  margin-left: 20px;
}

header div button {
  width: 90px;
  justify-content: center;
  align-items: center;
  border-radius: 5px;
  border: none;
}

header div button span {
  margin-left: 5px;
  text-transform: uppercase;
  font-size: 0.6rem;
}

#facebook {
  display: none;
  color: #3b5998;
}

#facebook:hover {
  filter: brightness(90%);
  cursor: pointer;
}

#twitter {
  display: none;
  color: #00acee;
}

#twitter:hover {
  filter: brightness(90%);
  cursor: pointer;
}

@media (min-width: 801px) {
  .label {
    display: flex;
  }

  #facebook,
  #twitter {
    display: flex;
    padding: 5px;
  }

  .sociais {
    width: 200px;
    display: flex;
    justify-content: space-around;
    margin-right: 15px;
  }

  .marca {
    display: flex;
    align-items: center;
  }
}
</style>
