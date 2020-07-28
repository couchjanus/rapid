<template>
    <section id="clients" class="wow fadeInUp">
      <div class="container">

        <header class="section-header">
          <h3>Our Clients</h3>
        </header>
      
            <vueper-slides
                class="no-shadow"
                :slide-ratio="1 / 4"
                :visible-slides="6"
                :arrows="false"
                fixed-height="60px"
                :gap="3"
                :dragging-distance="70"
                autoplay
                slide-image-inside 
                >
                <vueper-slide v-for="(slide, i) in slides" :key="i" :image="slide.image" />
            </vueper-slides>
      
      </div>
    </section>
</template>

<script>
// In your Vue.js component.
import { VueperSlides, VueperSlide } from 'vueperslides'

export default {
    name: `Clients`,
    components: { 
        VueperSlides, 
        VueperSlide 
    },
    data: () => ({
        rect: 0,
        slideHeight: 0,
        slideLeft: 0,
        active: null,
        selected: null,
        slides: [
            {
            image: require('./assets/images/clients/client-1.png')
            },
            {
            image: require('./assets/images/clients/client-2.png')
            },
            {
            image: require('./assets/images/clients/client-3.png')
            },
            {
            image: require('./assets/images/clients/client-4.png')
            },
            {
            image: require('./assets/images/clients/client-5.png')
            },
            {
            image: require('./assets/images/clients/client-6.png')
            },
            {
            image: require('./assets/images/clients/client-7.png')
            },
            {
            image: require('./assets/images/clients/client-8.png')
            },
        ]
    })
}
</script>