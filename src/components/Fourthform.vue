<template>
    <div class="container-fluid fourth-form">
        <div class="wrapper w-85 mx-auto">
            <div class="img-wrap position-relative">

                <div class="stats w-50 h-50 d-flex flex-column align-items-center text-uppercase">
                    <h1>280</h1>
                    <h5>Project</h5>
                    <div class="returns-stats d-flex justify-content-center">
                        <div class="comments d-flex flex-column align-items-center">
                            <h3>+3,500</h3>
                            <h6>User's Comments</h6>
                        </div>
                        <div class="happy-clients d-flex flex-column align-items-center">
                            <h3>100%</h3>
                            <h6>Happy Clients</h6>
                        </div>
                    </div>
                </div>

                <div class="proj-text position-absolute">
                    <div class="text-container">
                        <div class="main-title">
                            <h1 class="mt-black">We <span class="mt-green">Love </span>What We Do</h1>   
                        </div>
                        <div class="jumbo-line"></div>
                        <p>Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean. Separated they live in Bookmarksgrove.</p>
                        <ul class="fourth-form-list">
                            <li><i class="fas fa-check"></i> Far far away, behind the word mountains</li>
                            <li><i class="fas fa-check"></i> Large language ocean</li>
                            <li><i class="fas fa-check"></i> far from the countries Vokalia and Consonantia</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Fourthform',
}
</script>

<style lang="scss">
    @import "../assets/scss/partials/_variables.scss";

    .fourth-form {
        background-color: $background-grey;
        .img-wrap {
                width: 900px;
                height: 750px;
                border-radius: 10px;
                background-image:
                linear-gradient(to top right, rgba(12,218,162, 0.8), rgba(150,225,95, 0.8)),
                url('../assets/img/person-with-long-curly-hair-PZ99QM2-2x.jpg');
                background-size: cover;
                .stats {
                    padding-left: 44%;
                    padding-top: 22%;
                    color: $white-text;
                    .happy-clients {
                        border-left: 1px solid $white-text;
                    }
                    h1 {
                        font-weight: normal;
                        font-size: 8em;
                    };
                    h3 {
                        font-weight: normal;
                        font-size: 3.5em;
                        padding: 0 1em;
                    };
                    h6 {
                        font-weight: normal;
                        font-size: 1.5em;
                    }
                }
                .proj-text {
                    position: absolute;
                    width: 900px;
                    height: 750px;
                    border-radius: 10px;
                    top: 10%;
                    right: -90%;
                    background-color: white;
                    box-shadow: 0px 0px 46px rgba(0, 0, 0, .2);
                    .text-container {
                        padding: 0 5em;
                        padding-top: 7em;
                        p {
                            color: $grey-text;
                        }
                        .fourth-form-list {
                            list-style-type: none;
                            padding-top: 2em;
                            padding-left: 0;
                            li {
                                color: $grey-text;
                                padding-top: 1em;
                                i {
                                    color: $green-text;
                                }
                            }
                        }
                        .main-title h1 {
                            width: 60%
                        }
                    }
                }
            };
        
    }

</style>