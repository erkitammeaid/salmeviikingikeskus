<template>
  <nav>
    <div class="mainNav">
      <ul>
        <div>
          <li><a href="./mainpage.vue">Avaleht</a></li>
          <li><a href="./tegevused.vue">Tegevused</a></li>
          <li><a href="./salme-leiud.vue">Salme leiud</a></li>
          <li><a href="">Info</a></li>
          <li><a href="">Galerii</a></li>
        </div>
      <div class="languages">
          <a href=""><img class="EstoniaFlag" src="../assets/Est-flag.png" alt=""></a>
          <a href=""><img class="UkFlag" src="../assets/Uk-flag.png" alt=""></a>
      </div>
      </ul>
    </div>
  </nav>
  <div class="footer">footer</div>
</template>


<style>
ul{
  display: flex;
  justify-content: space-between;
}
.languages {
    display: flex;
    justify-content:flex-end ;
    width: auto;
}
.UkFlag {
    padding-left: 10px;
    height: 32px;
    width: 64px;
}
.EstoniaFlag {
    padding-right: 10px;
    height: 32px;
    width: 64px;
}
* {
  margin: 0;
  padding: 0;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
body {
  font-family: 'Skranji', cursive;
}
h1,
h2,
h3,
h4,
h5,
h6,
a {
  margin: 0;
}
a {
  color: inherit;
}
nav {
  top: 0%;
  width: 100%;
  position: left;
  background-color: #6A96D8;
}
.mainNav {
  padding: 1rem 6rem;
  margin: 0 auto;
  text-align: left;
}
.mainNav ul li {
  list-style: none;
  margin: 0 10px;
  display: inline-block;
}
.mainNav ul li a:hover {
  padding: 12px;
  color: #B6B6B6;
}
.mainNav ul li a {
  margin: 8px;
  padding: 10px;
  color: #fff;
  font-size: 1.2em;
  text-decoration: none;
  transition: all 0.3s ease-in-out;
}
.active {
  border-bottom: 2px solid #d0d7d9;
}
.mainNav p {
  margin-bottom: 16px;
  color: #fc0;
  font-weight: 700;
  font-size: 20px;
}
</style>
