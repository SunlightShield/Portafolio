<template>
    <div class="container">
  <div class="box">
    <div class="imgBx">
      <img src="~/assets/img/Tarjeta.PNG">
    </div>
    <div class="content">
      <div>
        <h2>Tarjeta de credito, maqueta funcional</h2>
        <p>Usando React, he completado como ejercicio una tarjeta de credito. genera de forma random cada clave numerica, expiración y CVC
          ademas en una tarjeta situada en la misma pagina, se puedne comprar los valores con validaciones sencillas. 
        </p>
        <button @click="iraTarjeta()">
          <span>Ir al Repositorio</span>  
        </button>
      </div>
    </div>
  </div>



  <div class="box">
    <div class="imgBx">
      <img src="~/assets/img/CalcEdad.PNG">
    </div>
    <div class="content">
      <div>
        <h2>Calculadora de edad</h2>
        <p>Una calculadora que despliega con exactitud cuantos días, meses y años han pasado desde una fecha intrducida por el usuario, creado con JS, HTML Y CSS
        </p>
        <button @click="iraCalculadoraJS()">
          <span>Ir al Repositorio</span>  
        </button>
      </div>
    </div>
  </div>
  <div class="box">
    <div class="imgBx">
      <img src="~/assets/img/cbodega.PNG">
    </div>
    <div class="content">
      <div>
        <h2>Mantenedor Bodega</h2>
        <p>Un sencillo mantenedor de bodega, permite la creación, eliminacion y modificación de productos, además de generar reportes y códigos de barra
          usando una base de datos SQL
        </p>
        <button @click="iraBodega()">
          <span>Ir al Repositorio</span>  
        </button>
      </div>
    </div>
  </div>
  <div class="box">
    <div class="imgBx">
      <img src="~/assets/img/todo-list.PNG">
    </div>
    <div class="content">
      <div>
        <h2>Lista de quehaceres </h2>
        <p>una lista de quehaceres, creada en JS, HTML y CSS
        </p>
        <button @click="iraTodo()">
          <span>Ir al Repositorio</span>  
        </button>
      </div>
    </div>
  </div>
</div>
</template>
<script>
export default {
  name: 'IndexPage',
  methods:{
   iraCalculadoraJS(){
   window.location.href = "https://github.com/SunlightShield/Calculadora_edad_JS" 
      },
      iraBodega(){
   window.location.href = "https://github.com/SunlightShield/Mantenedor_bodega" 
      },
      iraTodo(){
   window.location.href = "https://github.com/SunlightShield/To-doJS" 
      },
      iraTarjeta(){
   window.location.href = "https://github.com/SunlightShield/Tarjeta-Credito" 
      }
  },
}
</script>
