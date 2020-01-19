<template>
<div class="container mw-100 p-0">
  <body>
    <div class="top-container">
      <img class="top-cloud" src="~/assets/cloud.png" alt="cloud-img" />
      <h1>I'm Takuya Ueno.</h1>
      <p>a programmer</p>
      <img class="bottom-cloud" src="~/assets/cloud.png" alt="cloud-img" />
      <img src="~/assets/mountain.png" alt="mountain-img" />
    </div>
    <div class="middle-container">
      <div class="profile">
        <img src="~/assets/profile.jpg" alt />
        <h2 class="mt-1">Hello.</h2>
        <p>
          大学卒業後、イギリスに
          3 ヶ月語学留学、その後シンガポールで海外引越コーディ
          ネーターとして 2 年間働き、台湾で 1 年間語学留学をした後、ワーキングホリデー
          で特許翻訳、海外引越コーディネーターとして就業。その後リモートで Web システム開発の仕事をしておりました。
        </p>
      </div>
      <hr />
      <div class="skills">
        <div class="skill-row mb-0">
          <div>
            <img class="computer" src="~/assets/computer.png" alt />
          </div>
          <div class="text-left overflow-hidden">
            <h3>Language</h3>
            <p class="computer-p">HTML5, CSS3, Javascript, Ruby</p>
            <h3>Framework</h3>
            <p>Bootstrap, Vue.js, Nuxt.js, Ruby on Rails</p>
            <h3>Infrastructure</h3>
            <p>Heroku, MySQL, Docker, Jenkins, Slack, Git, Sourcetree, Bitbucket</p>
          </div>
        </div>
        <nuxt-link to="portfolio" class="btn text-center">Portfolio</nuxt-link>
      </div>
      <hr />
      <div class="contact-me">
        <h2>Get In Touch</h2>
        <h3>Lorem ipsum dolor sit amet, non elit.</h3>
        <p>
          Lorem ipsum dolor sit amet, in quis, aenean amet. Phasellus sodales,
          tellus donec dui, ornare erat.
        </p>
        <br />
        <a class="btn" href="mailto:name@email.com">CONTACT ME</a>
      </div>
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
