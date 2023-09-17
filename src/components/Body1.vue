<template>
  <div class="main">
    <div class="image">
      <img src="../assets/bottom.jpg" alt="" />
    </div>
    <div class="main-text">
      <div class="main-text-context">
        <p>
          Minimalist is a full-service digital creative agency located in
          Ontorio Canada. We focus on design, consulting, technology, and
          photography. We’ve been building unique digital products, platforms,
          and experiences for the past 6 years. Let us help your company grow.
        </p>
      </div>

      <button type="submit">Get in Touch</button>
    </div>
  </div>
</template>
<script setup></script>
<style lang="scss" scoped>
.main {
  width: 1440px;
  height: 289px;
  flex-shrink: 0;
  background-color: #fefec9;
  display: flex;
  justify-content: center;
  flex-direction: column;
  position: relative;
}

.image {
  position: absolute;
  top: 0;
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

.main-text {
  width: 940px;
  height: 168px;
  flex-shrink: 0;
  position: absolute;
  top: 0;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 100%;
  margin-top: 60px;
}

.main-text-context {
  width: 940px;
  color: #47474f;
  text-align: center;
  font-family: Vollkorn;
  font-size: 18px;
  font-style: normal;
  font-weight: 400;
  line-height: 25px;
}

button {
  width: 159px;
  height: 53px;
  border-color: #8bcac3;
  background-color: #fefec9;
  color: #47474f;
  text-align: center;
  font-family: Vollkorn;
  font-size: 17px;
  font-style: italic;
  font-weight: 400;
  line-height: 22px; /* 129.412% */
  margin-top: 21.95px;
}

button:hover {
  border-radius: 10px;
}
</style>
