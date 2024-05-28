<template>
  <Header></Header>
  <HomeView></HomeView>
  <Footer></Footer>
</template>
<script>
import Header from "@/components/Header.vue";
import Footer from "@/components/Footer.vue";
import HomeView from "@/views/HomeView.vue";

export default {
  components: {
    Header,
    Footer,
    HomeView,
  },
};
</script>
