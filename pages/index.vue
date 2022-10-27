<template>
<!--
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="6">
      <v-card class="logo py-4 d-flex justify-center">
        <NuxtLogo />
        <VuetifyLogo />
      </v-card>
      <v-card>
        <v-card-title class="headline">
          Welcome to the Vuetify + Nuxt.js template
        </v-card-title>
        <v-card-text>
          <p>
            Vuetify is a progressive Material Design component framework for
            Vue.js. It was designed to empower developers to create amazing
            applications.
          </p>
          <p>
            For more information on Vuetify, check out the
            <a
              href="https://vuetifyjs.com"
              target="_blank"
              rel="noopener noreferrer"
            >
              documentation </a
            >.
          </p>
          <p>
            If you have questions, please join the official
            <a
              href="https://chat.vuetifyjs.com/"
              target="_blank"
              rel="noopener noreferrer"
              title="chat"
            >
              discord </a
            >.
          </p>
          <p>
            Find a bug? Report it on the github
            <a
              href="https://github.com/vuetifyjs/vuetify/issues"
              target="_blank"
              rel="noopener noreferrer"
              title="contribute"
            >
              issue board </a
            >.
          </p>
          <p>
            Thank you for developing with Vuetify and I look forward to bringing
            more exciting features in the future.
          </p>
          <div class="text-xs-right">
            <em><small>&mdash; John Leider</small></em>
          </div>
          <hr class="my-3" />
          <a
            href="https://nuxtjs.org/"
            target="_blank"
            rel="noopener noreferrer"
          >
            Nuxt Documentation
          </a>
          <br />
          <a
            href="https://github.com/nuxt/nuxt.js"
            target="_blank"
            rel="noopener noreferrer"
          >
            Nuxt GitHub
          </a>
        </v-card-text>
        <v-card-actions>
          <v-spacer />
          <v-btn color="primary" nuxt to="/inspire"> Continue </v-btn>
        </v-card-actions>
      </v-card>
    </v-col>
  </v-row>
-->

  <v-main>
    <v-container>
      <v-row justify="center">
        <h1>aba097 portfolio</h1>
      </v-row>
    </v-container>
    <v-container>
      <v-row justify="center">
        <h2>Profile </h2>
      </v-row>
      <!-- <v-row justify="center">
        <v-col>
          <img src="~/assets/images/koara.png" width="150" height="150">
        </v-col>
        <v-col>
          <p>静岡大学総合科学研究科情報学専攻1年の大学院生。高校は浜松工業高校の情報技術科・情報処理部に所属し、
            授業では、ハードウェア・ソフトウェア・ネットワーク・データベース・アルゴリズムなど幅広く学び、
            部活動では、主に競技プログラミングをしていた。その後、静岡大学情報学部情報科学科に進学し、同じく情報分野について学ぶ。
            大学では、主にアプリケーションの開発をしており、英単語帳やTODO、研究関連などのアプリケーションを開発している。
          </p>
         <v-breadcrumbs class="pa-0" :items="linkItems">
            <template v-slot:item="{ item }">
              <v-breadcrumbs-item 
                :href="item.href"
                :disabled="item.disabled"
              >
                <span><v-icon large> {{ item.icon }} </v-icon> {{ item.text }} </span>
              </v-breadcrumbs-item>
            </template>
          </v-breadcrumbs>
          
          
        </v-col>
      </v-row> -->
    </v-container>
    <v-container>
      <v-row justify="center">
        <h2>Works</h2>
      </v-row>
    </v-container>
</v-main>
</template>

<script>

export default {
  data(){
    return {
      linkItems: [
        {
          text: 'Github',
          disabled: false,
          icon: 'mdi-github',
          href: 'https://github.com/aba097',
        },
        {
          text: 'Zenn',
          disabled: false,
          icon: 'mdi-post-outline',
          href: 'breadcrumbs_link_1',
        }
      ]
    }
  }
}
</script>
