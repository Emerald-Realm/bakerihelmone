<template>
  <div class="homepage">
    <hr />
    <p>this is the homepage</p>
    <hr />
    <TheHeader />
    <hr />
    <Service />
    <hr />
    <Philosophy />
    <hr />
    <TheFooter />
    <hr />
    <About />
    <hr />
    <Contact />
    <hr />
  </div>
</template>

<script>
import TheHeader from "./homepage/TheHeader";
import TheFooter from "./homepage/TheFooter";
import Philosophy from "./homepage/Philosophy";
import About from "./homepage/About";
import Contact from "./homepage/Contact.vue";
import Service from "./homepage/Service.vue";

export default {
  name: "Home",
  components: {
    TheHeader,
    TheFooter,
    Philosophy,
    About,
    Contact,
    Service,
  },
};
</script>
