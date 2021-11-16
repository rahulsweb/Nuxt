<template>

  <div>
  <section class="mailchimp-one">
    <div class="container text-justify">
   <div class="block-title text-center mt-10">
        <h2 class="block-title__title">Try Bip it free for 30 days</h2>
        <div class="mt-10 ">
                              <a href="#form" class="banner-one__btn thm-btn col-md-3 p-2 "><span>Get Started</span></a><!-- /.thm-btn -->

        </div>
<!-- /.block-title__title -->
      </div><!-- /.block-title -->
      <div class="mc-form__response"></div><!-- /.mc-form__response -->
    </div><!-- /.container -->
  </section>

        <div class="block-title text-center pt-5">
        <h2 class="block-title__title">Subscribe Our <span>Newsletter</span> <br> to Get New Updates.</h2><!-- /.block-title__title -->
      </div><!-- /.block-title -->
      <form action="#" class="mailchimp-one__mc-form mc-form mb-5" data-url="https://xyz.us18.list-manage.com/subscribe/post?u=20e91746ef818cd941998c598&amp;id=cc0ee8140e">
       
        <input type="email" id="mc-email" class="formInput border-bg" placeholder="Email address">
        <button type="submit"><i class="dimon-icon-right-arrow"></i>
          <!-- /.fa fa-paper-plane --></button>
      </form><!-- /.mailchimp-one__mc-form -->
  </div>



</template>

<script>
    export default {
      name: "Subscribe"
    }
</script>

<style scoped>
.p-2{
  padding:20px !important;
}
.border-bg{
  border:5px solid #ff4eb5 !important;
}
</style>
