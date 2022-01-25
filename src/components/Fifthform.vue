<template>
    <div class="container-fluid fifth-form">
        <div class="wrapper w-85 mx-auto d-flex justify-content-between">
            <div class="first-col w-30">
                <div class="main-title">
                    <h1 class="mt-black">With <span class="mt-green">Live Chat 24/7 </span>Support</h1>   
                </div>
                <div class="jumbo-line"></div>
                <p>Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean. Separated they live in Bookmarksgrove.</p>    
            </div>
            <div class="plan-card d-flex flex-column">
                <div class="plan-card-top position-relative">

                    <div class="top-plan w-100 d-flex flex-column align-items-center position-absolute">
                        <h2 class="text-uppercase">Designing</h2>
                        <p>All Designs</p>
                    </div>

                    <div class="top-price w-100 h-100 d-flex align-items-end justify-content-center">
                        <h1>$ 13 /Design</h1>
                    </div>
                </div>
                <div class="plan-card-bottom">
                    <ul>
                        <li><i class="fas fa-check"></i> Creative Design Enabled</li>
                        <li><i class="fas fa-check"></i> Vibrant Color Usage</li>
                        <li><i class="fas fa-check"></i> Eye Catching Design</li>
                        <li><i class="fas fa-check"></i> Extreme Typography</li>
                        <li><i class="fas fa-check"></i> Exceptional Design</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Fifthform',
}
</script>

<style lang="scss">
    @import "../assets/scss/partials/_variables.scss";

    .fifth-form {
        background-color: $background-grey;
        .first-col {
            padding: 0 2em;
            p {
                color: $grey-text;
            }
        }
        .plan-card {
            width: 20%;
            box-shadow: 0px 0px 46px rgba(0, 0, 0, .2);
            border-radius: 15px;
            overflow: hidden;
            .plan-card-top {
                background-image: $black-gradient;
                height: 230px;
                .top-plan {
                    background-color: white;
                    top: 13px;
                    padding-top: 0.5em;
                }
                .top-price {
                    h1 {
                        padding-bottom: 0.8em;
                        color: $white-text;
                    }
                }
            }
            .plan-card-bottom {
                ul {
                    list-style-type: none;
                    padding: 2em 2em 0.3em 2em;
                    text-align: center;
                    li {
                        margin: 1.5em 0;
                        i {
                            padding-right: 0.7em;
                        }
                    }
                }
            }
        }
    }

</style>