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
      <v-row justify="center" class="pa-10">
        <h1  class="text-h1 font-weight-black">aba097 portfolio</h1>
      </v-row>
    </v-container>

    <div style="background-color:#79c6b6;">
      <v-container>
        <v-row justify="center" class="px-10 pt-10 pb-5">
          <h2 class="text-h2 font-weight-black">Profile </h2>
        </v-row>
        <v-row justify="center">
          <v-col cols="2">
            <img src="~/assets/images/koara.png" width="150" height="150">
          </v-col>
          <v-col cols="6">
            <p>????????????????????????????????????????????????1???????????????????????????????????????????????????????????????????????????????????????????????????
              ?????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????
              ?????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????
              ???????????????????????????????????????????????????????????????????????????????????????TODO????????????????????????????????????????????????????????????????????????
            </p>
          <v-breadcrumbs class="pa-0" :items="linkItems">
              <template v-slot:item="{ item }">
                <v-breadcrumbs-item 
                  :href="item.href"
                  :disabled="item.disabled"
                >
                  <span class="font-weight-black"><v-icon large> {{ item.icon }} </v-icon> {{ item.text }} </span>
                </v-breadcrumbs-item>
              </template>
            </v-breadcrumbs>
          </v-col>
        </v-row>
      </v-container>
    </div>

    <v-container>
      <v-row justify="center" class="pa-10">
        <h2 class="text-h2 font-weight-black">Works</h2>
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
