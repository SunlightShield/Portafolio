<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="10" md="8">
      <!--CARD DE INICIO-->
      <v-card>
        <v-card-title class="headline">
          Bienvenido a mi pagina (en construcción)
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
      <br>
      <v-card>
        <v-card-title class="headline">
          Mis proyectos
        </v-card-title>
        <v-card-text>
          <p>En la siguiente pagina podra ver todos los proyectos que he publicado enmi pagina de github</p>
          <p>
            La mayoria de mis proyectos estan orientados al area de Front, usando Javascript, HTML y CSS, pero tambien tengo
            una aplicación de escritorio creada en C# 
          </p>
        </v-card-text>
        <v-card-actions>
          <v-spacer />
          <button @click="iraProyectos()">
            <div class="box-2">
              <div class="btn btn-one">
                <span>Proyectos</span>
              </div>
            </div>    
          </button> 
        </v-card-actions>
      </v-card>
      <!--FIN CARD DE Proyectos-->

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
