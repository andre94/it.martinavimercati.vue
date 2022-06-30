<template>
<div>
  
</div>
</template>

<script>

export default {
  
  name: 'SliderHome',

  mounted: function () {
    const jquery = document.createElement("script");
    jquery.setAttribute(
      "src",
      "http://ajax.googleapis.com/ajax/libs/jquery/1.10.1/jquery.js"
    );
    jquery.async = true;
    document.head.appendChild(jquery);
  }

}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

</style>
