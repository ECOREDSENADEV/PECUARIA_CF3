<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    #etapas.pb-5.h2 tema etapas
    .pb-5(v-for="item of 15")

    #producto.pb-5.h2 tema producto
    .pb-5(v-for="item of 15")

</template>

<script>
export default {
  name: 'TemaProducto',
  data: () => ({
    // variables de vue
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
