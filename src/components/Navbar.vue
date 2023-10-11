<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-md-6">
        <ul>
          <li>Pagina Inicial</li>
          <li>Categorias</li>
          <li>Contribua</li>
          <li>Acessibilidade</li>
        </ul>
      </div>
      <div class="col-md-6 d-flex align-items-center justify-content-center">
        <div>
          <img class="logo" src="../assets/logo.svg" alt="">
        </div>
        <div>
          <input type="search" placeholder="O que você procura?">
        </div>
        <img src="../assets/search-icon.svg" alt="">
      </div>
    </div>
    <div class="row section">
      <div class="col-md-4">
        <img class="ps-5 people" src="../assets/people.svg" alt="people">
      </div>

      <div class="col-md-8">
        <h1 class="text-light">PELO DIREITO DE SE COMUNICAR!</h1>
        <h4 class="text-light my-5">Sinalário: o aplicativo de inclusão que te ensina lingua de sinais</h4>
        <p class="text-light">
          Funciona como uma enciclopédia com os sinais em LIBRAS, apresentando os gestuais, <br> datilologia, expressões faciais e configuração de mão. Além de apresentar uso em frases. 
        </p>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.row {
  background-color: #FFFFFF !important;
  width: 100vw;
  display: flex;
  align-items: center !important;
}

ul {
  list-style: none;
  display: flex;
  align-items: center;

  li {
    padding-top: 15px;
    margin: 10px;
    margin-left: 50px;
  }
}

.logo {
  width: 60%;
}

input{
  border: none;
}

.section{
  background-color: #1c4c9c !important;
  padding: 110px  0px;
}
.people{
  width: 91%;
}
</style>