<template>
  <div class="app-body">
  <div class='home-wrapper'>
    <router-link to="/" class='home'></router-link>
  </div>
    <div class="demo-card-wide mdl-card mdl-shadow--2dp">
  <div class="mdl-card__supporting-text">
    Sorry, this page is currently under construction.
  </div>
  <div class="mdl-card__actions mdl-card--border">
    <a class="mdl-button mdl-button--colored mdl-js-button mdl-js-ripple-effect"><router-link to="/">Go Home</router-link>
    </a>
  </div>
</div>
  </div>
</template>

<script>
require('material-design-lite')
export default {
  name: 'Construction',
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

.home {
  margin: 3%;
  background-color: #E0F7FA;
  background-image: url('../assets/home.png');
  background-size: 80%;
  background-position: center;
  background-repeat: no-repeat;
  border-radius: 50%;
  display: block;
  width: 45px;
  height: 45px;
  -moz-box-shadow: 3px 3px #006064;
  -webkit-box-shadow: 3px 3px #006064;
  box-shadow: 3px 3px #006064;
  transition: .5s;
  -webkit-transition: .5s;
  -moz-transition: .5s;
}

.home:hover{
  -moz-transform: scale(1.2);
  -webkit-transform: scale(1.2);
  -ms-transform: scale(1.2);
  transform: scale(1.2);
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

button {
  padding: 20px;
  background: #fafafa;
  position: relative;
  border-radius: 50%;
}

.demo-card-wide.mdl-card {
  display: block;
  width: 80%;
  margin: auto;
}
.demo-card-wide > .mdl-card__title {
  color: #fff;
  height: 176px;
  background: url('../assets/construction.jpg') center / cover;
}
.demo-card-wide > .mdl-card__menu {
  color: #fff;
}

.demo-card-wide.mdl-card a {
  text-decoration: none;
  color: #0097A7;
  font-weight: bold;
  font-family: 'Nunito', sans-serif;
}

.mdl-card__supporting-text {
  font-family: 'Nunito', sans-serif;
  width: 100%;
}

.home-wrapper {
  display: block;
  width: 100%;
}
</style>
