<script setup>
//import HelloWorld from './components/HelloWorld.vue'
import boton from './components/boton.vue'
import lista from './components/lista.vue'

</script>

<template>
  <div class="container mx-auto py-5">
    
    
          <h1 class="text-3xl font-titular mb-5">ISCLAB</h1>
    <p>Laboratorio de sistemas y aplicaciones web</p>
    <p>contacto@isclab.com.mx</p>

  <boton>agregar</boton>
  <boton>editar</boton>
  <boton>eliminar</boton>
  <boton class="bg-secundario">info</boton>

  <main>
    <lista></lista>
  </main>

  <footer>
  
  </footer>
  
  </div>
</template>