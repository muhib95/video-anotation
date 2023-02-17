<template>
  <div class="header">
    <div class="header-nav">
      <ul>
        <li><a href="" class="logo">Video Anotation</a></li>
        <li><a href="">Platform</a></li>
        <li><a href="">Ecosystem</a></li>
        <li><a href="">Services</a></li>
        <li><a href="">Enterprise</a></li>
        <li><a href="">Pricing</a></li>
        <li><a href="">Blog</a></li>
        <li><a href="">Learn</a></li>
      </ul>
    </div>
    <div class="nav-login">
      <ul>
        <li><a href="">Log in</a></li>
        <li><a href="">Get a demo</a></li>
        <li><button class="btn">Try for free</button></li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.header {
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: beige;
  padding: 10px;
}
.header-nav ul {
  font-weight: 400;
  list-style: none;
  display: flex;
  justify-content: center;
  align-items: center;
}
.header-nav a {
  margin-right: 10px;
  text-decoration: none;
  color: black;
}
.nav-login ul {
  display: flex;
  list-style: none;
  align-items: center;
}
.nav-login a {
  margin-right: 25px;
  text-decoration: none;
  color: black;
}
.logo {
  font-size: larger;
  font-weight: 700;
}
.btn {
  background: palevioletred;
  color: aliceblue;
  border: none;
  padding: 8px;
  text-align: center;
  font-size: 16px;
  cursor: pointer;
}
</style>
