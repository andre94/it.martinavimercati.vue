<template>
<div>
  <b-navbar toggleable="lg">
  
    <b-button size="lg" class="mr-lg-4" href="#">Appuntamento</b-button>

    <b-navbar-brand href="#">NavBar</b-navbar-brand>

    <b-navbar-toggle target="home__nav-collapse"></b-navbar-toggle>

    <b-collapse id="home__nav-collapse" is-nav>
      <b-navbar-nav class="ml-auto">
        <b-nav-item class="text-left" href="#">Home</b-nav-item>
        <b-nav-item class="text-left" href="#">Chi Sono</b-nav-item>
        <b-nav-item class="text-left" href="#">Attività</b-nav-item>
        <b-nav-item class="text-left" href="#">Ipnosi</b-nav-item>
        <b-nav-item class="text-left" href="#">Contatti</b-nav-item>
      </b-navbar-nav>
    </b-collapse>

  </b-navbar>
</div>
</template>

<script>
export default {
  name: 'Menu'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

</style>
