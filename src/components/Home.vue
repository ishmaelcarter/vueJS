<template>
  <div class="app-body">
  <div id="about">
   <router-link to="/about" class='yellow'>About</router-link>
  </div>
  <div id="projects">
   <router-link to="/construction" class='red'>Projects</router-link>
  </div>
  <div id="contact">
   <router-link to="/construction" class='grey'>Contact</router-link>
  </div>
  <div id="page4">
   <router-link to="/construction" class='pink'>Music</router-link>
  </div>
  <div id="page5">
   <router-link to="/construction" class='orange'>Movies</router-link>
  </div>
  <div id="page6">
   <router-link to="/construction" class='blue'>Miscellaneous</router-link>
  </div>
  </div>
</template>

<script>
require('material-design-lite')
export default {
  name: 'Home',
  data () {
    return {
      msg: 'Welcome',
      intro: ''
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
  font-size: 100%;
}
ul {
  list-style-type: none;
  padding: 0;
}

ul {
  display: block;
  width: 100%;
  margin: auto;
}

li {
  display: block;
  width: 100%;
  margin: auto;
}

a {
  font-family: 'Nunito', sans-serif;
  font-size: 140%;
  font-weight: bold;
  letter-spacing: -1px;
}

.nav1 {
  background-color: #a8e43b;
}

.nav2 {
  background-color: #bc7ac8;
}

.nav3 {
  background-color: #56a7bf;
}

.nav4 {
  background-color: #1e678d;
}


img {
  display: block;
  max-width: 25%;
  max-height: 25%;
  margin: auto;
  border-radius: 50%;
}

.top {
  position: absolute;

}

.app-body {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  width: 100%;
}

.app-body #about,#projects,#contact,#page4,#page5,#page6 {
  display: block;
  width: 49%;
  height: 33vh;
  margin: auto;
  border: 3px solid #00838F;
  border-radius: 0%;
  -moz-box-shadow: 3px 4px #006064;
  -webkit-box-shadow: 3px 4px #006064;
  box-shadow: 3px 4px #006064;
  transition: .5s;
  -webkit-transition: .5s;
  -moz-transition: .5s;
  opacity: .9;
}

.app-body div a {
  display: block;
  width: 100%;
  height: inherit;
  text-align: left;
  text-decoration: none;
  padding-left: 15%;
  padding-top: 10%;
  transition: .5s;
  -webkit-transition: .5s;
  -moz-transition: .5s;
}

.app-body #about:hover .yellow{
  color: white;
}

.app-body #projects:hover .red{
  color: white;
}

.app-body #contact:hover .grey{
  color: white;
}

.app-body #page4:hover .pink{
  color: white;
}

.app-body #page5:hover .orange{
  color: white;
}

.app-body #page6:hover .blue{
  color: white;
}

.app-body div:hover {
      -moz-transform: scale(1.1);
      -webkit-transform: scale(1.1);
      -ms-transform: scale(1.1);
      transform: scale(1.1);
      opacity: 1;
      z-index: 1;
}

.yellow {
  color: #f8a62b;
}

.red {
  color: #d71f49;
}

.grey {
  color: #b5c2c8;
}

.pink {
  color: #f498ab;
}

.orange {
  color: #e6693a;
}

.blue {
  color: #6bb0cf;
}

#about {
  background: url('../assets/about.png') center no-repeat;
  background-size: 50%;
  background-color: #f8a62b;
}

#projects {
  background: url('../assets/projects.png') center no-repeat;
  background-size: 50%;
  background-color: #d71f49;
}

#contact {
  background: url('../assets/contact.png') center no-repeat;
  background-size: 50%;
  background-color: #b5c2c8;
}

#page4 {
  background: url('../assets/music.png') center no-repeat;
  background-size: 50%;
  background-color: #f498ab;
}

#page5 {
  background: url('../assets/movies.png') center no-repeat;
  background-size: 50%;
  background-color: #e6693a;
}

#page6 {
  background: url('../assets/clipboard.png') center no-repeat;
  background-size: 50%;
  background-color: #6bb0cf;
}

@media only screen
and (max-device-width : 600px) {
  .app-body #about,#projects,#contact,#page4,#page5,#page6 {
    width: 48%;
  }
}

.demo-card-wide.mdl-card {
  width: 512px;
}
.demo-card-wide > .mdl-card__title {
  color: #fff;
  height: 176px;
  background: url('../assets/logo.png') center;
  background-size: 50%;
}
.demo-card-wide > .mdl-card__menu {
  color: #fff;
}

button {
  padding: 20px;
  background: #fafafa;
  position: relative;
  border-radius: 50%;
}
</style>
