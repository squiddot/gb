<template>
  <div class="link-cards">
    <div class="headline">
      <h1>Creating With Purpose. <span class="headline__second">From day one.</span></h1>
    </div>
    <ul>
<!--      <li>-->
<!--        <a href="#" class="link-card" :style="{ backgroundImage: `url(${image0})`}">-->
<!--          <div class="icon">-->
<!--            <img src="../assets/icons/bell_icon.svg" alt="gb_logo"></div>-->
<!--          <h2>Unrivaled Service</h2>-->
<!--        </a>-->
<!--      </li>-->
      <li>
        <a href="#" class="link-card">
          <div class="bgimage"><img src="../assets/service.png" alt="gb_logo" style="opacity: .66"></div>
          <div class="icon"><img src="../assets/icons/bell_icon.svg" alt="gb_logo"></div>
          <h2>Unrivaled<br/> Service</h2>
        </a>
      </li>
      <li>
        <a href="#" class="link-card">
          <div class="bgimage"><img src="../assets/innovation.png" alt="gb_logo" style="opacity: .26"></div>
          <div class="icon">
            <img src="../assets/icons/ruler_icon.svg" alt="gb_logo"></div>
          <h2>Unending<br/> Innovation</h2>
        </a>
      </li>
      <li>
        <a href="#" class="link-card">
          <div class="bgimage"><img src="../assets/craftsmanship.png" alt="gb_logo" style="opacity: .12"></div>
          <div class="icon">
            <img src="../assets/icons/wrench_icon.svg" alt="gb_logo"></div>
          <h2>Pride In<br/> Craftsmanship</h2>
        </a>
      </li>
      <li>
        <a href="#" class="link-card">
          <div class="bgimage"><img src="../assets/products.png" alt="gb_logo"></div>
          <div class="icon">
            <img src="../assets/icons/cart_icon.svg" alt="gb_logo"></div>
          <h2>Products that<br/> Perform</h2>
        </a>
      </li>
    </ul>
  </div>
</template>

<script>
// import image0 from "../assets/service.png";
// import image1 from "../assets/innovation.png";
// import image2 from "../assets/craftsmanship.png";
// import image3 from "../assets/products.png";

export default {
  name: "LinkCards",
  // data() {
  //   return {
  //     image0,
  //     image1,
  //     image2,
  //     image3
  //   }
  // }
}
</script>

<style scoped>

</style>
