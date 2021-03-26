<template>
    <div class="menu-area">
        <div class="container d-flex justify-content-between align-items-center">
            <div class="nav ">
                <ul class="d-flex justify-content-between align-items-center mb-0">
                    <li>
                        <a href="#"> Home</a>
                    </li>
                    <li>
                        <a href="#"> About us</a>
                    </li>
                    <li>
                        <a href="#"> Domain</a>
                    </li>
                    <li>
                        <a href="#"> Hosting </a>
                    </li>
                    <li>
                        <a href="#"> Technology</a>
                    </li>
                    <li>
                        <a href="#"> Offers</a>
                    </li>
                    <li>
                        <a href="#"> Contacts Us</a>
                    </li>
                </ul>
            </div>
            <div class="search">
                <i class="fas fa-search"></i>
            </div>
        </div>
    </div>

</template>
<script>

export default {}
</script>
<style scoped>
.menu-area {
    background-color: #222;
}
.menu-area ul li {
    list-style-type:none;
    padding: 15px 0px;
}
.menu-area ul li a {
    text-decoration: none;
    color:#fff;
    padding: 18px 10px;
    transition: all 0.3s linear;
}
.menu-area ul li a:hover {
    background-color:#46af00;
}
.menu-area ul li a:active {
    background-color: #46af00;
}
.search i {
    color:#fff;
    font-size:1.1em;
}
.search {
    padding: 15px 20px;
    background-color:#46af00;
    cursor:pointer;
}

</style>
