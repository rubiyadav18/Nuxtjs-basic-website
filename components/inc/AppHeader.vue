<template>
  <div class="sticky-top">
    <nav class="navbar navbar-expand-lg">
      <div class="container">
        <a class="navbar-brand" href="#">
          <img
            src="https://cdn.dribbble.com/users/2594111/screenshots/17902714/media/3d6fc4a3d1359f607f4876367d6709eb.jpg?compress=1&resize=400x300"
            class="logo-img"
            alt=""
          />
        </a>

        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav ms-auto mb-2 mb-lg-0 nav-space">
            <button type="button" @click="routes('/')" class="home">
              Home
            </button>

            <button type="button" class="home" @click="routes('/about')">
              About Us
            </button>
            <button type="button" @click="routes('/services')" class="home">
              Our Services
            </button>
            <button type="button" @click="routes('/contact')" class="home">
              Contact Us
            </button>

            <button type="button" @click="routes('/profile')" class="home">
              profile
            </button>

            <input type="text" class="search" placeholder="" name="" />
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>
<script>
export default {
  name: "AppHeader",
  methods: {
    routes(val) {
      this.$router.push(val);
    },
  },
};
</script>
<style >
.logo-img {
  width: 110px;
  height: 80px;
}
.sticky-top {
  background-color: #0c0d21;
}

.home {
  outline: none;
  border: none;
  color: white;
  background: linear-gradient(to right, purple, rgb(217, 3, 217));
  border-radius: 20px;
  padding: 3px 15px;
  font-size: 14px;
}

.nav-space {
  justify-content: space-between;
  gap: 20px;
}

.search {
  border-radius: 40px;
  padding: 5px 10px;
  background-color: white;
  outline: none;
  border: none;
}
</style>

<!-- 0C0D21 -->