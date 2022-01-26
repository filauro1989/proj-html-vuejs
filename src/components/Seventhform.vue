<template>
    <div class="container-fluid seventh-form">
        <div class="wrapper w-85 mx-auto">
            <div class="seventh-top d-flex flex-column justify-content-center align-items-center">
                <div class="main-title">
                    <h1 class="mt-black">Latest News & Our <span class="mt-green">Blog </span></h1>   
                </div>
                <div class="jumbo-line"></div>
            </div>
            <div class="seventh-box d-flex justify-content-around">
                <div id="seventh-first-card" class="seventh-card w-30 rounded position-relative">
                    <div class="card-bottom rounded position-absolute">
                        <p>May24, 2018 by Alex</p>
                        <h4 class="d-flex align-items-center">
                            <i class="fas fa-circle"></i> 
                            Marketing Ideas
                        </h4>
                    </div>
                </div>  
                <div id="seventh-second-card" class="seventh-card w-30 rounded position-relative">
                    <div class="card-bottom rounded position-absolute">
                        <p>May24, 2018 by Alex</p>
                        <h4 class="d-flex align-items-center">
                            <i class="fas fa-circle"></i> 
                            Marketing Ideas
                        </h4>
                    </div>
                </div>  
                <div id="seventh-third-card" class="seventh-card w-30 rounded position-relative">
                    <div class="card-bottom rounded position-absolute">
                        <p>May24, 2018 by Alex</p>
                        <h4 class="d-flex align-items-center">
                            <i class="fas fa-circle"></i> 
                            Marketing Ideas
                        </h4>
                    </div>
                </div>  
            </div>
            <div class="btn-container w-100 d-flex justify-center">
                <div class="btn text-uppercase mx-auto">View All Post</div>
            </div>
        </div>

    </div>
</template>

<script>
export default {
    name: 'Seventhform',
}
</script>

<style lang="scss">
    @import "../assets/scss/partials/_variables.scss";

    .seventh-form {
        .seventh-box {
            #seventh-first-card {
                background-image: url('../assets/img/serious-businesswoman-with-documents-talking-on-P9Q6LX6-1024.jpg');
            }
            #seventh-second-card {
                background-image: url('../assets/img/Businessman-at-the-desk-in-his-office-resting--1024x768.jpg');
            }
            #seventh-third-card {
                background-image: url('../assets/img/simple-home-office-with-tree-PBXRXYB-large-1024x768.jpg');
            }
            .seventh-card {
                width: 500px;
                height: 350px;
                box-shadow: 0px 0px 46px rgba(0, 0, 0, .2);
                background-repeat: no-repeat;
                background-size: cover;
                background-position: center;
                .card-bottom {
                    width: 400px;
                    // height: 150px;
                    padding: 1.5em 2em;
                    background-color: $background-white;
                    left: 50px;
                    bottom: -50px;
                    box-shadow: 0px 0px 46px rgba(0, 0, 0, .2);
                    p {
                        padding-left: 1.3em;
                        padding-top: 1.5em;
                        margin-bottom: 0.2em;
                        color: $light-grey-text;
                    }
                    h4 {
                        font-weight: normal;
                        i {
                            font-size: 0.5em;
                            padding-right: 0.7em;
                            color: $green-text;
                        }
                    }

                }
            }
        }
        .btn-container {
            padding-top: 3em;
            .btn {
                background-image: $black-gradient;
                padding: 0.8em 3em;
                color: white;
                border-radius: 2em;
                margin-top: 6em;
            };
        }
    }


</style>