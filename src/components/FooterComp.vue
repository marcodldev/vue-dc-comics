<template>
  <footer>
    <div class="foot1 flex">
      <div class="margin flex between">
        <div class="navs">
          <div class="nav1 margleft">
            <nav>
              <h1>DC COMICS</h1>
              <ul>
                <li>Characters</li>
                <li>Comics</li>
                <li>Movies</li>
                <li>TV</li>
                <li>Games</li>
                <li>Videos</li>
                <li>News</li>
              </ul>
            </nav>

            <nav>
              <h1>SHOP</h1>
              <ul>
                <li>Shop DC</li>
                <li>Shop DC Collectibles</li>
              </ul>
            </nav>
          </div>

          <div class="nav2 margleft">
            <nav>
              <h1>DC</h1>
              <ul>
                <li>Term Of Use</li>
                <li>Privacy policy (New)</li>
                <li>Ad Choises</li>
                <li>Advertising</li>
                <li>Job</li>
                <li>Subscriptions</li>
                <li>Talent Workshops</li>
                <li>CPSC Certificates</li>
                <li>Ratings</li>
                <li>Shop Help</li>
                <li>Contact Us</li>
              </ul>
            </nav>
          </div>

          <div class="nav3 margleft">
            <nav>
              <h1>SITES</h1>
              <ul>
                <li>DC</li>
                <li>MAD Magazine</li>
                <li>DC Kids</li>
                <li>DC Universe</li>
                <li>DC Power Visa</li>
              </ul>
            </nav>
          </div>
        </div>

        <div>
          <img src="../assets/img/dc-logo-bg.png" alt="dclogo" />
        </div>
      </div>
    </div>

    <div class="foot2">
      <div class="margin flex between">
        <div>
          <button>SIGN-UP NOW!</button>
        </div>

        <div class="flex">
          <h2>FOLLOW US</h2>
          <div>
            <img src="../assets/img/footer-facebook.png" alt="facebook" />
            <img src="../assets/img/footer-twitter.png" alt="twitter" />
            <img src="../assets/img/footer-youtube.png" alt="youtube" />
            <img src="../assets/img/footer-pinterest.png" alt="pintarest" />
            <img src="../assets/img/footer-periscope.png" alt="periscope" />
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "FooterComp",
};
</script>

<style>
h2 {
  color: #0274bf;
  align-self: center;
  padding: 10px;
}

ul {
  padding: 0px;
}

.flex {
  display: flex;
}

.margin {
  width: 80%;
  margin: auto;
}

.foot1 {
  background-image: url("../assets/img/footer-bg.jpg");
  color: white;
}

.foot2 {
  background-color: #303030;
  padding: 20px;
}

.foot2 img {
  margin: 10px;
  cursor: pointer;
}

.foot2 button {
    align-self: center;
    margin: 0;
    padding: 10px;
    border: 3px solid #0274bf;
    color: white;
    background-color: #303030;
    cursor: pointer;

}

.between {
  justify-content: space-between;
}

.navs {
  display: flex;
  flex-wrap: wrap;
  padding: 20px 0px;
}

.margleft {
  padding-left: 40px;
}

li {
  text-align: left;
  color: grey;
}

nav h1 {
  padding: 10px 0px;
  text-align: left;
}

nav li {
  cursor: pointer;
  line-height: 1.5rem;
}
</style>