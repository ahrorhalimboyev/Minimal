<template>
  <div class="main">
    <div class="main-box">
      <h1>LET’s Get in touch</h1>
      <div class="inbox">
        <div class="box">
          <img src="../assets/IMAGE22.jpg" alt="" />
          <h2>MEET US IN PERSON</h2>
          <p>8776 Juniper Street</p>
          <p>Unit #204</p>
          <p>Merriweather, Ontorio</p>
          <p>Canada</p>
        </div>
        <div class="box1">
          <img src="../assets/IMAGE23.jpg" alt="" />
          <h2>The traditional way</h2>
          <p>The traditional way</p>
          <p>contact@minimal.com</p>
          <br />
          <br />
          <p>Contact form</p>
          <p>Scroll down</p>
        </div>
        <div class="box">
          <img src="../assets/IMAGE24.jpg" alt="" />
          <h2>Let’s get social</h2>

          <div class="logo">
            <div class="logoin">
              <img src="../assets/IMAGE24-1.jpg" alt="" />
              <p>Facebook</p>
            </div>
            <div class="logoin">
              <img src="../assets/IMAGE24-2.jpg" alt="" />
              <p>Twitter</p>
            </div>
            <div class="logoin">
              <img src="../assets/IMAGE24-3.jpg" alt="" />
              <p>LinkedIn</p>
            </div>
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
  height: 517px;
  flex-shrink: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  background-image: url("../assets/IMAGE25.jpg");
}

.main-box {
  width: 940px;
  height: 379px;
  flex-shrink: 0;
  display: flex;
  justify-content: center;
  flex-direction: column;
}

.main-box h1 {
  color: #333;
  text-align: center;
  font-family: Montserrat;
  font-size: 23px;
  font-style: normal;
  font-weight: 400;
  line-height: 36px; /* 156.522% */
  text-transform: uppercase;
  margin-top: 10.05px;
  margin-bottom: 72.95px;
}

.inbox {
  width: 940px;
  height: 260px;
  display: flex;
}

.box {
  width: 319.984px;
  height: 238px;
  flex-shrink: 0;
}

.box1 {
  width: 313.4px;
  height: 260px;
  flex-shrink: 0;
}

.logo {
  display: flex;
  align-items: center;
  flex-direction: column;
}
.logoin {
  width: 100px;
  display: flex;
  flex-direction: row;
  align-items: center;
  gap: 9px;
}

.logo img {
  width: 14px;
  height: 14px;
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
  margin-top: 26px;
  margin-bottom: 20px;
}

p {
  color: #212121;
  text-align: center;
  font-family: Vollkorn;
  font-size: 17px;
  font-style: normal;
  font-weight: 400;
  line-height: 22px; /* 129.412% */
}
</style>
