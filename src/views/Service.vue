<template>
  <div id="services" class="page">
    <header>
      <img src="@/assets/PhotoFond/3.png" alt="Une personne travaillant sur son ordi">
      <h1>SERVICES</h1>
      <h5>
        <p data-aos="fade-up" data-aos-duration="1500" data-aos-once="true">D</p>
        <p data-aos="fade-up" data-aos-duration="1500" data-aos-delay="250" data-aos-once="true">E</p>
        <p data-aos="fade-up" data-aos-duration="1500" data-aos-delay="500" data-aos-once="true">V</p>
        <p data-aos="fade-up" data-aos-duration="1500" data-aos-delay="750" data-aos-once="true">I</p>
        <p data-aos="fade-up" data-aos-duration="1500" data-aos-delay="1000" data-aos-once="true">S</p> 
      </h5>
      <h5>
        <p data-aos="fade-up" data-aos-duration="1500" data-aos-delay="1250" data-aos-once="true">G</p>
        <p data-aos="fade-up" data-aos-duration="1500" data-aos-delay="1500" data-aos-once="true">R</p>
        <p data-aos="fade-up" data-aos-duration="1500" data-aos-delay="1750" data-aos-once="true">A</p>
        <p data-aos="fade-up" data-aos-duration="1500" data-aos-delay="2000" data-aos-once="true">T</p>
        <p data-aos="fade-up" data-aos-duration="1500" data-aos-delay="2250" data-aos-once="true">U</p>
        <p data-aos="fade-up" data-aos-duration="1500" data-aos-delay="2500" data-aos-once="true">I</p>
        <p data-aos="fade-up" data-aos-duration="1500" data-aos-delay="2750" data-aos-once="true">T</p>
        <p class="exclamation" data-aos="fade-up" data-aos-duration="1500" data-aos-delay="3000" data-aos-once="true">!</p>
      </h5>
      <router-link to="/contact" @click="scrollToForm()" title="Contact" data-aos="fade-in" data-aos-duration="2500" data-aos-delay="3000" data-aos-once="true">CONTACT</router-link>
    </header>
    <section>
      <h5 class="description" data-aos="fade-left" data-aos-duration="2000" data-aos-once="true">
        <span class="debut">RL WebProject :</span> Nous sommes actuellement une micro-entreprise de développement web basée à <span>Embrun</span>, au cœur des <span>Hautes Alpes</span>.<br>
        Nous vous proposons un service de <span>Création</span> ou de <span>Reprise</span> de Site Web avec l’assurance de respecter les <span>recommandations SEO de Google</span>. Nous travaillons en étroite collaboration avec des <span>designers freelance</span> et un <a class="subline" title="Cliquer ici pour voir ces photos" href="https://www.instagram.com/lenylaurenti/" target="__blank">photographe / vidéaste Professionnel</a>, ce qui nous permet de vous garantir un <span>design moderne</span> avec des <a title="Cliquer ici pour voir ces photos" href="https://www.instagram.com/lenylaurenti/" target="__blank">photos et des vidéos de grande qualité</a>.
      </h5>
      <div class="all-service">
        <img src="@/assets/PhotoFond/4.png" alt="Écouteur et Téléphone Apple" data-aos="slide-right" data-aos-duration="1500" data-aos-offset="300" data-aos-once="true" data-aos-delay="500">
        <img src="@/assets/PhotoFond/5.png" alt="Clavier Apple" data-aos="slide-left" data-aos-duration="1500" data-aos-offset="300" data-aos-once="true" data-aos-delay="500">
        <div class="single-service" data-aos="fade-right" data-aos-duration="2000" data-aos-once="true">
          <h4>Site Vitrine</h4>
          <h5>Un <span>site vitrine</span> désigne généralement un site qui a pour <span>seule vocation</span> de <span>présenter l’activité</span> d’une entreprise, d’une organisation, d’un produit, et autres <span>renseignements utiles</span> aux internautes, prospects et/ou clients, et qui <span>ne propose donc pas</span> de réaliser des <span>transactions en ligne</span>.<br>Si vous êtes désireux(se) de <span>gagner en notoriété</span> au travers d’internet, préférer donc un <span>site vitrine</span>.</h5>
        </div>
        <div class="single-service" data-aos="fade-left" data-aos-duration="2000" data-aos-once="true">
          <h4>OnePage</h4>
          <h5>Comme son nom l’indique c’est un site qui n'a qu'une <span>seule page</span> avec toutes les <span>informations importantes</span>.<br>
          Ce style de site est <span>recommandé pour</span> des sites <span>très événementiel</span> ou <span>temporaire</span>.</h5>
        </div>
        <div class="single-service" data-aos="fade-right" data-aos-duration="2000" data-aos-delay="800" data-aos-once="true">
          <h4>Site Sur Mesure</h4>
          <h5>La réalisation de votre <span>site web sur-mesure</span> vous permet de créer un <span>site unique</span> en <span>termes de fonctionnalités</span>. De cette manière, vous pouvez <span>présenter très précisément</span> vos <span>produits</span> ou <span>services</span> ou encore <span>automatiser certaines actions</span>.<br><br>
            &#10004;	Vous avez <span>carte blanche avec le designer</span> qui prendra en compte toutes vos demandes concernant <span>le design</span>, <span>les animations</span>, <span>les fonctionnalités</span>, etc…<br><br>
            &#10004;	Vous aurez également si besoin est, <span>les services</span> de notre <a title="Cliquer ici pour voir ces photos" class="subline" href="https://www.instagram.com/lenylaurenti/" target="__blank">Photographe/Vidéaste</a>.</h5>
        </div>
      </div>
    </section>
    <article>
      <h2>COMPÉTENCES</h2>
      <div class="competences">
        <div class="single-competence" data-aos="fade-up" data-aos-duration="2000" data-aos-once="true">
          <img src="@/assets/Icon/7.png" alt="Logo SASS">
          <p>SASS</p>
        </div>
        <div class="single-competence" data-aos="fade-up" data-aos-duration="2000" data-aos-delay="400" data-aos-once="true">
          <img src="@/assets/Icon/8.png" alt="Logo Vue.JS">
          <p>VUE.JS</p>
        </div>
        <div class="single-competence" data-aos="fade-up" data-aos-duration="2000" data-aos-delay="800" data-aos-once="true">
          <img src="@/assets/Icon/9.png" alt="Logo MongoDB">
          <p>MONGODB</p>
        </div>
        <div class="single-competence" data-aos="fade-up" data-aos-duration="2000" data-aos-delay="1200" data-aos-once="true">
          <img class="express" src="@/assets/Icon/10.png" alt="Logo Express.JS">
          <p>EXPRESS.JS</p>
        </div>
        <div class="single-competence" data-aos="fade-up" data-aos-duration="2000" data-aos-delay="1600" data-aos-once="true">
          <img src="@/assets/Icon/11.png" alt="Logo Node.JS">
          <p>NODE.JS</p>
        </div>
        <div class="single-competence" data-aos="fade-up" data-aos-duration="2000" data-aos-delay="2000" data-aos-once="true">
          <img src="@/assets/Icon/12.png" alt="Logo MySQL">
          <p>MYSQL</p>
        </div>
      </div>
    </article>
    <Footer/>
  </div>
