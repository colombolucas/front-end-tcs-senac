<template>
  <div id="home" class="container">
    <div class="row">
      <div class="col-sm-6">
        <img src="https://s1.static.brasilescola.uol.com.br/be/conteudo/images/imagem-em-lente-convexa.jpg" alt="">
      </div>
      <div class="col-sm-6">
        <h3>Quem somos</h3>
        <p>Uma empresa de tecnologia focada em ajudar na socialização de projetos sociais em Criciuma-Sc</p>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'HomeView',
  components: {
  },
};
</script>

<style scoped>
  img{
    width: 70%;
    max-width: 70%;
    border-radius: 5%;
  }

  h3, p{
    color: #504B43
  }
</style>
