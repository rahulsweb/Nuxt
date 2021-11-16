<template>
  <div>
    <Header />
    <Banner />
       <CallToAction />
       <Meet />
         

      <Paid />
 

      <!-- <Video /> -->
    <Features />
    <Features1 />
     <Solution />
         <CallToActionTwo />
               <Security />
    <Pricing />

    <!-- <Testimonial /> -->
    <!-- <Brands />
    <Counter />
    <Screenshots /> -->
     <LogoSection />
    <Form />
    <!-- <BlogHome /> -->
    <Subscribe />
   
    <Footer />
    
  </div>
</template>
<script>
  import Header from "~/components/Header.vue";
  import Banner from "~/components/Banner.vue";
  import Features from "~/components/Features.vue";
    import Features1 from "~/components/Features1.vue";
  import Video from "~/components/Video.vue";
  import CallToAction from "~/components/CallToAction.vue";
    import Meet from "~/components/Meet.vue";
        import Paid from "~/components/Paid.vue";
          import Solution from "~/components/Solution.vue";
  import CallToActionTwo from "~/components/CallToActionTwo.vue";
  import LogoSection from "~/components/LogoSection.vue";
   import Security from "~/components/Security.vue";
  import Pricing from "~/components/Pricing.vue";
  import Testimonial from "~/components/Testimonial.vue";
  import Brands from "~/components/Brands.vue";
  import Counter from "~/components/Counter.vue";
  import Screenshots from "~/components/Screenshots.vue";
  import Faq from "~/components/Faq.vue";
  import BlogHome from "~/components/BlogHome.vue";
  import Subscribe from "~/components/Subscribe.vue";
    import Form from "~/components/Form.vue";
  import Footer from "~/components/Footer.vue";
  export default {
    components: {
      Header,
      Banner,
      Features,
       Features1,
      Video,
      CallToAction,
        Meet,
        Paid,
        Solution,
      CallToActionTwo,
      Security,
      Pricing,
      Testimonial,
      Brands,
      Counter,
      Screenshots,
      Faq,
      BlogHome,
      Subscribe,
      Form,
      Footer,
      LogoSection

    }
  }
</script>
