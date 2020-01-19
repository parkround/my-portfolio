<template>
<div class="container mw-100 p-0">
  <body>
    <div class="top-container">
      <img class="top-cloud" src="~/assets/cloud.png" alt="cloud-img" />
      <h1>Portfolio</h1>
      <img class="bottom-cloud" src="~/assets/cloud.png" alt="cloud-img" />
      <img src="~/assets/mountain.png" alt="mountain-img" />
    </div>
    <div class="middle-container">
      <h3 class="m-5">工事施行管理システム</h3>
      <p>Vue.js、 Ruby on Railsを使って、足場工事における予定、見積、現場、請求等を管理するシステムの実装、デバッギングを行いました。</p>
      <img class="mb-5" style="width:80%" src="~/assets/portfolio/cios01.png" alt="cios" />
      <p>レスポンシブデザインを実装しました。</p>
      <img class="mb-5" style="width:30%" src="~/assets/portfolio/cios02.png" alt="cios" />
      <h3 class="m-5">ボルダリングジムウェブサイト（練習用）</h3>
      <a href="https://pogo-climbing-gym.herokuapp.com/" target="_blank">
        <img class="mb-5" style="width:80%" src="~/assets/portfolio/pogo01.png" alt="cios" />
      </a>
    </div>

    <div class="bottom-container">
      <a class="footer-link" href="https://www.linkedin.com/">LinkedIn</a>
      <a class="footer-link" href="https://twitter.com/">Twitter</a>
      <a class="footer-link" href="https://www.appbrewery.co/">Website</a>
      <p>© 2020 Takuya Ueno</p>
    </div>
  </body>
</div>
</template>

<script>
import Logo from "~/components/Logo.vue";

export default {
  components: {
    Logo
  }
};
</script>

<style>
body {
  margin: 0;
  text-align: center;
}

hr {
  border-style: dotted none none;
  border-width: 7px;
  width: 10%;
  border-color: grey;
  margin: 50px auto;
}

.top-container {
  background-color: #b2e4d5;
  position: relative;
  padding-top: 100px;
}

.profile {
  width: 50%;
  margin: auto;
}
.profile img {
  width: 200px;
  margin-top: 30px;
  border-radius: 50%;
}
h1 {
  margin: 0;
}

.top-cloud {
  position: absolute;
  top: 30px;
  right: 200px;
}

.bottom-cloud {
  position: absolute;
  left: 100px;
  bottom: 300px;
}

.top-container h1 {
  font-size: 4rem;
  color: #66bfbf;
}
.top-container p {
  font-size: 2.5rem;
  color: #66bfbf;
  font-weight: normal;
  margin: 0;
}

.top-container {
  line-height: 2;
}

.skill-row {
  width: 50%;
  margin: 50px auto;
  line-height: 2;
  text-align: left;
}

.computer {
  width: 20%;
  float: left;
  margin-right: 30px;
}

.computer-p {
  clear: left;
}

.chillies-p {
  clear: right;
}
.chillies {
  width: 20%;
  float: right;
  margin-left: 30px;
}

h3 {
  color: #11999e;
}

a {
  color: #11999e;
}

h2 {
  color: #11999e;
}

.contact-me {
  width: 50%;
  margin: auto;
}

.bottom-container {
  background-color: #66bfbf;
  margin: 30px 0 0;
  padding: 30px;
}

.bottom-container p {
  margin: 0;
  padding: 30px 0 0;
  color: #eaf6f6;
}

.bottom-container a {
  padding: 30px;
  color: #11999e;
  text-decoration: none;
}

.btn {
  background-color: #66bfbf;
  color: white;
  padding: 10px;
  border-radius: 10px;
  text-decoration: none;
  margin: 30px;
}

a:hover {
  color: #eaf6f6;
}
</style>
