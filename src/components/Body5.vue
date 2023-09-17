<template>
  <div class="main">
    <div class="main-box">
      <div class="symbol">
        <img src="../assets/IMAGE19.jpg" alt="" />
      </div>
      <div class="pic">
        <div class="box">
          <div class="info">
            <h2>
              “I love these guys! They did a great job. I would recommend them
              to anyone.”
            </h2>
          </div>
          <img src="../assets/IMAGE20.jpg" alt="" />
          <h3>Julius Von Uberstien</h3>
        </div>
        <div class="box">
          <div class="info">
            <h2>
              “Elexis Corp. has grown immensely with the help of Minimal.”
            </h2>
          </div>
          <img src="../assets/IMAGE21.jpg" alt="" />
          <h3>Rachel Stamos</h3>
        </div>
      </div>
    </div>
  </div>
</template>
<script setup></script>
<style lang="scss" scoped>
.symbol {
  width: 62px;
  height: 62px;
  display: contents;
}

.symbol img {
  width: 62px;
  height: 62px;
}
.main {
  width: 1440px;
  height: 511px;
  flex-shrink: 0;
  display: flex;
  justify-content: center;
  align-items: center;
}

.main-box {
  display: flex;
  width: 940px;
  height: 373px;
  padding: 0.047px 23.5px 0px 23.5px;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap: 36.953px;
}

.pic {
  display: flex;
  flex-direction: row;
  //   padding-left: 55px;
  //   padding-right: 55px;
}

.info {
  width: 338px;
  height: 99px;
}
.box {
  width: 446.5px;
  height: 215px;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  flex-shrink: 0;
}

.info h2 {
  color: #333;
  text-align: center;
  font-family: Vollkorn;
  font-size: 26px;
  font-style: normal;
  font-weight: 400;
  line-height: 33px; /* 126.923% */
  //   margin-left: 70px;
  //   margin-right: 68;
  //   margin-top: 2px;
  //   margin-bottom: 24px;
  //   padding: 2px;
}

.box h3 {
  color: #ababab;
  text-align: center;
  font-family: Montserrat;
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
  line-height: 20px; /* 142.857% */
  text-transform: uppercase;
  margin-top: 10px;
}

img {
  width: 64px;
  height: 64px;
  flex-shrink: 0;
  margin-top: 24px;
  margin-bottom: 10px;
}
</style>
