<template>
  <footer class="top-footer">
      <div class="flex">
      <h1 class="footer-logo">estra inc.</h1>
      <nav class="footer-nav">
        <ul>
          <li><a href="#">home</a></li>
          <li><a href="#">about</a></li>
          <li><a href="#">service</a></li>
          <li><a href="#">works</a></li>
          <li><a href="#">price</a></li>
          <li><a href="#">contact</a></li>
        </ul>
      </nav>
     </div>
     <small>Copyright 2019 estra inc.All Rights Reserved</small>
  </footer>
</template>

<style scoped>
.top-footer{
  background: #000;
  text-align: center;
}
.flex{
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 70px;
  line-height: 70px;
}

.footer-logo{
  font-size: 20px;
  font-weight: bold;
  margin-left: 35px;
  color: #fff;
}

.footer-nav ul{
  display: flex;
}

.footer-nav li{
  margin-right: 35px;
  font-size: 16px;
}

.footer-nav a{
  color: #fff;
  text-decoration: none;
}

small{
  color: #fff;
}
</style>