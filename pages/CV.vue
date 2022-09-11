<template>
<div>
            <div v-if="$device.isDesktop">
      <v-row justify="center" align="center">
            <v-col xs="12" sm="10" md="12">
                <v-card>
                    <v-system-bar color="indigo darken-2" dark>
                    <v-spacer></v-spacer>
                    </v-system-bar>

                    <v-toolbar class="animate__animated animate__backInDown" color="indigo" dark>
                    <v-toolbar-title>Sebastián Espinoza</v-toolbar-title>
                        <v-spacer></v-spacer>
                    </v-toolbar>

                    <v-container fluid>
                        <v-row dense>
                            <v-card class="d-flex justify-space-around" flat tile>
                                <v-card class="d-flex lg 2 pa-5 animate__animated animate__backInLeft" outlined tile>
                                    ingresar foto aqui
                                </v-card>

                                <v-card class="pa-5 animate__animated animate__backInRight" outlined tile>
                                    Soy Sebastián Espinoza, de 28 años, egresado de la carrera Ingeniería en informática de Inacap. 
                                    Busco desempeñarme como desarrollador Front End, y también aprender más sobre el área de 
                                    Back End.
                                    Aparte de las experiencias mencionadas más abajo, también me he desempeñado en diversas áreas, 
                                    tales como líneas productivas, atención al cliente tanto telefónico como retail y gestión de bodegas 
                                    y adquisiciones.
                                </v-card>
                            </v-card>
                        </v-row>
                        <v-row dense>
                                <v-card class="d-flex justify-space-around animate__animated animate__backInDown" outlined tile>
                                    <v-list-item three-line>
                                        <v-list-item-content>
                                            <v-list-item-title class="text-h5">
                                            Mis experiencias relevantes
                                            </v-list-item-title>
                                            <v-card-subtitle>
                                                <b>Transportes Duo (Abril-2022 hasta Julio-2022)</b>
                                            </v-card-subtitle>
                                            <v-card-text>
                                                Tareas realizadas:<br/>
                                                Parte del equipo de programadores 
                                                de Front End, encargado del diseño y creación de 
                                                diferentes vistas para la plataforma web, trabajando
                                                con Vue2, Vuetify y JavaScript, también presté apoyo 
                                                al equipo de Back.
                                                Cerca del final del proyecto también se me pidió
                                                clonar el sitio en un proyecto Nuxt.
                                            </v-card-text>
                                            <br>
                                            <v-card-subtitle>
                                                <b>Dev Lef (De noviembre 2021 Hasta enero 2022)</b>
                                            </v-card-subtitle>
                                            <v-card-text>
                                                Tareas realizadas: <br/> 
                                                Parte del equipo de programadores 
                                                de Front End, encargados de la creación de las 
                                                diferentes vistas de una plataforma web.
                                                También realicé tareas de QA, documentación del 
                                                código y cumplí tanto como Monitor como líder de 
                                                equipo

                                            </v-card-text>
                                        </v-list-item-content>
                                    </v-list-item>
                                </v-card>   
                        </v-row>    

                        <v-row dense>
                            <v-card class="d-flex justify-space-around" flat tile>
                                <v-card class="d-flex justify-space-around animate__animated animate__backInLeft" outlined tile>
                                    <v-list-item three-line>
                                        <v-list-item-content>
                                            <v-list-item-title class="text-h5">
                                            Mis datos de contacto
                                            </v-list-item-title>
                                            <v-card-text>
                                                Santiago de Chile, Maipú<br/>
                                                Teléfono +56971489720<br/>
                                                E-mail sespinozahenriquez@gmail.com<br/>
                                                Git: <a href="https://github.com/SunlightShield">https://github.com/SunlightShield</a><br/>
                                                Linkedin: <a href="www.linkedin.com/in/sebastián-espinoza-hénriquez-367b4516a">www.linkedin.com/in/sebastián-espinoza-henriquez</a><br/>
                                            </v-card-text>
                                        </v-list-item-content>
                                    </v-list-item>
                                </v-card>

                                <v-card class="d-flex justify-space-around animate__animated animate__backInRight" outlined tile>
                                    <v-list-item three-line>
                                        <v-list-item-content>
                                            <v-list-item-title class="text-h5">
                                            Tecnologias
                                            </v-list-item-title>
                                            <v-card-text>
                                                Javascript -
                                                C# -
                                                Java -
                                                PHP -
                                                HTML -
                                                CSS -
                                                VUE  -
                                                NUXT - <br/> 
                                                Laravel -
                                                Angular -
                                                SQL
                                            </v-card-text> 
                                            <v-list-item-title class="text-h5">
                                            Idiomas
                                            </v-list-item-title>
                                            <v-card-text>
                                                Español<br/>
                                                Ingles B2<br/>
                                            </v-card-text>
                                        </v-list-item-content>
                                    </v-list-item>
                                </v-card>
                            </v-card>    
                        </v-row>
                        
                        <v-row dense>
                            <v-card class="d-flex justify-space-around animate__animated animate__backInDown" outlined tile>
                                    <v-list-item three-line>
                                        <v-list-item-content>
                                            <v-list-item-title class="text-h5">
                                            Mis Estudios
                                            </v-list-item-title>
                                            <v-card-subtitle>
                                                <b>Ingeniería en Informática (Egreso 2022)</b>
                                            </v-card-subtitle>
                                            <v-card-text>
                                                Durante mis estudios, aprendí diversas tecnologías tales como Java, C# y PHP, además de las diversas metodologías 
                                                y teorías sobre el desarrollo de soluciones informáticas.
                                                Mi proyecto final fue el desarrollo y posterior defensa de una aplicación de escritorio para manejo de bodegas e inventarios, creado en C#
                                                con una base de datos en SQL 
                                            </v-card-text>
                                            <br>
                                            <v-card-subtitle>
                                                <b>Literatura y lingüística inglesa (Incompleta)</b>
                                            </v-card-subtitle>
                                            <v-card-text>
                                                Estudio de la lengua y cultura inglesa, tanto en uso como en el meta lenguaje (Morfologia, historia y sintaxis) 
                                                como en la lingüística estructural de esta

                                            </v-card-text>
                                            <br>
                                            <v-card-subtitle>
                                                <b>Alicante del Rosal (Enseñanza media completa 2011)</b>
                                            </v-card-subtitle>
                                            <v-card-text>
                                                
                                            </v-card-text>
                                        </v-list-item-content>
                                    </v-list-item>
                                </v-card>
                        </v-row>    
                    </v-container>
                </v-card>
            </v-col>
        </v-row>
    </div>
    <div v-else>
      
      <v-row justify="center" align="center">
            <v-col xs="10">
                <v-card>
                    <v-system-bar color="indigo darken-2" dark>
                    <v-spacer></v-spacer>
                    </v-system-bar>

                    <v-toolbar class="animate__animated animate__backInDown" color="indigo" dark>
                    <v-toolbar-title>Sebastián Espinoza</v-toolbar-title>
                        <v-spacer></v-spacer>
                    </v-toolbar>

                    <v-container fluid>
                        <v-row dense>
                            <v-card class="d-flex justify-space-around" flat tile>
                                <v-card class="pa-5 animate__animated animate__backInRight" outlined tile>
                                    Soy Sebastián Espinoza, de 28 años, egresado de la carrera Ingeniería en informática de Inacap. 
                                    Busco desempeñarme como desarrollador Front End, y también aprender más sobre el área de 
                                    Back End.
                                    Aparte de las experiencias mencionadas más abajo, también me he desempeñado en diversas áreas, 
                                    tales como líneas productivas, atención al cliente tanto telefónico como retail y gestión de bodegas 
                                    y adquisiciones.
                                </v-card>
                            </v-card>
                        </v-row>
                        <v-row dense>
                                <v-card class="d-flex justify-space-around animate__animated animate__backInDown" outlined tile>
                                    <v-list-item three-line>
                                        <v-list-item-content>
                                            <v-list-item-title class="text-h5">
                                            Mis experiencias relevantes
                                            </v-list-item-title>
                                            <v-card-subtitle>
                                                <b>Transportes Duo (Abril-2022 hasta Julio-2022)</b>
                                            </v-card-subtitle>
                                            <v-card-text>
                                                Tareas realizadas:<br/>
                                                Parte del equipo de programadores 
                                                de Front End, encargado del diseño y creación de 
                                                diferentes vistas para la plataforma web, trabajando
                                                con Vue2, Vuetify y JavaScript, también presté apoyo 
                                                al equipo de Back.
                                                Cerca del final del proyecto también se me pidió
                                                clonar el sitio en un proyecto Nuxt.
                                            </v-card-text>
                                            <br>
                                            <v-card-subtitle>
                                                <b>Dev Lef (De noviembre 2021 Hasta enero 2022)</b>
                                            </v-card-subtitle>
                                            <v-card-text>
                                                Tareas realizadas: <br/> 
                                                Parte del equipo de programadores 
                                                de Front End, encargados de la creación de las 
                                                diferentes vistas de una plataforma web.
                                                También realicé tareas de QA, documentación del 
                                                código y cumplí tanto como Monitor como líder de 
                                                equipo

                                            </v-card-text>
                                        </v-list-item-content>
                                    </v-list-item>
                                </v-card>   
                        </v-row>    

                        <v-row dense>
                            <v-card class="d-flex justify-space-around animate__animated animate__backInLeft" flat tile>
                                <v-list-item three-line>
                                        <v-list-item-content>
                                            <v-list-item-title class="text-h5">
                                            Mis datos de contacto
                                            </v-list-item-title>
                                            <v-card-text>
                                                Santiago de Chile, Maipú<br/>
                                                Teléfono +56971489720<br/>
                                                E-mail sespinozahenriquez@gmail.com<br/>
                                                Git: <a href="https://github.com/SunlightShield">https://github.com/SunlightShield</a><br/>
                                                Linkedin: <a href="www.linkedin.com/in/sebastián-espinoza-hénriquez-367b4516a">www.linkedin.com/in/sebastián-espinoza-henriquez</a><br/>
                                            </v-card-text>
                                        </v-list-item-content>
                                </v-list-item>
                            </v-card> 
                            <v-card>
                                <v-list-item three-line>
                                        <v-list-item-content>
                                            <v-list-item-title class="text-h5">
                                            Tecnologias
                                            </v-list-item-title>
                                            <v-card-text>
                                                Javascript -
                                                C# -
                                                Java -
                                                PHP -
                                                HTML -
                                                CSS -
                                                VUE  -
                                                NUXT - <br/> 
                                                Laravel -
                                                Angular -
                                                SQL
                                            </v-card-text> 
                                            <v-list-item-title class="text-h5">
                                            Idiomas
                                            </v-list-item-title>
                                            <v-card-text>
                                                Español<br/>
                                                Ingles B2<br/>
                                            </v-card-text>
                                        </v-list-item-content>
                                    </v-list-item>
                            </v-card>       
                        </v-row>
                        
                        <v-row dense>
                            <v-card class="d-flex justify-space-around animate__animated animate__backInDown" outlined tile>
                                    <v-list-item three-line>
                                        <v-list-item-content>
                                            <v-list-item-title class="text-h5">
                                            Mis Estudios
                                            </v-list-item-title>
                                            <v-card-subtitle>
                                                <b>Ingeniería en Informática (Egreso 2022)</b>
                                            </v-card-subtitle>
                                            <v-card-text>
                                                Durante mis estudios, aprendí diversas tecnologías tales como Java, C# y PHP, además de las diversas metodologías 
                                                y teorías sobre el desarrollo de soluciones informáticas.
                                                Mi proyecto final fue el desarrollo y posterior defensa de una aplicación de escritorio para manejo de bodegas e inventarios, creado en C#
                                                con una base de datos en SQL 
                                            </v-card-text>
                                            <br>
                                            <v-card-subtitle>
                                                <b>Literatura y lingüística inglesa (Incompleta)</b>
                                            </v-card-subtitle>
                                            <v-card-text>
                                                Estudio de la lengua y cultura inglesa, tanto en uso como en el meta lenguaje (Morfologia, historia y sintaxis) 
                                                como en la lingüística estructural de esta

                                            </v-card-text>
                                            <br>
                                            <v-card-subtitle>
                                                <b>Alicante del Rosal (Enseñanza media completa 2011)</b>
                                            </v-card-subtitle>
                                            <v-card-text>
                                                
                                            </v-card-text>
                                        </v-list-item-content>
                                    </v-list-item>
                                </v-card>
                        </v-row>    
                    </v-container>
                </v-card>
            </v-col>
        </v-row>

    </div>
        
    </div>
        <!--EN CASO DE QUE LA PANTALLA SEA TELEFONO-->   
        
</template>
<script>
import 'animate.css';
  export default {
    

    data: () => ({
      
    }),
  }
</script>