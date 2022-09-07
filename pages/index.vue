<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="10" md="8">
      <!--CARD DE INICIO-->
      <v-card>
        <v-card-title class="headline">
          Bienvenido a mi pagina
        </v-card-title>
        <v-card-text>
          <p>Soy Sebastian Espinoza, un programador de 28 años, en busqueda de un nuevo trabajo</p>
          <p>
            En esta pagina exhibo mis trabajos y experiencias, ademas de mi curriculum. Casi todos orientados al area de Front End
          </p>
          <p>
            Tambien tengo conocimientos en lenguajes como C#, y java.
          </p>

          <p>Gracias por visitar mi pagina! </p>
          <br>
          <a
            href="https://github.com/SunlightShield"
            target="_blank"
            rel="noopener noreferrer"
          >
           Mi GitHub
          </a>
        </v-card-text>
        <v-card-actions>
          <v-spacer />
            <div class="box-1">
              <button @click="iraCV()">
                <div class="btn btn-one">
                  <span>Ir a CV</span>
                </div>
              </button>  
            </div>
        </v-card-actions>
      </v-card>
      <!--FIN CARD DE INICIO-->

      <!--CARD DE Proyectos-->
      <v-card>
        <v-card-title class="headline">
          Bienvenido a mi pagina
        </v-card-title>
        <v-card-text>
          <p>Vuetify is a progressive Material Design component framework for Vue.js. It was designed to empower developers to create amazing applications.</p>
          <p>
            For more information on Vuetify, check out the <a
              href="https://vuetifyjs.com"
              target="_blank"
              rel="noopener noreferrer"
            >
              documentation
            </a>.
          </p>
          <p>
            If you have questions, please join the official <a
              href="https://chat.vuetifyjs.com/"
              target="_blank"
              rel="noopener noreferrer"
              title="chat"
            >
              discord
            </a>.
          </p>
          <p>
            Find a bug? Report it on the github <a
              href="https://github.com/vuetifyjs/vuetify/issues"
              target="_blank"
              rel="noopener noreferrer"
              title="contribute"
            >
              issue board
            </a>.
          </p>
          <p>Thank you for developing with Vuetify and I look forward to bringing more exciting features in the future.</p>
          <div class="text-xs-right">
            <em><small>&mdash; John Leider</small></em>
          </div>
          <hr class="my-3">
          <a
            href="https://nuxtjs.org/"
            target="_blank"
            rel="noopener noreferrer"
          >
            Nuxt Documentation
          </a>
          <br>
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
          <button @click="iraProyectos()">
            <div class="box-1">
              <div class="btn btn-one">
                <span>Proyectos</span>
              </div>
            </div>    
          </button> 
        </v-card-actions>
      </v-card>
      <!--FIN CARD DE Proyectos-->

      <!--CARD DE CV-->
      <v-card>
        <v-card-title class="headline">
          Bienvenido a mi pagina
        </v-card-title>
        <v-card-text>
          <p>Vuetify is a progressive Material Design component framework for Vue.js. It was designed to empower developers to create amazing applications.</p>
          <p>
            For more information on Vuetify, check out the <a
              href="https://vuetifyjs.com"
              target="_blank"
              rel="noopener noreferrer"
            >
              documentation
            </a>.
          </p>
          <p>
            If you have questions, please join the official <a
              href="https://chat.vuetifyjs.com/"
              target="_blank"
              rel="noopener noreferrer"
              title="chat"
            >
              discord
            </a>.
          </p>
          <p>
            Find a bug? Report it on the github <a
              href="https://github.com/vuetifyjs/vuetify/issues"
              target="_blank"
              rel="noopener noreferrer"
              title="contribute"
            >
              issue board
            </a>.
          </p>
          <p>Thank you for developing with Vuetify and I look forward to bringing more exciting features in the future.</p>
          <div class="text-xs-right">
            <em><small>&mdash; John Leider</small></em>
          </div>
          <hr class="my-3">
          <a
            href="https://nuxtjs.org/"
            target="_blank"
            rel="noopener noreferrer"
          >
            Nuxt Documentation
          </a>
          <br>
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
          <v-btn
            color="primary"
            nuxt
            to="/inspire"
          >
            Continue
          </v-btn>
        </v-card-actions>
      </v-card>
      <!--FIN CARD DE CV-->

    </v-col>

    <!--cards de animaciones-->

  </v-row>

</template>

<script>
export default {
  name: 'IndexPage',
  methods:{
   iraCV(){
   this.$router.push('/CV'); 
      },
      iraProyectos(){
   this.$router.push('/Proyectos'); 
      }
  },
}
</script>
