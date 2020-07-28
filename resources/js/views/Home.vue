<template>
  <default-layout>
    <template v-slot:default>
<!--==========================
      About Us Section
    ============================-->
    <!--==========================
      Services Section
    ============================-->
        <!--==========================
      Why Us Section
    ============================-->
    <!--==========================
      Call To Action Section
    ============================-->
    <!--==========================
      Features Section
    ============================-->
     <!--==========================
      Portfolio Section
    ============================-->
    <!--==========================
      Clients Section testimonials
    ============================-->
    <!--==========================
      Team Section
    ============================-->
    <!--==========================
      Clients Section
    ============================-->
      <Clients></Clients>
      <!--==========================
      Pricing Section
    ============================-->
    <!--==========================
      Frequently Asked Questions Section
    ============================-->
    <section id="faq">
      <div class="container">
        <header class="section-header">
          <h3>Frequently Asked Questions</h3>
          <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque</p>
        </header>

    <Faq title="base expander:rightToLeft">
        <h3>Lorem ipsum dolor sit amet</h3>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Blanditiis explicabo porro, voluptatum laborum cumque molestiae quibusdam accusamus sed, quam sint ducimus libero distinctio? Dolore laborum, quos dolorem recusandae deleniti quasi.</p>
    </Faq>
    <Faq title="expander animation:leftToRight" animation="leftToRight">
        <h3>Lorem ipsum dolor sit amet</h3>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Blanditiis explicabo porro, voluptatum laborum cumque molestiae quibusdam accusamus sed, quam sint ducimus libero distinctio? Dolore laborum, quos dolorem recusandae deleniti quasi.</p>
    </Faq>
    <Faq title="expander animation:bounceIn" animation="bounceIn">
        <h3>Lorem ipsum dolor sit amet</h3>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Blanditiis explicabo porro, voluptatum laborum cumque molestiae quibusdam accusamus sed, quam sint ducimus libero distinctio? Dolore laborum, quos dolorem recusandae deleniti quasi.</p>
    </Faq>
    <Faq title="expander animation:bottomToTop" animation="bottomToTop">
        <h3>Lorem ipsum dolor sit amet</h3>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Blanditiis explicabo porro, voluptatum laborum cumque molestiae quibusdam accusamus sed, quam sint ducimus libero distinctio? Dolore laborum, quos dolorem recusandae deleniti quasi.</p>
    </Faq>
</div>
    </section><!-- #faq -->
    </template>
  </default-layout>
</template>

<script>
import DefaultLayout from "../components/layouts/DefaultLayout.vue";
import Clients from "../components/sliders/Clients.vue";
import Faq from "../components/landing/Faq.vue";

export default {
  name: "Home",
  components: {
    DefaultLayout,
    Clients,
    Faq
  }
};
</script>
