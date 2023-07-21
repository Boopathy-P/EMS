<template>
  <div id="carouselExampleCaptions" class="carousel slide">
    <div class="carousel-indicators bg-dark">
        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" class="active"  aria-label="Slide 1"></button>
        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" class="active" aria-label="Slide 2"></button>

    </div>
    

    <div class="Carousel-inner">
        <div class="carousel-item active">
            <img v-bind:src="BannerImg" class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block text-dark">
                <h5>
                    Upcoming Event
                </h5>
                <p>
                    Some content 
                </p>
            </div>
        </div>
        <div class="carousel-item">
            <img  v-bind:src="BannerImg" class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block text-dark">
                <h5>
                    Upcoming Event
                </h5>
            </div>
        </div>
        <div class="carousel-item">
            <img  v-bind:src="BannerImg" class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block text-dark">
                <h5>
                    Upcoming Event
                </h5>
            </div>
        </div>



    </div>
   
   

 </div>
</template>

<script>


</script>
