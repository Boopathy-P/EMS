<template>
    <div>
        <nav class="navbar sticky navbar-expand-lg navbar-light bg-white shadow">
        <div class="container">
            <a class="navbar-brand" href="#Home"><img v-bind:src="LogoImage" class="logo-img" alt="">
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
                <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">Home</a>
                </li>
                <li class="nav-item">
                <a class="nav-link" href="#">About us</a>
                </li>
                <li class="nav-item">
                <a class="nav-link" href="#">Event Services</a>
                </li>
                <li class="nav-item">
                <a class="nav-link" href="#">Contact Us</a>
                </li>
               
            </ul>
            <form class="d-flex">
                <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                <button class="btn btn-outline-success" type="submit">Search</button>
            </form>
            </div>
        </div>
        </nav>
    </div>
  
</template>

<script>
export default {
    name: 'AppHeader',
    data(){
        return{
            LogoImage:require("../Eventmanagement/image/Logo2.webp")
        }
    }

}
</script>
<style scoped>
.logo-img{
    width: 170px;
    height: 50px;
}
.nav-item{
  
    font-size: 20px;
}
</style>







