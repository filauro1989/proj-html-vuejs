<template>
    <div class="container-fluid position-relative">
        <div class="wrapper w-85 d-flex mx-auto">
            <div class="left-box w-35">
                <div class="main-title">
                    <h1 class="mt-black">We Are Here To Make Your <span class="mt-green">Website</span> Look More <span class="mt-green">Elegant</span> And Stylish!</h1>   
                </div>
                <div class="jumbo-line"></div>
                <div class="btn text-uppercase">View All</div>

            </div>
            <div class="right-box w-65 d-flex flex-wrap">
                <div class="form-card">
                    <div class="card-wrapper">
                        <i class="fas fa-tachometer-alt mt-green"></i>
                        <h2>Speed Optimization</h2>
                        <p class="grey-text">Far far away, behind the word mountains, far from the countries Vokalia Separated...</p>
                    </div>
                </div>
                <div class="form-card">
                    <div class="card-wrapper">
                        <i class="fas fa-tachometer-alt mt-green"></i>
                        <h2>Speed Optimization</h2>
                        <p class="grey-text">Far far away, behind the word mountains, far from the countries Vokalia Separated...</p>
                    </div>
                </div>
                <div class="form-card">
                    <div class="card-wrapper">
                        <i class="fas fa-tachometer-alt mt-green"></i>
                        <h2>Speed Optimization</h2>
                        <p class="grey-text">Far far away, behind the word mountains, far from the countries Vokalia Separated...</p>
                    </div>
                </div>
                <div class="form-card">
                    <div class="card-wrapper">
                        <i class="fas fa-tachometer-alt mt-green"></i>
                        <h2>Speed Optimization</h2>
                        <p class="grey-text">Far far away, behind the word mountains, far from the countries Vokalia Separated...</p>
                    </div>
                </div>
            </div>
            <div class="rotated-text position-absolute rotate">17 years of experience helping people for best solutions</div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Firstform',

}
</script>

<style lang="scss">
    @import "../assets/scss/partials/_variables.scss";

    .wrapper {
        padding: 13em 0;
    }
    .left-box {
        margin-right: 2em;
        margin-top: 3em;
        .btn {
                background-image: $green-gradient;
                padding: 0.8em 3em;
                color: white;
                border-radius: 2em;
                margin-top: 2em;
        };
    }
    .right-box {
        gap: 2.5em;
        margin-left: 5em;

    }
    .form-card:hover {
        background-image: $green-gradient;
        color: white;
        i {
            color: white;
        };
        p {
            color: white;
        }
    }
    .form-card {
        width: calc(50% - 2.5em);
        border-radius: 20px;
        box-shadow: 0px 0px 46px rgba(0, 0, 0, .2);
        cursor: pointer;
        .card-wrapper {
            padding: 3.5em
        };
        i {
            font-size: 4em;
            padding-bottom: 0.3em
        };
        h2 {
            font-weight: normal;
            padding: 0.6em 0;
        };
        p {
            font-size: 1.1em;
        }

    }

</style>