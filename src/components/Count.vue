<template>
  <div class="count-area">
      <div class="container">
          <div class="count">
              <p>Happy Clients</p>
              <h2>75,000</h2>
          </div>
           <div class="count">
              <p>Servers</p>
              <h2>2,400</h2>
          </div>
           <div class="count">
              <p>Dedicated Staff</p>
              <h2>1,500</h2>
          </div>
           <div class="count">
              <p>Awards Won</p>
              <h2>3,011</h2>
          </div>
      </div>
  </div>
</template>

<script>
</script>

<style scoped >
.count-area {
    margin: 60px 0 ;
}
.container {
    display: grid;
    grid-template-columns: 25% 25% 25% 25%;
    padding: 70px 0;
    border: 1px solid #ddd;
    box-shadow: 3px 3px 19px 1px  #dedede;
}
.count p {
    color: #888;
    font-size:1.3rem;
    font-weight:600;
}
.count h2 {
    font-weight:700;
    font-size:3.1rem;
}
</style>
