<template>
  <div>
    <slider />
    <Aboutus />
    <OurServices />
    <ContactUs />
    <profile/>
  </div>
</template>

<script>
import slider from "~/components/slider.vue";
import Aboutus from "~/components/Aboutus.vue";
import OurServices from "~/components/OurServices.vue";
import ContactUs from "~/components/ContactUs.vue";
import profile from "~/components/profile.vue"

export default {
  name: "IndexPage",
  comments: { slider, Aboutus, OurServices, ContactUs,profile },
  head() {
    return {
      title: "Home Page",
      meta: [
        {
          hid: "description",
          name: "description",
          content: "Home page description",
        },
        {
          hid: "keywords",
          name: "keywords",
          content: "Home page",
        },
      ],
    };
  },
};
</script>
<style>
.aboutus {
  /* margin-left: 31rem; */
  /* display: grid;
  place-items: center; */
}
.serviceus {
  /* margin-left: 39rem;
  display: flex;
  justify-content: center; */
  animation-name: example;
  animation-duration: 3s;
  animation-iteration-count: infinite;
}

@keyframes example {
  0% {
    color: red;
  }
  25% {
    color: blue;
  }
  50% {
    color: green;
  }
  75% {
    color: yellow;
  }
  100% {
    color: red;
  }
}
/* 
.box {
  margin-left: 15rem;
}
.service-heading {
  margin-left: 16rem;
}
.service-heading2 {
  margin-left: 16rem;
}
.pargraph {
  border-radius: 20px;
  margin-left: 260px;
} */
</style>

<!-- <div class="d-flex items-top justify-content-center" style="width: 100vw">
  <h1 class="">rubi yadav</h1>
</div> -->