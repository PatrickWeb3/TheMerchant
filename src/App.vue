<template>
  <div>
    <TopHeader />
    <BottomHeader />
    <HeroImage />
    <BestSellerProducts />
    <AboutSection />
    <LatestProducts />
    <BenefitsSection />
    <NewsLetter />
    <CommonQuestions />
    <FooterSection />
  </div>
</template>

<script>
import TopHeader from './components/TopHeader.vue'
import BottomHeader from './components/BottomHeader.vue'
import HeroImage from './components/HeroImage.vue'
import BestSellerProducts from './components/BestSellerProducts.vue'
import AboutSection from './components/AboutSection.vue'
import LatestProducts from './components/LatestProducts.vue'
import BenefitsSection from './components/BenefitsSection.vue'
import NewsLetter from './components/NewsLetter.vue'
import CommonQuestions from './components/CommonQuestions.vue'
import FooterSection from './components/FooterSection.vue'

export default {
  name: 'App',
  components: {
    TopHeader,
    BottomHeader,
    HeroImage,
    BestSellerProducts,
    AboutSection,
    LatestProducts,
    BenefitsSection,
    NewsLetter,
    CommonQuestions,
    FooterSection,
  }
}
</script>
