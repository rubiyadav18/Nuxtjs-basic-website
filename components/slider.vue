<template>
    <div>
      <b-carousel
      id="carousel-fade"
      style="text-shadow: 0px 0px 2px #000"
      fade
      indicators
      img-width="1010"
      img-height="170px"
    >
      <b-carousel-slide
        caption="First Slide"
        img-src="/images/coding.webp"
      ></b-carousel-slide>
  
      <b-carousel-slide
        caption="Second Slide"
        img-src="/images/coding.webp"
      ></b-carousel-slide>
  
      <b-carousel-slide
        caption="Third Slide"
        img-src="images/slider5.png"
      ></b-carousel-slide>
    </b-carousel>
  
    </div>
  </template>
  
  <script>
  export default {
    name:'slider'
  
  }
  </script>
  
  