<template>
  <div class="hello">
    <h1></h1>
    <img src="../assets/headshot.png">
    <nav>
      <ul>
        <li class="nav1">Contact</li>
        <li class="nav2">Misc.</li>
        <li class="nav3">Projects</li>
      </ul>
    </nav>
    <div>

    </div>
  </div>
</template>

<script>
export default {
  name: 'Header',
  data () {
    return {

    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}

ul {
  display: block;
  width: 100%;
}

li {
  display: inline-block;
  width: 25%;
}

a {
  color: #42b983;
}

img {
  display: block;
  max-width: 20%;
  margin: auto;
  border-radius: 50%;
}

.top {
  position: absolute;

}
</style>
