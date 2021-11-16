<template>
  <section class="service-one" id="features">
    <br><br><br>
    <div class="container pt-5">
      <div class="block-title text-center " >
        <h2 class="block-title__title pt-5">Check out our features.</h2>
        <!-- /.block-title__title -->
      </div>
      <!-- /.block-title -->
      <div class="row">
        <div
          class="col-lg-3 col-md-6 col-sm-12 col-xs-12 wow fadeInUp"
        
        >
          <div class="service-one__single text-center ">
            <div class="service-one__inner first-block">
              <i class="service-one__icon dimon-icon-laptop"></i>
              <h3>
                <a href="#"
                  >CALENDAR WEBSITE <br />
                  INTEGRATION</a
                >
              </h3>
              <p class="p-2">
                Send guests your Bip it link or embed it on your website, email
                campaigns, social profiles, and landing pages.
              </p>
        
            </div>
            <!-- /.service-one__inner -->
          </div>
          <!-- /.service-one__single -->
        </div>
        <!-- /.col-lg-3 col-md-6 col-sm-12 -->
        <div
          class="col-lg-3 col-md-6 col-sm-12 wow fadeInDown"
          data-wow-duration="1500ms"
        >
          <div class="service-one__single text-center">
            <div class="service-one__inner sec-block">
              <i class="service-one__icon dimon-icon-presentation"></i>
              <h3>
                <a href="#"
                  >VIDEO CONFERENCE<br />
                  WEBSITE INTEGRATION</a
                >
              </h3>
              <p class="p-2">
                Embed Bip it video conferencing solution directly on your
                website for smoother appointments.
              </p>
            
            </div>
            <!-- /.service-one__inner -->
          </div>
          <!-- /.service-one__single -->
        </div>
        <!-- /.col-lg-3 col-md-6 col-sm-12 -->
        <div
          class="col-lg-3 col-md-6 col-sm-12 wow fadeInUp "
          data-wow-duration="1500ms"
        >
          <div class="service-one__single text-center ">
            <div class="service-one__inner third-block">
              <i class="service-one__icon dimon-icon-target"></i>
              <h3>
                <a href="#"
                  >MULTIPLE <br />
                  BOOKING FORMS</a
                >
              </h3>
              <p class="p-2">
                Set the right form for the right goal: one-on-one, group
                meetings, and round- robin for rotating availability.
              </p>
           
            </div>
            <!-- /.service-one__inner -->
          </div>
          <!-- /.service-one__single -->
        </div>
        <!-- /.col-lg-3 col-md-6 col-sm-12 -->
        <div
          class="col-lg-3 col-md-6 col-sm-12 wow fadeInDown"
          data-wow-duration="1500ms"
        >
          <div class="service-one__single text-center">
            <div class="service-one__inner forth-block">
              <i class="service-one__icon dimon-icon-visualization"></i>
              <h3>
                <a href="#"
                  >FREE & PAID <br />
                  APPOINTMENTS</a
                >
              </h3>
              <p class="p-2">
                Offer your services for free, or schedule paid appointments. You
                can take the payment at the time of booking, during or at the
                end of the meeting.
              </p>
        
            </div>
            <!-- /.service-one__inner -->
          </div>
          <!-- /.service-one__single -->
        </div>
        <!-- /.col-lg-3 col-md-6 col-sm-12 -->
      </div>
      <!-- /.row -->
    </div>
    <!-- /.container -->
  </section>
</template>

<script>
export default {
  name: "Featires",
};
</script>

<style scoped>
.service-one__single::before{
  opacity: 1 !important;
}
/* .service-one__single{
  height: 590px;
} */
.first-block{
  padding-bottom:20% !important ;
}
.sec-block{
  padding-bottom:33% !important ;
}
.third-block{
  padding-bottom:19% !important ;
}
.forth-block{
  padding-bottom:5% !important ;
}



</style>
