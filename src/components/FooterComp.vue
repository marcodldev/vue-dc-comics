<template>
  <footer>
    <div class="foot1 flex margin2">
      <div class=" flex between">
        <div class="navs">
          <div class="nav1 margleft">
            <nav>
              <h1>DC COMICS</h1>
              <ul>
                <li> <a href="#">Characters</a> </li>
                <li> <a href="#">Comics</a> </li>
                <li> <a href="#">Movies</a> </li>
                <li> <a href="#">TV</a> </li>
                <li> <a href="#">Games</a> </li>
                <li> <a href="#">Videos</a> </li>
                <li> <a href="#">News</a> </li>
              </ul>
            </nav>

            <nav>
              <h1>SHOP</h1>
              <ul>
                <li> <a href="#">Shop DC</a> </li>
                <li> <a href="#">Shop DC Collectibles</a> </li>
              </ul>
            </nav>
          </div>

          <div class="nav2 margleft">
            <nav>
              <h1>DC</h1>
              <ul>
                <li> <a href="#">Term Of Use</a> </li>
                <li> <a href="#">Privacy policy (New)</a> </li>
                <li> <a href="#">Ad Choises</a> </li>
                <li> <a href="#">Advertising</a> </li>
                <li> <a href="#">Job</a> </li>
                <li> <a href="#">Subscriptions</a> </li>
                <li> <a href="#">Talent Workshops</a> </li>
                <li> <a href="#">CPSC Certificates</a> </li>
                <li> <a href="#">Ratings</a> </li>
                <li> <a href="#">Shop Help</a> </li>
                <li> <a href="#">Contact Us</a> </li>
              </ul>
            </nav>
          </div>

          <div class="nav3 margleft">
            <nav>
              <h1>SITES</h1>
              <ul>
                <li> <a href="#">DC</a> </li>
                <li> <a href="#">MAD Magazine</a> </li>
                <li> <a href="#">DC Kids</a> </li>
                <li> <a href="#">DC Universe</a> </li>
                <li> <a href="#">DC Power Visa</a> </li>
              </ul>
            </nav>
          </div>
        </div>


      </div>
      <div class="logodc">
        <!-- <img src="../assets/img/dc-logo-bg.png" alt="dclogo" /> -->
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
    background-image: url('../assets/img/footer-bg.jpg');
    color: white;
    background-size: 100%;
    position: relative;
    height: 30rem;
  }

  .foot1 img {


    height: 30rem;
  }

  .foot2 {
    background-color: #303030;
    width: 100%;
    padding: 20px;
  }

  .margin2 {
    justify-content: space-around;
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
    line-height: 1.5rem;
  }

  li a {
    text-decoration: none;
    color: lightgray;
  }

  .logodc {
    background-image: url('../assets/img/dc-logo-bg.png');
    background-repeat: no-repeat;
    width: 35rem;
    height: 100%;
  }
</style>