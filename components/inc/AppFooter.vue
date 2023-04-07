<template>
  <div>
    <footer>
      <div class="row primary">
        <div class="column about">
          <h3>Developer</h3>

          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Vitae,
            voluptatem corporis error non,
          </p>

          <!-- <a class="navbar-brand" href="#">
          <img
            src="https://cdn.dribbble.com/users/2594111/screenshots/17902714/media/3d6fc4a3d1359f607f4876367d6709eb.jpg?compress=1&resize=400x300"
            class="logo-img"
            alt=""
          />
        </a> -->

          <div class="social">
            <i class="fa-brands fa-facebook-square"></i>
            <i class="fa-brands fa-instagram-square"></i>
            <i class="fa-brands fa-twitter-square"></i>
            <i class="fa-brands fa-youtube-square"></i>
            <i class="fa-brands fa-whatsapp-square"></i>
          </div>
        </div>

        <div class="column links">
          <h3>Links</h3>

          <ul>
            <li>
              <a href="#faq">FACEBOOK</a>
            </li>
            <li>
              <a href="#cookies-policy">TWITER</a>
            </li>
            <li>
              <a href="#terms-of-services">Terms Of Service</a>
            </li>
            <li>
              <a href="#support">Support</a>
            </li>
          </ul>
        </div>

        <div class="column links">
          <h3>Links</h3>
          <ul>
            <li>
              <a href="#faq">F.A.Q</a>
            </li>
            <li>
              <a href="#cookies-policy">Cookies Policy</a>
            </li>
            <li>
              <a href="#terms-of-services">Terms Of Service</a>
            </li>
            <li>
              <a href="#support">Support</a>
            </li>
          </ul>
        </div>

        <div class="column subscribe">
          <h3>Write Your Email</h3>
          <div>
            <input type="email" placeholder="Your email id here" />
            <button>Subscribe</button>
          </div>
        </div>
      </div>

      <div class="row copyright">
        <div class="footer-menu">
          <a href="">Home</a>
          <a href="">About Us</a>
          <a href="">Contact Us</a>
          <a href="">Search</a>
          <a href="">Galary</a>
        </div>
        <p>Hello © 2023 Rubi Developer</p>
      </div>
    </footer>
  </div>
</template>

<script>
export default {};
</script>

<style>
body {
  padding: 0;
  margin: 0;
  min-height: 100vh;
  display: flex;
  align-items: flex-end;
}
footer {
  background-color: #121315;
  color: #a7a7a7;
  font-size: 16px;
}

footer * {
  font-family: "Poppins", sans-serif;
  box-sizing: border-box;
  border: none;
  outline: none;
}

.row {
  /* padding: 1em 1em; */
  /* padding: 10px; */
}
.row.primary {
  display: grid;
  grid-template-columns: 2fr 1fr 1fr 2fr;
  align-items: stretch;
}
.column {
  width: 100%;
  display: flex;
  flex-direction: column;
  padding: 0 2em;
  min-height: 15em;
}
h3 {
  width: 100%;
  text-align: left;
  color: white;
  font-size: 1.4em;
  white-space: nowrap;
}
ul {
  list-style: none;
  display: flex;
  flex-direction: column;
  padding: 0;
  margin: 0;
}
li:not(:first-child) {
  margin-top: 0.8em;
}
ul li a {
  color: #a7a7a7;
  text-decoration: none;
}
ul li a:hover {
  color: #2a8ded;
}
.about p {
  text-align: justify;
  line-height: 2;
  margin: 0;
}
input,
button {
  font-size: 1em;
  padding: 1em;
  width: 100%;
  border-radius: 5px;
  margin-bottom: 5px;
}
button {
  /* background-color: #c7940a; */
  color: white;

  background: linear-gradient(to right, purple, rgb(217, 3, 217));

  /* background: linear-gradient(to right, purple, rgb(217,) */
}
div.social {
  display: flex;
  justify-content: space-around;
  font-size: 2.4em;
  flex-direction: row;
  margin-top: 0.5em;
}
.social i {
  color: #bac6d9;
}

.copyright {
  padding: 0.3em 1em;
  background-color: #25262e;
}
.footer-menu {
  float: left;
  margin-top: 10px;
}

.footer-menu a {
  color: #cfd2d6;
  padding: 6px;

  text-decoration: none;
}
.footer-menu a:hover {
  color: #27bcda;
}
.copyright p {
  font-size: 0.9em;
  text-align: right;
}
.row {
  margin: 0px !important;
  padding: 0px !important;
}
@media screen and (max-width: 850px) {
  .row.primary {
    grid-template-columns: 1fr;
  }
}
</style> 