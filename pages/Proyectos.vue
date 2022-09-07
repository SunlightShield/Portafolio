<template>
    <div class="container">
  <div class="box">
    <div class="imgBx">
      <img src="~/assets/img/CalcEdad.PNG">
    </div>
    <div class="content">
      <div>
        <h2>Calculadora de edad</h2>
        <p>Una calcula que despliega con exactitud cuantos dias, meses y años han pasado desde una fecha intrducida por el usuario. creado con JS, HTML Y CSS
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
        <p>Un sencillo mantenedor de bodega, permite la creación, eliminacion y modificación de productos, ademas de generar reportes y codigos de barra
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
      <img src="">
    </div>
    <div class="content">
      <div>
        <h2>Proximamente</h2>
        <p>solo un placeholder para el siguiente proyecto
        </p>
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
      }
  },
}
</script>
