<template>
  <div class="preloader">
    <img src="/assets/images/resources/Bip it Logo.png" class="preloader__image" alt="" width="200">
  </div>
</template>

<script>
    export default {
      name: "Preloader",
      mounted() {
          if ($('.preloader').length) {
            $('.preloader').fadeOut();
          }
      }
    }
</script>

<style scoped>

</style>
