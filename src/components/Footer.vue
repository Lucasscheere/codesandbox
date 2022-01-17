<template>
  <footer class="footer">
    <div class="marca">_Falha</div>
    <div class="copyright">
      Copyright Falha de S. Paulo. Todos os direitos reservados. É proibida a
      reprodução do conteúdo desta página em qualquer meio de comunicação,
      eletrônico ou impresso, sem autorização escrita da Falhapress
      <a href="mailto:pesquisa@falhapress.com.br">
        (pesquisa@falhapress.com.br)
      </a>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
  components: {},
};
</script>

<style scoped>
.footer {
  background-color: #283c4f;
  display: flex;
  justify-content: space-around;
  align-items: center;
  color: #ddd;
}

.marca {
  font-size: 2.3em;
  display: none;
}

.copyright {
  padding: 25px 10px;
}
footer div a {
  color: inherit;
}

@media (min-width: 801px) {
  .copyright {
    font-size: 0.9em;
    height: 100px;
    padding-right: 100px;
  }

  .marca {
    display: block;
    padding: 0 100px;
  }
}
</style>