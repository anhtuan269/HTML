<template>
  <div class="register">
    <div class="container">
      <h2>register your domain now !</h2>
      <form action="#">
        <label for="domain">
          <input
            type="text"
            id="domain"
            placeholder="Find your perfect domain name..."
          />
        </label>
        <label for="select">
          <select name="" id="select">
            <option value="" selected=".com"> .COM</option>
            <option value="" > .NET</option>
            <option value="" > .CO.IN</option>
            <option value="" > .WEDSITE</option>
            <option value="" > .ORG</option> 
          </select>
        </label>
        <label for="submit">
            <button>SEARCH DOMAIN</button>
        </label>
      </form>
      <div class="domains">
        <ul>
          <li>
            <div class="domain">
              <h3>
                <span class="dom">.com</span>
                <span class="price">$9.99</span>
              </h3>
              <span class="time">(1 Year)</span>
            </div>
          </li>
          <li>
            <div class="domain">
              <h3>
                <span class="dom">.Co.in</span>
                <span class="price">$9.99</span>
              </h3>
              <span class="time">(1 Year)</span>
            </div>
          </li>
          <li>
            <div class="domain">
              <h3>
                <span class="dom">.Website</span>
                <span class="price">$9.99</span>
              </h3>
              <span class="time">(1 Year)</span>
            </div>
          </li>
          <li>
            <div class="domain">
              <h3>
                <span class="dom">.Net</span>
                <span class="price">$9.99</span>
              </h3>
              <span class="time">(1 Year)</span>
            </div>
          </li>
          <li>
            <div class="domain">
              <h3>
                <span class="dom">.Org </span>
                <span class="price">$9.99</span>
              </h3>
              <span class="time">(1 Year)</span>
            </div>
          </li>
          <li>
            <div class="domain">
              <h3>
                <span class="dom">.Online</span>
                <span class="price">$9.99</span>
              </h3>
              <span class="time">(1 Year)</span>
            </div>
          </li>
          <li>
            <div class="domain">
              <h3>
                <span class="dom">.Store</span>
                <span class="price">$9.99</span>
              </h3>
              <span class="time">(1 Year)</span>
            </div>
          </li>
          <li>
            <div class="domain">
              <h3>
                <span class="dom">.biz</span>
                <span class="price">$9.99</span>
              </h3>
              <span class="time">(1 Year)</span>
            </div>
          </li>
        </ul>
      </div>
      <a href="#" class="border border-2 rounded-pill"> Domain Price List</a>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style scoped>
.register {
  margin: 50px 50px;
}
h2 {
  text-transform: uppercase;
  font-weight: 700;
  font-size: 40px;
  margin-bottom: 50px;
}
form {
    display: flex;
    justify-content: center;
    align-items: center;
    cursor: pointer;
    margin-bottom: 50px;
}
#domain {
    width:600px;
    height:50px;
    border:1px solid #222;
    border-radius: 10px 0 0 10px;
    padding: 0 15px;
}
#select {
    height: 50px;
    margin-left:-1px;
    padding:  0  10px  0 15px ;
    background-color: #dedede;
        position: relative;
    top: -0.25px;
}
button {
    width:200px;
    height:50px;
    background-color: #46af00;
    color:#fff;
    font-weight:600;
    border-radius: 0 10px 10px 0;
    border: 1px solid #222;
    transition: all 0.3s ease-in;
}
.domains {
    margin-bottom: 50px;
}
ul {
    display: flex;
    justify-content: space-between;
    background-color: #dedede;
    padding: 0 30px;
}
ul li {
    list-style-type: none;
}
h3 {
    margin-bottom: 0;
}
.dom {
    font-size: 1.5rem;
    font-weight:700;
}
.price {
    margin-left: 10px;
    font-size: 0.8rem;
    font-weight:600;
}
.time {
    font-weight: 600;
    font-size: 0.9rem;
}
a {
    text-decoration: none;
    padding: 10px 30px;
    color:#222;
    margin-top: 30px;
}
</style>
