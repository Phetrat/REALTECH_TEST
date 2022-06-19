<template>
  <div>
    <div class="carousel-wrapper d-md-block d-none">
      <client-only>
        <slick :options="slickOptions">
          <div class="img-wrapper">
            <img src="~assets/images/blog.png" />
          </div>
          <div class="img-wrapper">
            <img src="~assets/images/blog.png" />
          </div>
          <div class="img-wrapper">
            <img src="~assets/images/blog.png" />
          </div>
          <div class="img-wrapper">
            <img src="~assets/images/blog.png" />
          </div>
          <div class="img-wrapper">
            <img src="~assets/images/blog.png" />
          </div>
          <div class="img-wrapper">
            <img src="~assets/images/blog.png" />
          </div>
        </slick>
      </client-only>
    </div>
    <div class="d-md-none d-block">
      <div class="img-wrapper">
        <img src="~assets/images/blog.png" class="w-50" />
        <h3 class="text-dark">อ่านเพิ่มเติม ➝</h3>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      slickOptions: {
        arows: false,
        slidesToShow: 3,
        dots: true,
        focusOnSelect: true,
        infinite: true,
        speed: 500,
        slidesToScroll: 3,
        touchThreshold: 5,
      },
    };
  },
};
</script>

<style>
.carousel-wrapper {
  padding: 40px;
}
.img-wrapper img {
  margin: auto;
  width: 100%;
  height: 100%;
  background-image: linear-gradient(gray 100%, transparent 0);
}
</style>
