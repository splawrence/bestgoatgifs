<template>
<ul>
  <li><a class="active" href="#BARN YARD (home)">BARN YARD (home)</a></li>
  <li><a href="#Goats">GOATS</a></li>
  <li><a href="#GIFS">GIFS</a></li>
  <li><a href="#WHAT MORE COULD YOU WANT?">WHAT MORE COULD YOU WANT?</a></li>
</ul>

</template>

<script>
  export default {

  }

</script>

<style>
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #333;
}

li {
  float: left;
}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

li a:hover:not(.active) {
  background-color: #111;
}

.active {
  background-color: #2c2194;
}
</style>