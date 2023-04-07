
<template>
  <div>
    <div class="hero">
      <nav>
        <img src="/images/logoname.png" class="logo" />
      </nav>
      <div class="detel">
        <h1>I, Am Rubi <span>Yadav</span></h1>
        <p>This Is my Profiles Details</p>
        <a href="#">#DOWNLOAD CV</a>
      </div>
      <div class="image">
        <img src="images/download.jpeg" class="shap">
        <img src="images/my.jpeg" class="myprofile"/>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  font-family: sans-serif;
}
.hero {
  position: relative;
  width: 100%;
  height: 100vh;
  background: #eff4fd;
}
nav {
  display: flex;
  width: 84%;
  margin: auto;
  align-items: center;
  padding: 20px 0;
  justify-content: space-between;
}
nav ul li {
  display: inline-block;
  list-style: none;
  margin: 10px 20px;
}

.detel {
  margin-left: 8%;
  margin-top: 13%;
}
.logo {
  height: 70px;
  width: 120px;
  background-color: #eff4fd;
  padding: 10px;
}
.detel {
  font-size: 20px;
  color: #212121;
  margin-bottom: 20px;
}
span {
  color: orange;
}
.detel p {
  color: #555;
  line-height: 22px;
}
.detel a {
  background: #212121;
  padding: 10px 18px;
  text-decoration: none;
  font-weight: bold;
  color: #fff;
  display: inline-block;
  margin: 30px 0px;
  border-radius: 5px;
}
.image {
  width: 30%;
  height: 60%;
  position: absolute;
  bottom: 0;
  right: 100px;
  margin-top: 20px;
}
.image img {
  height: 100%;
  position: absolute;
  bottom: 100px;
  left: 50%;
  transform: translateX(-50%);
  transition: bottom 1s left 1s;
}

.profile2 {
  margin-top: 30px;
}
.image:hover .shap{
    bottom: 40px;
    

}

.image:hover .myprofile{
    left:45%

}
.shap{
    margin-top: 40px;
}

</style>