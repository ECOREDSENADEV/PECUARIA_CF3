<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    #t_2_2_1.pb-5.h2 tema 2.2.1
    .pb-5(v-for="item of 15")

    #t_2_2_2.pb-5.h2 tema 2.2.2
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
