<template>
 <div class="header">
   <div class="container d-flex justify-content-between align-items-center">
       <div class="left-header d-flex  " >
         <div class="email d-flex align-items-center">
           <i class="far fa-envelope mr-1"></i>
           <p> contact@companyname.com</p>
         </div>
         <div class="phone d-flex align-items-center">
           <i class="fas fa-phone-alt"></i>
           <p> 
             <span class="head" >Call Us: </span>
             <span class="number">1800-1234-1234-1234 </span>
           </p>
         </div>
       </div>
      <div class="right-header d-flex align-items-center">
        <div class="right d-flex align-items-center">
          <i class="fas fa-gift"></i>
          <p>Offers</p>
        </div>
        <div class="right d-flex align-items-center">
          <i class="fas fa-user"></i>
          <p>Login</p>
        </div>
        <div class="right d-flex align-items-center">
          <i class="fas fa-pen"></i>
          <p>Sign Up</p>
        </div>
     </div>
   </div>
 </div>
</template>

<script>
export default {
  props: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.header {
  background-color: #46af00;
  padding: 15px 0;
  color: #fff

}
.header .container .phone {
  margin-left: 20px;
}
.header .container .phone i {
  font-size: 1.1rem;
}
.header .container .phone  p {
  font-weight:600;
}
.right {
  padding: 0 10px;
  border-right: 1px solid #888;
}
.right:last-child{
border-right:none;
}
i {
  margin-right: 10px;
  color: #fff;
}
p {
  color: #fff;
}
span {
  color: #fff;
}
</style>
