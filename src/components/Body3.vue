<template>
  <div class="main">
    <div class="main-box">
      <div class="main-box-title">
        <h1>Recent projects</h1>
      </div>
      <div class="main-box-img">
        <div class="images">
          <img src="../assets/IMAGE6.jpg" alt="image" />
          <h2>woods</h2>
          <h3>Photography</h3>
        </div>
        <div class="images">
          <img src="../assets/IMAGE7.jpg" alt="image" />
          <h2>path</h2>
          <h3>Website • Photography</h3>
        </div>
        <div class="images">
          <img src="../assets/IMAGE8.jpg" alt="image" />
          <h2>darkness</h2>
          <h3>Website</h3>
        </div>
        <div class="images">
          <img src="../assets/IMAGE9.jpg" alt="image" />
          <h2>waves</h2>
          <h3>Photography</h3>
        </div>
        <div class="images">
          <img src="../assets/IMAGE10.jpg" alt="image" />
          <h2>drops</h2>
          <h3>Website</h3>
        </div>
        <div class="images">
          <img src="../assets/IMAGE11.jpg" alt="image" />
          <h2>ocean</h2>
          <h3>Website</h3>
        </div>
        <div class="images">
          <img src="../assets/IMAGE12.jpg" alt="image" />
          <h2>town</h2>
          <h3>Website</h3>
        </div>
        <div class="images">
          <img src="../assets/IMAGE13.jpg" alt="image" />
          <h2>mountain</h2>
          <h3>Website</h3>
        </div>
        <div class="images">
          <img src="../assets/IMAGE14.jpg" alt="image" />
          <h2>camera</h2>
          <h3>Website</h3>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped>
.main {
  width: 1440px;
  height: 1469px;
  flex-shrink: 0;
  background: #f5f5f5;
  display: flex;
  justify-content: center;
  align-items: center;
}

.main-box {
  width: 940px;
  height: 1330.953px;
  flex-shrink: 0;
}

.main-box-title h1 {
  color: #333;
  text-align: center;
  font-family: Montserrat;
  font-size: 23px;
  font-style: normal;
  font-weight: 400;
  line-height: 36px; /* 156.522% */
  text-transform: uppercase;
  margin-top: 79px;
}

.main-box-img {
  width: 940px;
  height: 1142.953px;
  margin-top: 73px;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  gap: 20px;
}

h2 {
  color: #333;
  text-align: center;
  font-family: Montserrat;
  font-size: 16px;
  font-style: normal;
  font-weight: 400;
  line-height: 20px; /* 125% */
  text-transform: uppercase;
}

h3 {
  color: #333;
  text-align: center;
  font-family: Vollkorn;
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
  line-height: 20px; /* 142.857% */
}

img {
  width: 300px;
  height: 300px;
  flex-shrink: 0;
}

.images:hover {
  transform: scale(1.02);
  transition: 0.4s ease-in-out;
  box-shadow: 0 0 10px rgba(0, 0, 0, 1);
}
</style>
