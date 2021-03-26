<template>
    <div class="logo-area">
        <div class="container  d-flex justify-content-between align-items-center">
            <div class="logo">
                <img src="../assets/image/logo.png" alt="">
            </div>
            <div class="support  d-flex justify-content-between align-items-center">
                <div class="item  d-flex justify-content-between align-items-center">
                    <i class="fas fa-comments"></i>
                    <p> Live Chat</p>
                </div>
                 <div class="item  d-flex justify-content-between align-items-center">
                    <i class="fas fa-headset"></i>
                    <p> Support</p>
                </div>
                 <div class="item border border-2 rounded-pill  d-flex justify-content-between align-items-center">
                    <i class="fas fa-shopping-cart"></i>
                    <p> View Cart </p>
                </div>
            </div>
        </div>
    </div>

</template>
<script>

export default{

}
</script>
<style scoped>
.logo-area {
    margin: 20px 0;
}
.logo-area .container .logo img {
    width: 50px;
    height:50px;
}
.item {
    margin: 0 10px;
    cursor:pointer;
    
}
.item:last-child {
    margin-right: 0px;
}
.item.border {
    padding: 5px 15px;

}
.border {
    border-color: #46af00!important;
    transition: all 0.3s ease;

}
p {
    color: #222;
    font-weight:600;
}
i {
    margin-right:5px;
}
.border:hover i  {
    color:#fff;
}
 .border:hover p{
     color:#fff;
 }
</style>
