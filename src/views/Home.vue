<template>
  <div class="home">
    <Menu />
    <SliderHome />
  </div>
</template>

<style lang="scss">

</style>

<script>
// @ is an alias to /src
import Menu from '@/components/Menu.vue'
import SliderHome from '@/components/SliderHome.vue'

export default {
  name: 'Home',
  components: {
    Menu,
    SliderHome
  }
}
</script>
