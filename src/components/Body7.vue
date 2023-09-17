<template>
  <div class="main">
    <input class="name" type="text" placeholder="Name" />
    <input class="email" type="email" placeholder="Email" />
    <input class="budget" type="number" placeholder="Budget" />
    <textarea
      class="description"
      type="text"
      placeholder="Describe your project..."
    />
    <button type="submit">Send Message</button>
    <img src="../assets/IMAGE26.jpg" alt="" />
    <h1>Minimal Template made in Webflow. All rights reserved.</h1>
  </div>
</template>
<script setup></script>
<style lang="scss" scoped>
.main {
  width: 1440px;
  height: 639px;
  flex-shrink: 0;
  background-color: black;
  display: flex;
  align-items: center;
  flex-direction: column;
}

.name {
  width: 564px;
  height: 57px;
  flex-shrink: 0;
  background: rgba(255, 255, 255, 0.18);
  margin-top: 69px;
  border: none;
  padding-left: 31px;
  box-sizing: border-box;
  font-family: Vollkorn;
  font-size: 17px;
  font-style: italic;
  font-weight: 400;
  line-height: 22px;
  color: #fff; /* Text color */
  text-align: left;
}

.name::placeholder {
  color: #fff;
  text-align: start;
  font-family: Vollkorn;
  font-size: 17px;
  font-style: italic;
  font-weight: 400;
  line-height: 22px; /* 129.412% */
}

.email {
  width: 564px;
  height: 57px;
  flex-shrink: 0;
  background: rgba(255, 255, 255, 0.2);
  border: none;
  padding-left: 31px;
  box-sizing: border-box;
  font-family: Vollkorn;
  font-size: 17px;
  font-style: italic;
  font-weight: 400;
  line-height: 22px;
  color: #fff; /* Text color */
  text-align: left;
}

.email::placeholder {
  color: #fff;
  text-align: start;
  font-family: Vollkorn;
  font-size: 17px;
  font-style: italic;
  font-weight: 400;
  line-height: 22px; /* 129.412% */
}

.budget {
  width: 564px;
  height: 57px;
  flex-shrink: 0;
  background: rgba(255, 255, 255, 0.18);
  border: none;
  padding-left: 31px;
  box-sizing: border-box;
  font-family: Vollkorn;
  font-size: 17px;
  font-style: italic;
  font-weight: 400;
  line-height: 22px;
  color: #fff; /* Text color */
  text-align: left;
}

.budget::placeholder {
  color: #fff;
  text-align: start;
  font-family: Vollkorn;
  font-size: 17px;
  font-style: italic;
  font-weight: 400;
  line-height: 22px; /* 129.412% */
}

.description {
  position: relative;
  width: 564px;
  height: 127px;
  flex-shrink: 0;
  background: rgba(255, 255, 255, 0.2);
  border: none;
  padding: 20px; /* Adjust padding */
  box-sizing: border-box;
  font-family: Vollkorn;
  font-size: 17px;
  font-style: italic;
  font-weight: 400;
  line-height: 22px;
  color: #fff; /* Text color */
  text-align: left;
}

.description::placeholder {
  color: #fff;
  font-family: Vollkorn;
  font-size: 17px;
  font-style: italic;
  font-weight: 400;
  line-height: 22px;
  position: absolute;
  top: 20px; /* Adjust as needed to position the placeholder */
  left: 30px; /* Adjust as needed to position the placeholder */
}

button {
  width: 210px;
  height: 53px;
  border-color: #8bcac3;
  background-color: black;
  color: #8bcac3;
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
img {
  width: 43px;
  height: 46px;
  margin-top: 37.05px;
}

h1 {
  color: rgba(255, 255, 255, 0.4);
  text-align: center;
  font-family: Vollkorn;
  font-size: 15px;
  font-style: normal;
  font-weight: 400;
  line-height: 22px; /* 146.667% */
  margin-top: 15.05px;
}
</style>
