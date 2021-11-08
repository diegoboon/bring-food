<template>
  <div id="app">
    <div class="navbar-container"> <!-- Menú inferior (TABS) -->
      <div class="navbar-content">
        <router-link to="/">
          <i class='bx bx-home-alt bx-sm'></i>
        </router-link>
        <router-link to="/historial">
          <i class='bx bx-message-square-detail bx-sm'></i>
        </router-link>
        <router-link to="/perfil">
          <i class='bx bx-user bx-sm'></i>
        </router-link>
        
      </div>
    </div>
    <router-view />
  </div>
</template>
<style lang="less">



.header {
  .logo{
    width: 200px;
    margin-left: 18%;
    margin-bottom: -50px;
  }
  .banner{
    width: 100%;
    border-radius: 30px;
    margin-top: 13px;
  }
  
  .combo-header {
    background-color: rgba(74, 174, 84);
    color: white;
    padding: 20px;
    border-radius: 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-top: 20px;
    .img {
      width: 50%;
      img {
        width: 100%;
        object-fit: cover;
        border-radius: 10px;
      }
    }
    .text {
      width: 50%;
      h3 {
        font-weight: 400;
      }
      p {
        font-weight: 300;
      }
    }
  }
  .input {
    display: flex;
    position: relative;
    align-items: center;
    margin-top: 15px;
    margin-bottom: 15px;
    input {
      width: 100%;
      background-color: rgba(250, 248, 248);
      border: 0px;
      outline: none;
      padding: 10px;
      padding-left: 30px;
      border-radius: 10px;
    }
    .icon-input {
      position: absolute;
      margin-left: 10px;
    }
  }
  .title {
    margin-top: 60px;
    font-weight: 350;
  }
}

.categorias{
  width: 50px;
}
.navbar-container {
  background-color: #fff;
  width: 100%;
  position: fixed;
  bottom: 0;
  .navbar-content {
    padding: 20px;
    display: flex;
    justify-content: space-between;
    a {
      color: rgba(163, 163, 163);
      &.router-link-exact-active {
        color: rgba(255, 131, 62);
      }
    }
  }
}

#app, #home, #about {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
* {
  font-family: 'Josefin Sans', sans-serif;
  margin: 0px;
  padding: 0px;
}



h2 {
  font-weight: 400;
}

.precio{
  font-size: 1.5rem;
  color:#ff7300;
  text-shadow: 1.5px 0 0 #fff, -1.5px 0 0 #fff, 0 1.5px 0 #fff, 0 -1.5px 0 #fff, 1px 1px #fff, -1px -1px 0 #fff, 1px -1px 0 #fff, -1px 1px 0 #fff;
}
.home, .about {
  
  .scroll-menu-top {
    .scroll-content-top {
      display: flex;
    }
  }
  .top-products {
    background-color: rgba(250, 248, 248);
    padding: 10px;
    border-radius: 10px;
    .top-products-img {
      img {
        width: 50%;
      }
    }
    position: relative;
    i {
      position: absolute;
      right: 0;
      bottom: 0;
      padding: 10px;
      color: white;
      border-radius: 50px;
      background-color: rgba(74, 174, 84);
      margin: 5px;
    }
    min-width: 150px;
    .top-products-text {
      margin-top: 10px;
      .top-products-price {
        color: rgba(255, 131, 62);
      }
      .top-products-title {
        color: rgba(47, 47, 47);
      }
    }
  }
  margin: 20px;
  .scroll-menu {
    margin-top: 10px;
    .scroll-content {
      display: flex;
      overflow-y: auto;
      &::-webkit-scrollbar {
        display: none;
      }
      .avatar {
        background-color: rgba(250, 248, 248);
        padding: 20px;
        border-radius: 10px;
        margin: 2px;
        i {
          color: rgba(255, 131, 62);
        }
      }
    }
  }
}
.content{
  border-top: 1px solid rgba(163, 163, 163, 0.5);
  border-bottom: 1px solid rgba(163, 163, 163, 0.5);

  
}


.c-details span {
    font-weight: 300;
    font-size: 13px
}

.icon {
    width: 50px;
    height: 50px;
    
    border-radius: 15px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 39px
}

.badge span {
    background-color: #fffbec;
    width: 60px;
    height: 25px;
    padding-bottom: 3px;
    border-radius: 5px;
    display: flex;
    color: #fed85d;
    justify-content: center;
    align-items: center
}

.greene span {
    background-color: #edfdf0;
    width: 89px;
    height: 24px;
    font-weight: bold;
    padding-bottom: 3px;
    border-radius: 5px;
    display: flex;
    color: #00f77b;
    justify-content: center;
    align-items: center
}

.progress {
    height: 10px;
    border-radius: 10px
}


.progress div {
    background-color: rgb(0, 255, 157);
}


.text1 {
    font-size: 14px;
    font-weight: 600
}

.text2 {
    color: #a5aec0
}

[class*="icon-"] {
    font-size: 20px;
    color: #a5aec0;
    display: inline-block;
}
.icon-l{
  background: url(assets/img/logo.png) no-repeat;
}


</style>
