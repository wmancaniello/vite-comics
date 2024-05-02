<script>
export default {};
</script>

<template>
  <div class="footer">
    <div class="footer-top">
      <div class="list">
        <div class="left">
          <h2>DC COMICS</h2>
          <ul>
            <li><a href="">Characters</a></li>
            <li><a href="">Comics</a></li>
            <li><a href="">Movies</a></li>
            <li><a href="">TV</a></li>
            <li><a href="">Games</a></li>
            <li><a href="">Videos</a></li>
            <li><a href="">News</a></li>
          </ul>
          <h2>SHOP</h2>
          <ul>
            <li><a href="">Shop DC</a></li>
            <li><a href="">Shop DC Collectibles</a></li>
          </ul>
        </div>
        <div class="middle">
          <h2>DC</h2>
          <ul>
            <li><a href="">Terms Of Use</a></li>
            <li><a href="">Privacy policy (New)</a></li>
            <li><a href="">Ad Choices</a></li>
            <li><a href="">Advertising</a></li>
            <li><a href="">Jobs</a></li>
            <li><a href="">Subscriptions</a></li>
            <li><a href="">Talent Workshops</a></li>
            <li><a href="">CPSC Certificates</a></li>
            <li><a href="">Ratings</a></li>
            <li><a href="">Shop Help</a></li>
            <li><a href="">Contact Us</a></li>
          </ul>
        </div>
        <div class="right">
          <h2>SITES</h2>
          <ul>
            <li><a href="">DC</a></li>
            <li><a href="">MAD Magazine</a></li>
            <li><a href="">DC Kids</a></li>
            <li><a href="">DC Universe</a></li>
            <li><a href="">DC power Visa</a></li>
          </ul>
        </div>
      </div>
    </div>
    <div class="footer-end">
      <div>SIGN UP NOW</div>
      <div>FOLLOW US</div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.footer {
  .footer-top {
    height: 50vh;
    display: flex;
    background-image: url(../assets/img/footer-bg.jpg);
    // background-color: grey;

    .list {
      display: flex;
      margin-left: 100px;
      gap: 50px;
      padding-top: 50px;

      .left {
        display: flex;
        flex-direction: column;
        gap: 15px;
      }

      .middle {
        display: flex;
        flex-direction: column;
        gap: 15px;
      }

      .right {
        display: flex;
        flex-direction: column;
        gap: 15px;
      }
    }
  }

  .footer-end {
    height: 20vh;
    background-color: #303030;
    color: white;
    text-align: center;
  }

  h2 {
    color: white;
  }

  a {
    color: #959595;
  }
}
</style>
