<template>
  <div>
    <Header />
    <Content />
    <AboutUs />
    <Parceiros />
    <ContactUs />
    <Footer />
  </div>
</template>

<script>
import Header from '@/components/organisms/Header.vue'
import Content from '@/components/organisms/Content.vue'
import Parceiros from '@/components/molecules/Parceiros.vue'
import AboutUs from '@/components/molecules/AboutUs.vue'
import ContactUs from '@/components/organisms/ContactUs.vue'
import Footer from '@/components/molecules/Footer.vue'

export default {

components: {
  Header,
  Content,
  AboutUs,
  Parceiros,
  ContactUs,
  Footer,
}
}
</script>

<style lang="scss" scoped>

</style>