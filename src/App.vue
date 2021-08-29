<template>
    <div id="nav">
      <div class="logo">
        <router-link to="/"><p>RL WebProject</p></router-link>
      </div>
      <div class="nav-bar">
        <router-link to="/portefolio">Portefolio</router-link>
        <router-link to="/services">Services</router-link>
        <router-link to="/contact">Contact</router-link>
      </div>
      <i @click="scrollToTop()" id="up" class="fas fa-chevron-up" title="Retour vers le Haut"></i>
    </div>
    <transition name="router-anim">
      <router-view/>
    </transition>
</template>

<script>

export default {
  name: 'Nav',
  methods: {
    scrollToTop() {
      window.scrollTo(0,0);
    }
  }
}
</script>

<style lang="scss">
@-webkit-keyframes going {
  from {
    -webkit-transform: translateX(0);
            transform: translateX(0);
  }
  to {
    -webkit-transform: translateX(-70px);
            transform: translateX(-70px);
    opacity: 0;
  }
}
@keyframes going {
  from {
    -webkit-transform: translateX(0);
            transform: translateX(0);
  }
  to {
    -webkit-transform: translateX(-70px);
            transform: translateX(-70px);
    opacity: 0;
  }
}
@-webkit-keyframes coming {
  from {
    -webkit-transform: translateX(-70px);
            transform: translateX(-70px);
    opacity: 0;
  }
  to {
    -webkit-transform: translateX(0);
            transform: translateX(0);
    opacity: 1;
  }
}
@keyframes coming {
  from {
    -webkit-transform: translateX(-70px);
            transform: translateX(-70px);
    opacity: 0;
  }
  to {
    -webkit-transform: translateX(0);
            transform: translateX(0);
    opacity: 1;
  }
}
.page {
  position: fixed;
  width: inherit;
}
.router-anim-enter-active {
  -webkit-animation: coming 1s;
          animation: coming 1s;
  opacity: 0;
}
.router-anim-leave-active {
  -webkit-animation: going 1s;
          animation: going 1s;
}
#app {
  font-family: 'Montserrat', sans-serif;
  text-align: center;
  color: #fff;
    i.fa-chevron-up {
      cursor: pointer;
      padding: 10px 10px;
      z-index: 50;
      position: fixed;
      bottom: 5vh;
      right: 5vh;
      border-radius: 5px;
      background: rgba(255, 255, 255, 0.548);
      font-size: large;
      color: #000;
    }
}

#nav {
  @font-face{
    font-family:"alphacentauri-medium";
    src:url("https://dafonttop.com/wp-data/a/316/12316/file/Alphacentauri-MVY4p.ttf") format("woff"),
        url("https://dafonttop.com/wp-data/a/316/12316/file/Alphacentauri-MVY4p.ttf") format("opentype"),
        url("https://dafonttop.com/wp-data/a/316/12316/file/Alphacentauri-MVY4p.ttf") format("truetype");
  }
  position: relative;
  background: transparent;
  height: 18vh;
  width: 100%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding-left: 4vw;
  padding-right: 5vw;
  .logo {
    z-index: 10;
    p {
      color: #89815F;
      font-family: 'AlphaCentauri';
      font-size: x-large;
      letter-spacing: 10pt;
    }
  }
  .nav-bar {
    z-index: 20;
    a {
      font-weight: bold;
      color: #fff;
      margin-left: 100pt;
      padding-bottom: 1vh;
      border: 0px solid transparent;
      transition: border 1s .1s;
      &.router-link-exact-active {
        border-bottom: 1px solid #89815F;
        
      }
    }
  }

  //***** Max-width *****//

  @media screen and(max-width: 1024px) {
    .nav-bar {
      a {
        margin-left: 50pt;
      }
    }
  }
  @media screen and(max-width: 768px), (max-height: 768px) {
    flex-direction: column;
    justify-content: center !important;
    .logo, .nav-bar {
      width: 100%;
    }
    .logo {
      margin-bottom: 4vh;
      p {
        font-size: xx-large;
        color: #a39555;
      }
    }
    .nav-bar {
      a {
        margin-left: 25pt;
        margin-right: 25pt;
      }
    }
  }
  @media screen and(max-width: 540px), (max-height: 540px) {
    .logo {
      margin-top: 2vh;
      p {
        font-size: x-large;
      }
    }
  }
  @media screen and(max-width: 414px), (max-height: 414px) {
    .logo {
      p {
        font-size: large;
      }
    }
    .nav-bar {
      display: flex;
      justify-content: space-between;
      a {
        font-size: small;
        margin: 0;
      }
    }
  }
  @media screen and(max-width: 375px), (max-height: 375px) {
    .nav-bar {
      a {
        font-size: x-small;
      }
    }
  }
}
</style>
