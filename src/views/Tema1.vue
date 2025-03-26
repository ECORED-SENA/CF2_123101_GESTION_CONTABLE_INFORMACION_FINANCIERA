<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Información Contable

    Separador
    <!-- BLOQUE  -->
    #t_1_1.titulo-segundo.color-acento-contenido
      h2 1.1 Historia, cualidades y objetivos de la información contable
    

    Separador
    <!-- BLOQUE  -->
    #t_1_2.titulo-segundo.color-acento-contenido
      h2 1.2 Marco conceptual bajo Estándares Internacionales

    
    Separador
    <!-- BLOQUE  -->
    #t_1_3.titulo-segundo.color-acento-contenido
      h2 1.3 Reconocimiento, medición, presentación, revelación y baja de cuentas de los elementos de los estados financieros

    
    Separador
    <!-- BLOQUE  -->
    #t_1_4.titulo-segundo.color-acento-contenido
      h2 1.4 Política contable
 
</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({
    mostrarIndicadorTarjetaAudio: true,
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
