<template>
  <div class="hosting-area">
    <div class="container">
      <h2>POPULAR PRICIING PACKAGES</h2>
      <div class="hostings">
        <div class="hosting">
          <div class="type bg-1">
            <h4>Standard Hosting</h4>
            <p>For individual Wedsite</p>
          </div>
          <div class="info">
              <ul>  
                  <li><p>Web Space 10GB</p></li>
                  <li><p>Bandwidth 100GB</p></li>
                  <li><p>Website 1</p></li>
                  <li><p>Email IDs Unlimited</p></li>
                  <li><p>Subdomain Unlimited</p></li>
                  <li><p>FPT Unlimited</p></li>
                  <li><p>MySQL DB Unliited</p></li>
              </ul>
          </div>
          <div class="price">
              <p>
                  <span class="pri">
                      <span class="up">$</span>69
                  </span>
                  <span class="month">
                      /mo
                  </span>
              </p>
          </div>
          <div class="continute">
              <button class="border border-2 rounded-pill">Continute</button>
          </div>
        </div>
        <div class="hosting">
          <div class="type bg-2">
            <h4>Classic Hosting</h4>
            <p>For Business owners</p>
          </div>
          <div class="info">
              <ul>  
                  <li><p>Web Space 100GB</p></li>
                  <li><p>Bandwidth 500GB</p></li>
                  <li><p>Website 1</p></li>
                  <li><p>Email IDs Unlimited</p></li>
                  <li><p>Subdomain Unlimited</p></li>
                  <li><p>FPT Unlimited</p></li>
                  <li><p>MySQL DB Unliited</p></li>
              </ul>
          </div>
          <div class="price">
              <p>
                  <span class="pri blue">
                      <span class="up blue">$</span>79
                  </span>
                  <span class="month">
                      /mo
                  </span>
              </p>
          </div>
          <div class="continute">
              <button class="border border-2 rounded-pill">Continute</button>
          </div>
        </div>
        <div class="hosting">
          <div class="type bg-3">
            <h4>Premium Hosting</h4>
            <p>For Company owners</p>
          </div>
          <div class="info">
              <ul>  
                  <li><p>Web Space Unlimited</p></li>
                  <li><p>Bandwidth Unlimited</p></li>
                  <li><p>Website 1</p></li>
                  <li><p>Email IDs Unlimited</p></li>
                  <li><p>Subdomain Unlimited</p></li>
                  <li><p>FPT Unlimited</p></li>
                  <li><p>MySQL DB Unliited</p></li>
              </ul>
          </div>
          <div class="price">
              <p>
                  <span class="pri green">
                      <span class="up green">$</span>69
                  </span>
                  <span class="month">
                      /mo
                  </span>
              </p>
          </div>
          <div class="continute">
              <button class="border border-2 rounded-pill">Continute</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style scoped>
.hosting-area {
    background-color: #eee;
    padding:50px;
}
.hostings {
    display: grid;
    grid-template-columns: 33.33% 33.33% 33.33%;
}
.hosting-area .hostings .hosting {
    margin: 0 20px 20px;
    background-color: #fff;
}
.hosting  .type {
    padding: 20px 0;
    background-color:#46af00;
}
h2 {
    margin: 0 0 50px 0 ;
    font-weight:700;

}
h4 {
    font-size: 1.7rem;
    font-weight:600;
    color:#fff;

}
.type p {
    color:#fff;
    margin-top:10px;
    font-weight:600;
}
li {
    list-style-type: none;
    padding-top: 10px;
}
li p {
    font-weight:600;
}
.info {
    padding: 20px  0 30px   ;
}
.price {
    background-color: #dedede;
    padding: 15px 0;
}
.pri {
    font-size: 2.5rem;
    color:#46af00;
    font-weight:700;
}
.month {
    font-weight:600;
}
.up {
    font-size: 2.5rem;
    color:#46af00;
    font-weight:700;
    position:relative;
    top: -10px;
    margin-right:8px;
}
.continute {
    margin:30px 0;
}
button {
    padding: 10px 40px;
    text-transform: uppercase;
    font-weight:600;
}
.blue {
    color: rgb(10, 93, 202)
}
.green {
    color: orange ;
}
</style>
