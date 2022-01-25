<template>
    <div class="container-fluid second-form d-flex position-relative">
        <div class="left-box w-65">
            <div class="img-wrap"></div>
        </div>
        <div class="right-box w-35">
            <div class="main-title">
                <h1 class="mt-black">learn more about our <span class="mt-green">missions</span></h1>   
            </div>
            <div class="jumbo-line"></div>
            <p>Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean. Separated theu live in Bookmarksgrove.</p>
            <div class="btn text-uppercase">View All</div>
        </div>
        <div class="img-wrap-clean"></div>
    </div>
</template>

<script>
export default {
    name: 'Secondform',
}
</script>

<style lang="scss">
    @import "../assets/scss/partials/_variables.scss";

    .second-form {
        background-color: $background-grey;
        padding-top: 13em;
        padding-bottom: 17em;
        .img-wrap-clean {
            width: 800px;
            height: 700px;
            border-radius: 20px;
            position: absolute;
            top: 300px;
            left: 225px;
            background-image: url('../assets/img/busy-architect-PYVKWM4-1024x872.jpg');
        }
        .left-box {
            margin-top: 0;
            .img-wrap {
                width: 800px;
                height: 700px;
                border-top-right-radius: 30px;
                border-bottom-right-radius: 30px;
                background-image:
                linear-gradient(to top right, rgba(150,225,95, 0.8) , rgba(12,218,162, 0.8)),
                url('../assets/img/busy-architect-PYVKWM4-1024x872.jpg');
                background-size: cover;
            };
        };
        .right-box {
            margin-left: 0;
            padding-top: 6em;
            .btn {
                background-image: $green-gradient;
                padding: 0.8em 3em;
                color: white;
                border-radius: 2em;
                margin-top: 2em;
            };
            .main-title {
                h1 {
                    width: 60%
                }
            }
        };
        
    }

</style>