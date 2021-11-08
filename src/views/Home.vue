<template>
  <div class="home">
    <div class="header">
      <img class="logo" src="../assets/img/logo2.png">
      <h2 class="title">Hola <b>Diego!</b></h2>
      <div class="input">
        <input type="text" placeholder="¿Que deseas pedir hoy?... " />
        <div class="icon-input">
          <i class="bx bx-search"></i>
        </div>
      </div>
      <div >
        <img class="banner" src="../assets/img/banner.jpg">
      </div>
      <div class="combo-header">
        <div class="text">
          <h3>Combo Lunes</h3>
          <p>Hamburguesa de pollo + Coca-cola <br> por <strong class="precio">$159</strong></p>
        </div>
        <div class="img">
          <img
            src="https://images.unsplash.com/photo-1591722937570-370bf646acc7?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=750&q=80"
            alt=""
          />
        </div>
      </div>
    </div>
    <div class="scroll-menu">
      <div class="scroll-content">
        <div  class="avatar">
          <i><img class="categorias" src="../assets/img/aros-de-cebolla.png" alt=""></i>
          <p>Frituras</p>
        </div>
        <div  class="avatar">
          <i><img class="categorias" src="../assets/img/coca.png" alt=""></i>
          <p>Refresco</p>
        </div>
        <div  class="avatar">
          <i><img class="categorias" src="../assets/img/taco.png" alt=""></i>
          <p>Comida</p>
        </div>
        <div  class="avatar">
          <i><img class="categorias" src="../assets/img/word.png" alt=""></i>
          <p>Copias</p>
        </div>
      </div>
    </div>
    <h2>Productos más vendidos</h2>
    <div class="scroll-menu">
      <div class="scroll-content">
        <div :key="index" v-for="(item, index) in 10" class="top-products">
          <div class="top-products-img">
            <img src="../assets/img/doritos.png"
              alt=""/>
          </div>
          

          <div class="top-products-text">
            <div class="top-products-title">Doritos</div>
            <div class="top-products-price">$17.50</div>
          </div>

          <i class="bx bx-plus-medical"></i>
        </div>
        
      </div>
    </div>
  </div>
</template>


