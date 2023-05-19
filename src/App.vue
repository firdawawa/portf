<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com">
  <link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,400;0,700;0,800;0,900;1,400;1,700;1,800;1,900&display=swap" rel="stylesheet">

  <div class="container">
      <div class="header">
      <img class="logo" src="./assets/img/logo.png" alt="Logo">
      <div class="nav-head">
        <a id="ahead1" href="#aboutme">About Me</a>
        <a id="ahead" href="#portfolio">Portfolio</a>
        <a id="ahead" href="#contact">Contact</a>
      </div>  
    </div>

    <div class="body-container">
    <div class="body">
      <div id="aboutme">
        <div class="namepict">
          <div class="namedesc">
            <div class="nama">FIRDAUSI BAIQ ARDANA</div>
            <h5>Undergraduate student majoring Information Technology in Brawijaya University. Having interest in tech especially design. Participate actively in college activity, but still holding on academic class greatly. Able to hold perfectly on problem solving, meticulous, ardent, and critical thinking.</h5>
          </div>
          <img class="foto-profil" src="./assets/img/profil.png" alt="Profile">
        </div>
        <div class="skill">
          <div class="skillhead">Skill</div>
          <div class="skilldesc">
            <div class="skillleft">
              <h5>Design Thinking</h5>
              <h5>UX Research</h5>
              <h5>Designing</h5>
              <h5>Prototyping</h5> 
            </div>
            <div class="skillright">
              <h5>Wireframe</h5>
              <h5>HTML/CSS</h5> 
              <h5>JavaScript</h5> 
            </div> 
          </div>
        </div>
        <div class="experience">
          <div class="head">Experience</div>
            <div class="tabel-container">
              <table>
                <tr class="table-content"><td>RAION</td></tr>
                <tr class="table-content"><td>RAION</td></tr>
                <tr class="table-content"><td>Nuri</td></tr>
              </table>
              <table>
                <tr class="table-content"><td>|</td></tr>
                <tr class="table-content"><td>|</td></tr>
                <tr class="table-content"><td>|</td></tr>
              </table>
              <table>
                <tr class="table-content"><td>UI/UX App Designer</td></tr>
                <tr class="table-content"><td>UI/UX App Designer Intern</td></tr>
                <tr class="table-content"><td>UI/UX Designer</td></tr>
              </table>
              <table>
                <tr class="table-content"><td>|</td></tr>
                <tr class="table-content"><td>|</td></tr>
                <tr class="table-content"><td>|</td></tr>
              </table>
              <table>
                <tr class="table-content"><td>April 2023 - Present</td></tr>
                <tr class="table-content"><td>March - April 2023</td></tr>
                <tr class="table-content"><td>January 2023</td></tr>
              </table>
            </div>
          </div>
        </div>

      <div id="portfolio">
        <div class="port-container">
          <div class="porthead">Portfolio</div>
          <div class="sharejoy">
            <div class="sharehead">
              <img class="sharelogo" src="./assets/img/sharejoy.png" alt="ShareJoy">
              <div class="sharetitle">ShareJoy</div>
            </div>
            <div class="share-content">
              <h5>Social purpose platform that allows the user to donate money or things. With main target user for teenagers and millennials, to rise their social empathy with others. Beside that, this app can help them who have struggle with unused things the have to bring more goodness through donation.</h5>
              <img class="phoneshare" src="./assets/img/dev1.png" alt="phone sharejoy">
            </div>
            <div class="shareui">
              <img class="shareuides" src="./assets/img/shareui1.png">
              <img class="shareuides" src="./assets/img/shareui2.png">
              <img class="shareuides" src="./assets/img/shareui3.png">
              <img class="shareuides" src="./assets/img/shareui4.png">
            </div>
          </div>
          <div class="studyhive">
            <div class="studyhead">
              <img class="studylogo" src="./assets/img/studyhive.png" alt="ShareJoy">
              <div class="studytitle">StudyHive</div>
            </div>
            <div class="study-content">
              <img class="phonestudy" src="./assets/img/dev2.png" alt="phone sharejoy">
              <h5>IT course and training platform, where the user can register their participants to take the class and build excellent portfolio as an attempt to prepare their career. The main target participants are they who have difficulties on economic status or have disability issue. Hope through this app, we can give the chance and portion to them equal with other people who are luckier.</h5>
            </div>
            <div class="studyui">
              <img class="studyuides" src="./assets/img/studyui1.png">
              <img class="studyuides" src="./assets/img/studyui2.png">
              <img class="studyuides" src="./assets/img/studyui3.png">
              <img class="studyuides" src="./assets/img/studyui4.png">
            </div>
          </div>
        </div>
      </div>

      <div id="contact">
        <div class="lets">LET’S HAVING WORK TOGETHER</div>
        <div class="contact-container">
          <div class="contacthead">Contact Me</div>
          <div class="wa">
            <img class="wa-icon" src="./assets/img/wa.png">
            <a class="wa-name" href="https://wa.me/6282330014557" target="_blank">082330014557</a>
          </div>
          <div class="gmail">
            <img class="gmail-icon" src="./assets/img/gmail.webp">
            <a class="gmail-name" href="mailto: firdaardana0111@gmail.com" target="_blank">firdaardana0111@gmail.com</a>
          </div>
          <div class="linkedin">
            <img class="linkedin-icon" src="./assets/img/linkedin.png">
            <a class="linkedin-name" href="https://www.linkedin.com/in/firdaardana/" target="_blank">https://www.linkedin.com/in/firdaardana/</a>
          </div>
        </div>
      </div>
    </div>
  </div>

    <div class="footer">
      <div class="footer-content">All Rights Reserved | 2023</div>
    </div>
  </div>
  <!-- <header>
    <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />

      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView /> -->
</template>

<style scoped>
/* header {
  line-height: 1.5;
  max-height: 100vh;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
  margin-top: 2rem;
}

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }

  nav {
    text-align: left;
    margin-left: -1rem;
    font-size: 1rem;

    padding: 1rem 0;
    margin-top: 1rem;
  }
} */
</style>
