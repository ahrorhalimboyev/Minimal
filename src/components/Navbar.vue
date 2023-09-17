<template>
  <div class="main">
    <div class="main-in">
      <div class="main-pic">
        <img src="../assets/IMAGE.jpg" alt="image" />
        <div class="box">
          <p>Minimal</p>
        </div>
      </div>
      <div class="main-menu">
        <h3 style="width: 60px">process</h3>
        <h3 style="width: 66px">projects</h3>
        <h3 style="width: 35px">team</h3>
        <h3 style="width: 61px">contact</h3>
      </div>
    </div>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped>
.main {
  width: 1440px;
  height: 106px;
  flex-shrink: 0;
  background: #fff;
  display: flex;
  justify-content: center;
  align-items: center;
}
.main-in {
  display: inline-flex;
  justify-content: center;
  align-items: flex-start;
  gap: 427px;
}

.main-pic {
  width: 155px;
  height: 70px;
  display: flex;
  align-items: center;
}

img {
  width: 65px;
  height: 70px;
  flex-shrink: 0;
}

.box {
  width: 72px;
  margin-left: 18px;
  display: flex;
  justify-content: center;
}

p {
  width: 72px;
  color: #333;
  font-family: Oswald;
  font-size: 18px;
  font-style: normal;
  font-weight: 400;
  line-height: 38px;
  text-transform: uppercase;
}

h3 {
  color: #404040;
  font-family: Montserrat;
  font-size: 12px;
  font-style: normal;
  font-weight: 400;
  line-height: 20px; /* 166.667% */
  text-transform: uppercase;
}

.main-menu {
  display: flex;
  height: 45px;
  padding: 23px 0px 0px 34px;
  justify-content: flex-end;
  align-items: flex-start;
  gap: 34px;
}
</style>
