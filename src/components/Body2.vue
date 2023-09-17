<template>
  <div class="main">
    <div>
      <h1>How we make brands thrive</h1>
    </div>
    <div class="out-box">
      <div class="box">
        <div class="pic">
          <img src="../assets/IMAGE3.jpg" alt="" />
        </div>
        <h2>SET a target</h2>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse
          varius enim in eros elementum tristique.
        </p>
      </div>
      <div class="box">
        <div class="pic">
          <img src="../assets/IMAGE4.jpg" alt="" />
        </div>
        <h2>design a solution</h2>
        <p>
          Duis cursus, mi quis viverra ornare, eros dolor interdum nulla, ut
          commodo diam libero vitae erat.
        </p>
      </div>
      <div class="box">
        <div class="pic">
          <img src="../assets/IMAGE5.jpg" alt="" />
        </div>
        <h2>track the progress</h2>
        <p>
          Aenean faucibus nibh et justo cursus id rutrum lorem imperdiet. Nunc
          ut sem vitae risus tristique posuere.
        </p>
      </div>
    </div>
  </div>
</template>
<script setup></script>
<style lang="scss" scoped>
.main {
  width: 1440px;
  height: 625px;
  background: #fff;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

h1 {
  //   width: 394px;
  color: #333;
  text-align: center;
  font-family: Montserrat;
  font-size: 20px;
  font-style: normal;
  font-weight: 400;
  line-height: 36px; /* 156.522% */
  text-transform: uppercase;
  margin-top: 20px;
  margin-bottom: 73px;
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
  margin-top: 38px;
}

p {
  width: 297px;
  color: #333;
  text-align: center;
  font-family: Vollkorn;
  font-size: 15px;
  font-style: normal;
  font-weight: 400;
  line-height: 22px; /* 146.667% */
  margin-top: 20px;
}

.out-box {
  width: 940px;
  height: 368px;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: row;
  gap: 20px;
}

.box {
  width: 319.984px;
  height: 368px;
  flex-shrink: 0;
}

.pic {
  width: 300px;
  height: 219px;
  flex-shrink: 0;
  background: #f5f5f5;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
