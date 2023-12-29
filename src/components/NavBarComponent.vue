<template>
  <div class="Navbar">
    <b-navbar type="dark" variant="dark">
      <b-navbar-nav class="mx-auto">
        <router-link to="/" class="nav-link" v-bind="selected">Home</router-link>
        <router-link to="/about" class="nav-link" v-bind="selected">About</router-link>
      </b-navbar-nav>
    </b-navbar>
  </div>
</template>

<script>
export default {
  name: 'Navbar',
  data(){
    return{
      selected: false
    }
  },
  methods: {
    seleccionado(){
      this.selected = !this.selected
    }
  }
}
</script>

<style scoped>

</style>


