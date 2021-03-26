<template>
  <div class="services-area">
    <div class="container">
      <h2>OURS SERVICES</h2>
      <div class="services">
        <div class="db">
          <div class="avatar">
            <img src="../assets/image/ana.png" alt="">
          </div>
          <h4 class="name">Complete Analisys</h4>
          <p>
            Lorem ipsum dolor sit amet consectetur elit. Excepturi
            autem modi ullam nulla quaerat, quae aspernatur nostrum quod placeat
            dolore atque molestias voluptatem aperiam, dolorem libero eius,
            assumenda vitae fugit?
          </p>
          <button class="border border-2 rounded-pill">Continute</button>
        </div>
        <div class="db">
          <div class="avatar">
            <img src="../assets/image/data.png" alt="">
          </div>
          <h4 class="name">Unlimited Strorage</h4>
          <p>
            Lorem ipsum dolor sit amet consectetur elit. Excepturi
            autem modi ullam nulla quaerat, quae aspernatur nostrum quod placeat
            dolore atque molestias voluptatem aperiam, dolorem libero eius,
            assumenda vitae fugit?
          </p>
          <button class="border border-2 rounded-pill">Continute</button>
        </div>
        <div class="db">
          <div class="avatar">
            <img src="../assets/image/transefer.png" alt="">
          </div>
          <h4 class="name">Domain Transfer</h4>
          <p>
            Lorem ipsum dolor sit amet consectetur elit. Excepturi
            autem modi ullam nulla quaerat, quae aspernatur nostrum quod placeat
            dolore atque molestias voluptatem aperiam, dolorem libero eius,
            assumenda vitae fugit?
          </p>
          <button class="border border-2 rounded-pill">Continute</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>
<style scoped>
.services-area {
  margin : 50px 0 80px;
} 
h2 {
  margin-bottom:50px;
  text-transform: uppercase;
  font-weight:700;
}
h4 {
  margin-bottom: 30px;
  font-weight:700;
}
.services {
  display: grid;
  grid-template-columns: 33.33% 33.33% 33.33%;
}
.db {
  background-color:#eee;
  margin: 0 20px;
  padding:40px;
}
.avatar {
  padding: 30px 0;
    width: 140px;
    height: 140px;
    margin: 0px auto 30px;
    background-color: #fff;
    border-radius: 50%;
    align-items: center;
}
.avatar img {
  width: 100px;
    position: relative;
    top: -10px;
}
button {
  margin: 30px 0;
  padding: 10px 40px;
  text-transform: uppercase;
  font-weight:600;
}
p {
  text-align:left;
}
</style>