</template>

<script>
import Footer from '@/components/Footer'

export default {
  name: 'Service',
  components: {
    Footer
  },
  methods: {
    scrollToForm() {
      window.scrollTo(0,2000);
    }
  }
}
</script>

<style lang="scss">
#services {
  height: 100vh;
  background: -webkit-gradient(linear, left top, right top, from(#2A2A2A), to(#010101));
  background: -o-linear-gradient(left, #2A2A2A, #010101);
  background: linear-gradient(to right, #2A2A2A, #010101);
  position: relative;
  top: -18vh;
  header {
    text-align: left;
    margin-left: 10vw;
    padding-top: 38vh;
    height: 100vh;
    img {
      z-index: 0;
      pointer-events: none;
      position: absolute;
      opacity: 0.57;
      top: 0;
      right: 0;
      height: 100vh;
    }
    h1 {
      font-weight: 600;
      font-size: 100px;
      color: #fff;
    }
    h5 {
      display: -webkit-box;
      display: -ms-flexbox;
      display: flex;
      font-weight: 300;
      font-size: x-large;
      p.exclamation {
        margin-bottom: 5vh;
        padding-left: 10px;
      }
    }
    a {
      padding: 8px 40px;
      font-weight: bold;
      border: 1px solid #fff;
      text-align: center;
      margin-left: 110pt;
    }
  }
  section {
    background: #0E0E0E;
    height: 162vh;
    h5 {
      text-align: left;
      font-weight: 300;
    }
    .description {
      padding: 3vh 0;
      line-height: 2.8vh;
      width: 60vw;
      height: 25vh;
      margin: auto;
      .debut {
        margin-right: 15px;
        font-size: large;
      }
      span {
        font-weight: bold;
      }
      a {
        font-weight: bold;
        &.subline {
          -webkit-text-decoration: underline 0.5px;
                  text-decoration: underline 0.5px;
        }
      }
    }
    .all-service {
      position: relative;
      width: 60vw;
      height: 110vh;
      margin: auto;
      display: -webkit-box;
      display: -ms-flexbox;
      display: flex;
      -webkit-box-orient: vertical;
      -webkit-box-direction: normal;
          -ms-flex-direction: column;
              flex-direction: column;
      -webkit-box-pack: justify;
          -ms-flex-pack: justify;
              justify-content: space-between;
      img {
        z-index: 10;
        position: absolute;
        height: 60vh;
        &:nth-child(1) {
          opacity: 0.30;
          top: 22vh;
          left: -20vw;
        }
        &:nth-child(2) {
          opacity: 0.25;
          height: 70vh;
          top: 46vh;
          right: -36vw;
        }
      }
      .single-service {
        z-index: 10;
        position: relative;
        width: 26vw;
        text-align: left;
        &:nth-of-type(2) {
          left: 34vw;
        }
        h4 {
          margin-top: 5vh;
          color: #89815F;
          margin-bottom: 7vh;
          font-size: x-large;
        }
        h5 {
          font-size: medium;
          line-height: 2.5vh;
          span, a {
            font-weight: bold;
            &.subline {
              text-decoration: underline;
            }
            &.bold {
              font-weight: 700;
            }
          }
        }
      }
    }
  }
  article {
    height: 82vh;
    h2 {
      font-weight: 600;
      margin-top: 2vh;
      color: #89815F;
      font-size: xxx-large;
    }
    .competences {
      margin: auto;
      width: 60vw;
      display: -webkit-box;
      display: -ms-flexbox;
      display: flex;
      -ms-flex-wrap: wrap;
          flex-wrap: wrap;
      -webkit-box-pack: justify;
          -ms-flex-pack: justify;
              justify-content: space-between;
      .single-competence {
        position: relative;
        width: 20vw;
        margin-top: 15vh;
        img {
          height: 10vh;
          &.express {
            position: absolute;
            right: 2.5vw;
            height: 20vh;
          }
        }
        &:nth-of-type(4) {
          p {
            position: absolute;
            right: 6.8vw;
            bottom: 0;
          }
        }
      }
    }
  }

  //***** Max-width *****//

  @media screen and(max-width: 1366px) {
    section {
      .all-service {
        img {
          height: 55vh;
          &:nth-child(1) {
            top: 12vh;
            left: -20vw;
          }
          &:nth-child(2) {
            height: 60vh;
            top: 52vh;
            right: -40vw;
          }
        }
      }
    }
  }
  @media screen and(max-width: 1024px) {
    header {
      img {
        height: 60vh;
        top: 20vh;
      }
    }
    section {
      .description {
        width: 85vw;
      }
      .all-service {
        img {
          height: 40vh;
          &:nth-child(1) {
            top: 12vh;
          }
          &:nth-child(2) {
            height: 50vh;
            top: 52vh;
            right: -40vw;
          }
        }
        .single-service {
          width: 50vw;
          &:nth-of-type(2) {
            left: 20vw;
          }
        }
      }
    }
  }
  @media screen and(max-width: 768px) {
    header {
      img {
        top: 30vh;
      }
      h1 {
        font-size: 70px;
      }
    }
    article {
      h2 {
        font-size: xx-large;
      }
    }
  }
  @media screen and(max-width: 540px), (max-height: 540px) {
    header {
      img {
        height: 60vh !important;
        top: 30vh !important;
      }
      h1 {
        font-size: xxx-large;
      }
      h5 {
        font-size: large;
      }
    }
    section {
      height: 190vh !important;
      .description {
        height: 40vh;
        font-size: x-small;
        .debut {
          font-size: medium;
        }
      }
      .all-service {
        height: 115vh;
        .single-service {
          h4 {
            font-size: medium;
          }
          h5 {
            font-size: small;
          }
        }
      }
    }
    article {
      height: 105vh;
      .competences {
        .single-competence {
          width: 25vw;
        }
      }
    }
  }
  @media screen and(max-width: 414px), (max-height: 414px) {
    header {
      img {
        height: 50vh;
        right: -25vw;
      }
      h1 {
        font-size: xx-large;
      }
      h5 {
        font-size: medium;
      }
      a {
          font-size: x-small !important;
          padding: 5px 30px;
          margin-left: 30pt;
        }
    }
    section {
      height: 225vh !important;
      .all-service {
        img {
          height: 40vh;
          &:nth-child(1) {
            top: 22vh;
          }
          &:nth-child(2) {
            height: 40vh;
            top: 110vh;
            right: -55vw;
          }
        }
      }
    }
    article {
      h2 {
        font-size: x-large;
      }
      .competences {
        .single-competence {
          width: 22vw;
          p {
            font-size: small;
          }
          img {
          height: 7vh;
        }
        }
      }
    }
  }
  @media screen and(max-width: 375px) {
    header {
      img {
        height: 40vh !important;
        top: 50vh !important;
      }
    }
    section {
      .all-service {
        img {
          height: 35vh;
          &:nth-child(1) {
            top: 40vh;
            left: -25vw;
          }
          &:nth-child(2) {
            height: 40vh;
            right: -55vw;
          }
        }
        .single-service {
          width: 58vw;
        }
      }
      .description {
        font-size: xx-small;
        .debut {
          font-size: small;
        }
      }
    }
    article {
      height: 100vh !important;
    }
  }

  //***** Max-height *****//

  @media screen and(max-height: 768px) {
    header {
      img {
        height: 80vh;
        top: 20vh;
      }
    }
  }
  @media screen and(max-height: 414px) {
    header {
      img {
        height: 70vh !important;
        top: 20vh !important;
        right: 0;
      }
    }
    section {
      .all-service {
        img {
          height: 60vh;
          &:nth-child(1) {
            top: 22vh;
          }
          &:nth-child(2) {
            height: 70vh;
            top: 68vh;
            right: -35vw;
          }
        }
        .single-service {
          h5 {
            line-height: 4vh;
          }
        }
      }
    }
  }
}
</style>