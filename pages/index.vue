<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="10" md="8">
      <!--CARD DE INICIO-->
      <v-card>
        <v-card-title class="headline">
          Bienvenido a mi página (en construcción)
        </v-card-title>
        <v-card-text>
          <p>Soy Sebastián Espinoza, un programador chileno de 28 años, en búsqueda de un nuevo trabajo</p>
          <p>Actualmente me encuentro trabajando en la empresa Soluziona, como desarrollador Front end, trabajamos con React, y C# para el backend.
            me estoy entrenando para trabajar en el backend de mis propios proyectos.
          </p>
          <p>
            En esta página exhibo mis trabajos y experiencias, además de mi currículum. Casi todos orientados al área de Front End
          </p>
          <p>
            También tengo conocimientos en lenguajes como C#, y Java.
          </p>

          <p>Gracias por visitar mi página! </p>
          <br>
          <a
            href="https://github.com/SunlightShield"
            target="_blank"
            rel="noopener noreferrer"
          >
           Mi GitHub
          </a>
        </v-card-text>
        </v-card>
        <v-card>
          <v-card-actions class="justify-space-between">
            <div class="box-1">
              <button @click="iraCV()">
                <div class="btn btn-one">
                  <span>Ir a CV</span>
                </div>
              </button>  
            </div>
              <div class="box-3">
                <button @click="iraGit()">
                  <div class="btn btn-one">
                    <span>Ir a GitHub</span>
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
          <p>En la siguiente página podrá ver todos los proyectos que he publicado en mi perfil de GitHub</p>
          <p>
            La mayoría de mis proyectos están orientados al área de Front, usando Javascript, HTML y CSS, pero también tengo
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
      },
      iraGit(){
   window.location.href = "https://github.com/SunlightShield" 
      }
  },
}
console.log("hola gabriel");
</script>
