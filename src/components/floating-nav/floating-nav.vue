<template>
  <nav>
    <ul>
      <li>
        <a href="https://www.facebook.com/parthvyas17/">
          <i class="fab fa-facebook-f"></i>
          <span>Facebook</span>
        </a>
      </li>
      <li>
        <a href="https://twitter.com/parth_vyas17">
          <i class="fab fa-twitter"></i>
          <span>Twitter</span>
        </a>
      </li>
      <li>
        <a href="mailto:parth-vyas@outlook.com">
          <i class="fas fa-envelope"></i>
          <span>E-mail</span>
        </a>
      </li>
      <li>
        <a href="https://www.linkedin.com/in/parth17/">
          <i class="fab fa-linkedin-in"></i>
          <span>Linkedin</span>
        </a>
      </li>
      <li>
        <a href="https://github.com/VyasLogic">
          <i class="fab fa-github"></i>
          <span>Github</span>
        </a>
      </li>
    </ul>
  </nav>
</template>

<style scoped>
nav {
  position: fixed;
  width: 70px;
  margin-top: 250px !important;

  transition: all 0.3s linear;
  box-shadow: 2px 2px 8px 0px rgba(0, 0, 0, 0.4);
}
nav li {
  height: 60px;
  position: relative;
  top: 70;
  left: 0;
}
nav li a {
  color: white;
  display: block;
  height: 100%;
  width: 100%;
  line-height: 60px;
  padding-left: 25%;
  border-bottom: 1px solid rgba(0, 0, 0, 0.4);
  transition: all 0.3s linear;
}
nav li:nth-child(1) a {
  background: #4267b2;
}
nav li:nth-child(2) a {
  background: #1da1f2;
}
nav li:nth-child(3) a {
  background: #e1306c;
}
nav li:nth-child(4) a {
  background: #2867b2;
}
nav li:nth-child(5) a {
  background: #333;
}
nav li:nth-child(6) a {
  background: #ff0000;
}
nav li a i {
  position: absolute;
  top: 17px;
  left: 20px;
  font-size: 27px;
}
ul li a span {
  display: none !important;
  font-weight: bold;
  letter-spacing: 1px;
  text-transform: uppercase;
}
a:hover {
  z-index: 1;
  width: 200px;
}
ul li:hover a span {
  padding-left: 30%;
  display: block !important;
}
</style>
