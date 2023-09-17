<template>
  <div class="main">
    <div class="main-box">
      <div class="main-box-title">
        <h1>our team</h1>
      </div>
      <div class="wrap">
        <div class="info">
          <img src="../assets/IMAGE15.jpg" alt="" />
          <h2>Ron Swanson</h2>
          <h3>Founder</h3>
          <div class="tag">
            <img src="../assets/IMAGE15-1.jpg" alt="" />
            <img src="../assets/IMAGE15-2.jpg" alt="" />
            <img src="../assets/IMAGE15-3.jpg" alt="" />
          </div>
        </div>
        <div class="info">
          <img src="../assets/IMAGE16.jpg" alt="" />
          <h2>Julia Depish</h2>
          <h3>Marketing</h3>
          <div class="tag">
            <img src="../assets/IMAGE15-1.jpg" alt="" />
            <img src="../assets/IMAGE15-2.jpg" alt="" />
            <img src="../assets/IMAGE15-3.jpg" alt="" />
          </div>
        </div>
        <div class="info">
          <img src="../assets/IMAGE17.jpg" alt="" />
          <h2>Danny Devry</h2>
          <h3>Designer</h3>
          <div class="tag">
            <img src="../assets/IMAGE17-1.jpg" alt="" />
            <img src="../assets/IMAGE15-1.jpg" alt="" />
            <img src="../assets/IMAGE17-3.jpg" alt="" />
            <img src="../assets/IMAGE17-4.jpg" alt="" />
            <img src="../assets/IMAGE15-3.jpg" alt="" />
          </div>
        </div>
        <div class="info">
          <img src="../assets/IMAGE18.jpg" alt="" />
          <h2>Lisa Smith</h2>
          <h3>Developer</h3>
          <div class="tag">
            <img src="../assets/IMAGE18-1.jpg" alt="" />
            <img src="../assets/IMAGE15-1.jpg" alt="" />
            <img src="../assets/IMAGE15-3.jpg" alt="" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script setup></script>
<style lang="scss" scoped>
.main {
  width: 1440px;
  height: 616px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.main-box {
  width: 940px;
  height: 478px;
  flex-shrink: 0;
}

h1 {
  color: #333;
  text-align: center;
  font-family: Montserrat;
  font-size: 23px;
  font-style: normal;
  font-weight: 400;
  line-height: 36px; /* 156.522% */
  text-transform: uppercase;
  margin-top: 10.05px;
  margin-bottom: 73px;
}

.info {
  width: 240px;
  height: 339px;
  flex-shrink: 0;
  display: flex;
  justify-content: center;
  flex-direction: column;
  align-items: center;
}

.info:hover {
  transform: scale(1.02);
  transition: 0.4s ease-in-out;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
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
  margin-top: 20px;
  margin-bottom: 6px;
}

h3 {
  color: #333;
  text-align: center;
  font-family: Vollkorn;
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
  line-height: 20px; /* 142.857% */
  margin-bottom: 17.95px;
}

img {
  width: 220px;
  height: 220px;
  flex-shrink: 0;
}
.tag {
  display: flex;
  width: 220px;
  height: 35px;
  padding: 11.047px 60px 9.953px 61px;
  justify-content: center;
  align-items: flex-start;
  gap: 21px;
  flex-shrink: 0;
}

.tag img {
  width: 14px;
  height: 14px;
  flex-shrink: 0;
}

.wrap {
  display: flex;
  gap: 20px;
}
</style>
