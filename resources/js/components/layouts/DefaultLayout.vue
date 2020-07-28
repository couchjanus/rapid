<template>
  <div>
    <!-- Header -->
    <rapid-header></rapid-header>
    <rapid-intro></rapid-intro>
    
    <!-- Content -->
    <main id="main">
        <slot></slot>
    </main>
    <!-- Footer -->
    <rapid-footer></rapid-footer>
    
    <a href="#" class="back-to-top"><i class="fa fa-chevron-up"></i></a>
  </div>
</template>

<script>
import RapidHeader from './RapidHeader';
import RapidFooter from './RapidFooter';
import RapidIntro from './RapidIntro';

export default {
    name: `DefaultLayout`,
    components: {
        RapidHeader,
        RapidIntro,
        RapidFooter
    },
    data() {
        return {
        }
    },
    created() {    
    },
};
</script>
