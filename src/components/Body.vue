<template>
  <div class="main">
    <div class="main-text">
      <h3>Making brands stand out</h3>
      <h4>is our obsession</h4>
      <div class="h"></div>
      <h5>Let us help your brand stand out.</h5>
    </div>
    <div class="image">
      <img src="../assets/up.jpg" alt="" />
    </div>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped>
.main {
  width: 1440px;
  height: 391px;
  flex-shrink: 0;
  background-image: url("../assets/IMAGE1.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  background-position: 0%;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  position: relative;
}

h3 {
  width: 672px;
  color: #fff;
  text-align: center;
  font-family: Montserrat;
  font-size: 44px;
  font-style: normal;
  font-weight: 400;
  line-height: 55px; /* 125% */
  text-transform: uppercase;
}

h4 {
  width: 432px;
  color: #fff;
  text-align: center;
  font-family: Montserrat;
  font-size: 43px;
  font-style: normal;
  font-weight: 400;
  line-height: 55px; /* 127.907% */
  text-transform: uppercase;
}

.h {
  width: 80px;
  height: 2px;
  flex-shrink: 0;
  background-color: #fff;
  margin-top: 28px;
}

h5 {
  width: 225px;
  color: rgba(255, 255, 255, 0.81);
  text-align: center;
  font-family: Vollkorn;
  font-size: 15px;
  font-style: normal;
  font-weight: 400;
  line-height: 20px; /* 133.333% */
  margin-top: 25px;
}

.main-text {
  width: 940px;
  height: 195px;
  flex-shrink: 0;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.image {
  position: absolute;
  bottom: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
}

img {
  width: 52px;
  height: 26px;
  flex-shrink: 0;
}
</style>
