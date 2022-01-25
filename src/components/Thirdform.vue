<template>
    <div class="container-fluid third-form">
        <div class="wrapper w-85 mx-auto d-flex">
            <div class="left-box w-40">
                <div class="main-title">
                    <div class="jumbo-line"></div>
                            <h1 class="mt-black">Our recent <span class="mt-green">web design</span> & some examples of past<span class="mt-green">projects</span></h1>   
                        </div>
                    <div class="jumbo-line translated-10"></div>
            </div>
            <div class="right-box w-60 d-flex align-items-end">
                <p>Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean. Separated theu live in Bookmarksgrove.</p>
            </div>
        </div>
        <div class="showroom w-85 mx-auto position-relative">

            <img class="" src="../assets/img/ina-soulis-227104-unsplash-1024x1024.jpg" alt="">
            <img class="" src="../assets/img/sunisa-misa-531163-unsplash-1024x1024.jpg" alt="">
            <img class="" src="../assets/img/355H-1024x1024.jpg" alt="">
            <img class="" src="../assets/img/photo-1448932252197-d19750584e56-1024x1024.jpg" alt="">
            <img class="" src="../assets/img/business-competition-PB366D8-1024x1024.jpg" alt="">
            <img class="" src="../assets/img/cozy-sofa-in-living-room-PQR5AB9-1024x1024.jpg" alt="">
            <img class="" src="../assets/img/aa9a4539-PQGJ7HU-1024x1024.jpg" alt="">
            <img class="" src="../assets/img/cody-davis-253928-unsplash-1024x1024.jpg" alt="">

            <div class="rotated-text position-absolute rotate">17 years of experience helping people for best solutions</div>
            
        </div>
        <div class="btn-container w-100 d-flex justify-center">
            <div class="btn text-uppercase mx-auto">Read More</div>
        </div>
        

    </div>
</template>

<script>
export default {
    name: 'Thirdform',
}
</script>

<style lang="scss">
    @import "../assets/scss/partials/_variables.scss";
    .third-form {
        padding-bottom: 12em;
        .rotated-text {
            right: -200px;
        }
        .wrapper {
            padding-bottom: 4em;
        }
        .translated-10 {
            margin-left: 20px;
            margin-bottom: 0;
        };
        .showroom img {
            border-radius: 5px;
            padding: 0.2em 0.2em;
            width: calc(25% - 1em);
        }
        .btn {
            background-image: $green-gradient;
            padding: 0.8em 3em;
            color: white;
            border-radius: 2em;
            margin-top: 6em;
        };
    }

</style>