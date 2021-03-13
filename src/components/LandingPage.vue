<template>
  <v-row>
    <v-col sm="12" md="3" class="avatar-section text-center pl-8 pr-8">
      <v-img src="../assets/avatar.jpg" class="my-3" height="144" width="144"
        style="border-radius: 50%; margin: 0 auto;"
      />
      <h3>
        <strong style="padding: 0 4px;">Code Guardian</strong>
        /
        <strong style="padding: 0 4px;">IT Artist</strong>
      </h3>
      <p>My thirst of knowledge made me discover a lot of wonders,.</p>
      <p>I can handle any <strong>design</strong> tool and I master <strong>the art of code</strong>. </p>
      <p>I also make music as a hobby.</p>
    </v-col>

    <v-col sm="12" md="9" cols="12" class="main-container pl-8 pr-4">
      <section id="mastered-technos" class="mastered-technos">
        <h2>Code Guardian</h2>
        <h3>The journey consists in being at the right place at the right moment</h3>
        <!-- <div id="mozaicTrigger"></div> -->
        <div class="container">
          <div id="journey" class="row journey">
            <article class="col s12 m6 offset-m3">
              <div class="card skill-tile dark-nice nomaxhskill">
              <div class="card-content">
                <h4>Lead developer at <a href="https://timbtrack.com/"><abbr title="International Business Renaissance">IBR</abbr></a>, from 2019 to now</h4><img src="<?= IMG.'/ico/logo-timbtrack-block-white.png' ?>" alt="Timbtrack" class="ico small">
              </div>
              </div>
            </article>
            <article class="col s12 m6">
              <div class="card skill-tile dark nomaxhskill">
                <div class="card-content">
                  <h4>Mixed all knowledge at <a href="https://becode.org/">BeCode</a>, 2017-2018</h4><img class="ico small" src="<?= IMG.'ico/becodeorg.png' ?>" alt="BeCode">
                </div>
              </div>
            </article>
            <article class="col s12 m6">
              <div class="card skill-tile dark nomaxhskill">
                <div class="card-content">
                  <h4>Studied at <a href="https://www.heaj.be/">Albert Jacquard</a>, 2013 to 2016</h4><img class="ico small" src="<?= IMG.'ico/heaj.png' ?>" alt="HEAJ">
                </div>
              </div>
            </article>
          </div>
        </div>
        <h3 class="clearfix">1. Start from scratch</h3>
        <div class="container">
          <div id="scratch" class="row learned">
            <article class="col s12 m4">
              <div class="card skill-tile">
              <div class="card-content">
                <i class="devicon-html5-plain devicon big"></i><span class="alt-tile"><strong>HTML5</strong> warrior</span>
              </div>
              </div>
            </article>
            <article class="col s12 m4">
              <div class="card skill-tile">
              <div class="card-content">
                <i class="devicon-css3-plain devicon big"></i><span class="alt-tile"><strong>CSS3</strong> wizard</span>
              </div>
              </div>
            </article>
            <article class="col s12 m4">
              <div class="card skill-tile">
              <div class="card-content">
                <i class="devicon-javascript-plain devicon big"></i><span class="alt-tile"><strong>JavaScript</strong> writer</span>
              </div>
              </div>
            </article>
          </div>
        </div>
        <h3 class="clearfix">2. Use frameworks</h3>
        <div class="container">
          <div id="frameworks" class="row learned">
            <article class="col s12 m4">
              <div class="card skill-tile">
              <div class="card-content">
                <i class="fab fa-vuejs devicon big"></i><span class="alt-tile">Lead developer on multiple <strong>VueJS</strong> <a href="https://timbtrack.com/">projects</a></span>
              </div>
              </div>
            </article>
            <article class="col s12 m4">
              <div class="card skill-tile">
              <div class="card-content">
                <i class="devicon-react-plain devicon big"></i><span class="alt-tile">Worked on several <strong>React</strong> <a href="https://constructr.be/">applications</a></span>
              </div>
              </div>
            </article>
            <article class="col s12 m4">
              <div class="card skill-tile">
              <div class="card-content">
                <i class="fab fa-angular devicon big"></i><span class="alt-tile">Can handle any framework such as <strong>Angular</strong> with ease</span>
              </div>
              </div>
            </article>
          </div>
        </div>
        <h3 class="clearfix">3. Get into more stacks</h3>
        <div class="container">
          <div id="more" class="row learned">
            <article class="col s12 m4">
              <div class="card skill-tile">
              <div class="card-content">
                <i class="devicon-php-plain devicon big"></i><span class="alt-tile"><a href="https://www.linkedin.com/in/axel-fiolle/detail/skills/(ACoAABP99YMBYi-m_8zbKoUSOzyNZBdZ7eUiMlw,28)/">Everybody</a> says I'm good at <strong>PHP</strong></span>
              </div>
              </div>
            </article>
            <article class="col s12 m4">
              <div class="card skill-tile">
              <div class="card-content">
                <i class="devicon-nodejs-plain devicon big"></i><span class="alt-tile"><strong>NodeJS</strong> is the coolest thing I ever handled</span>
              </div>
              </div>
            </article>
            <article class="col s12 m4">
              <div class="card skill-tile">
              <div class="card-content">
                <i class="fas fa-server devicon big"></i><span class="alt-tile"><strong>MySQL</strong> and <strong>MongoDB</strong> are my first choices</span>
              </div>
              </div>
            </article>
          </div>
        </div>
      </section>


    </v-col>
  </v-row>
</template>

<script>
  export default {
    name: 'LandingPage',

    data: () => ({
      ecosystem: [
        {
          text: 'vuetify-loader',
          href: 'https://github.com/vuetifyjs/vuetify-loader',
        },
        {
          text: 'github',
          href: 'https://github.com/vuetifyjs/vuetify',
        },
        {
          text: 'awesome-vuetify',
          href: 'https://github.com/vuetifyjs/awesome-vuetify',
        },
      ],
      importantLinks: [
        {
          text: 'Documentation',
          href: 'https://vuetifyjs.com',
        },
        {
          text: 'Chat',
          href: 'https://community.vuetifyjs.com',
        },
        {
          text: 'Made with Vuetify',
          href: 'https://madewithvuejs.com/vuetify',
        },
        {
          text: 'Twitter',
          href: 'https://twitter.com/vuetifyjs',
        },
        {
          text: 'Articles',
          href: 'https://medium.com/vuetify',
        },
      ],
      whatsNext: [
        {
          text: 'Explore components',
          href: 'https://vuetifyjs.com/components/api-explorer',
        },
        {
          text: 'Select a layout',
          href: 'https://vuetifyjs.com/getting-started/pre-made-layouts',
        },
        {
          text: 'Frequently Asked Questions',
          href: 'https://vuetifyjs.com/getting-started/frequently-asked-questions',
        },
      ],
    }),
  }
</script>

<style lang="scss" scoped>
  .avatar-section {
    color: white;
    background: rgba(0,0,0,.75);
    min-height: calc(100vh - 52px);
  }
  .main-container {
    background: rgba(255,255,255,.25);
    min-height: calc(100vh - 52px);
  }
</style>