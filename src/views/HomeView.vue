<template>
  <div class="home">
    <TituloComponent msg="PAGINA HOME"/>
  </div>
</template>

<script>
// @ is an alias to /src
import TituloComponent from '@/components/TituloComponent.vue'


export default {
  name: 'HomeView',
  components: {
    TituloComponent,
  }
}
</script>
