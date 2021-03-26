<template>
  <div class="footer-area">
    <div class="container">
      <div class="footer">
        <div class="item">
          <h4>Quick Link</h4>
          <ul>
            <li><a href="#"> Domain</a></li>
            <li><a href="#"> Hosting</a></li>
            <li><a href="#"> Technology</a></li>
            <li><a href="#"> Offer</a></li>
            <li><a href="#"> Contacts Us</a></li>
          </ul>
        </div>
        <div class="item">
          <h4>Account</h4>
          <ul>
            <li><a href="#"> My Account</a></li>
            <li><a href="#"> My Renewals</a></li>
            <li><a href="#"> Create Account</a></li>
            <li><a href="#"> Reseller Hosting</a></li>
            <li><a href="#"> Shared Hosting</a></li>
          </ul>
        </div>
        <div class="item">
          <h4>Product</h4>
          <ul>
            <li><a href="#"> Control Panel</a></li>
            <li><a href="#"> Dedicated Hosting </a></li>
            <li><a href="#"> Domain Transfer</a></li>
            <li><a href="#"> Reseller Hosting</a></li>
            <li><a href="#"> Shared Hosting</a></li>
          </ul>
        </div>
        <div class="item">
          <h4>Newsletter</h4>
          <ul>
            <li><a href="#"> Sing Up news and special offers</a></li>
            <li>
              <input type="text" placeholder="Enter Your Email Address.." />
            </li>
            <li>
              <button class="border border-2 rounded-pill">SUBSCRIBE</button>
            </li>
          </ul>
        </div>
      </div>
      <p class="fllow">Follow Us On</p>
      <div class="more-info">
        <div class="left-info">
          <div class="socail">
            <ul class="social-icon">
              <li>
                <i class="fab fa-facebook-f"></i>
              </li>
              <li>
                <i class="fab fa-instagram-square"></i>
              </li>
              <li>
                <i class="fab fa-youtube"></i>
              </li>
              <li>
                <i class="fab fa-google-plus-g"></i>
              </li>
              <li>
                <i class="fab fa-twitter"></i>
              </li>
              <li>
                <i class="fab fa-pinterest-p"></i>
              </li>
            </ul>
          </div>
        </div>
        <div class="right">
          <div class="payment">
            <img src="../assets/image/img-payment.png" alt="" />
          </div>
        </div>
      </div>
    </div>
    <div class="copy-right">
      <div class="container">
        <div class="left">
          <p>Coppyright © 2019 Companyname.com.All Right Reserved</p>
        </div>
        <div class="right">
          <ul>
            <li>
              <a href="#"> About Us</a>
            </li>
            <li>
              <a href="#"> Sitemap</a>
            </li>
            <li>
              <a href="#"> Legals</a>
            </li>
            <li>
              <a href="#">Privacy Policy</a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
</script>

<style scoped>
.copy-right {
    background-color: #222;
    margin-top: 30px;
    padding: 15px 0;
}
.copy-right .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.left p {
    color:#fff;
    font-size: 0.9rem;
}
.right ul {
    display: flex;
    align-items: center
}
.right ul li {
    margin: 5px 0px 0;
    padding: 0 10px;
    border-right: 1px solid #ddd;
}
.right ul li:last-child {
    border-right: 0;
}
.right ul li a {
    font-size: 0.9rem ;
}
.footer-area {
  background-color: #333;
  padding: 50px 0 0;
}
.footer {
  margin: 0 0 50px;
  background-color: #444;
  display: grid;
  grid-template-columns: 25% 25% 25% 25%;
  padding: 20px 0;
}
li {
  list-style: none;
  padding: 0 0 10px;
}
li a {
  text-decoration: none;
  color: #fff;
  transition: all 0.3 ease-in-out;
  padding: 10px 0;
}
li a:hover {
  color: #46af00;
}
.item {
  text-align: left;
  margin: 0 20px;
}
h4 {
  color: #fff;
  font-weight: 600;
  font-size: 1.3rem;
  margin-bottom: 15px;
}
li input {
  width: 100%;
  padding: 5px 20px;
  border-radius: 50px;
  margin-top: 15px;
}
li button {
  margin-top: 15px;
  padding: 10px 30px;
  background-color: #46af00;
  color: #fff;
  font-weight: 700;
  transition: all 0.3 linear;
  letter-spacing: 1px;
}
li button:hover {
  background-color: #fff;
  color: #222;
  border: 1px solid #fff !important;
}
.follow {
  text-align: left;
  color: #fff;
  margin-bottom: 5px;
}
.social-icon {
  display: flex;
  align-items: center;
}
.social-icon li {
  margin: 0 10px;
}
.social-icon li:first-child {
  margin-left: 0;
}
.social-icon li i {
  color: #fff;
  font-size: 1.5rem;
}
</style>
