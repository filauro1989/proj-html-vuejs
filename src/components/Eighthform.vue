<template>
    <div class="container-fluid eighth-form">
        <div class="white-wrapper w-100">
            <div class="eighth-card-box w-85 mx-auto d-flex justify-content-around">
                <div class="eighth-card w-45 d-flex flex-column align-items-center">
                    <h5>Are You Ready?</h5>
                    <h1>Start a New Project</h1>
                    <div class="input-box">
                        <input type="email" placeholder="Enter You Email Address">
                        <input type="submit" value="SUBMIT">
                    </div>
                </div>
                <div class="eighth-card eighth-card-green w-45 d-flex flex-column align-items-center">
                    <h5>What Are You Waiting For?</h5>
                    <h1>Let's Talk About Work</h1>
                    <div class="btn-container w-100 d-flex justify-center">
                        <div class="btn text-uppercase mx-auto">Start Now</div>
                    </div>
                </div>
            </div>
        </div>
        <div class="grey-wrapper w-100">
            
        </div>
    </div>
</template>

<script>
export default {
    name: 'Eighthform',
}
</script>

<style lang="scss">
    @import "../assets/scss/partials/_variables.scss";

    .eighth-form {
        .white-wrapper {
            height: 400px;
            .eighth-card-box {
                .eighth-card.eighth-card-green{
                    background-image: $green-gradient;
                }
                .eighth-card {
                    background-image: $black-gradient;
                    border-radius: 15px;
                    padding: 4em;
                    h5 {
                        color: $light-grey-text;
                    }
                    h1 {
                        color: $white-text;
                        padding-bottom: 1.5em;
                    }
                    .input-box {
                        input {
                            border: none;
                            background-color: #4A4A4A;
                            padding: 1em 3em;
                            color: $light-grey-text;
                            outline: none;
                        }
                        input[type=email] {
                            border-top-left-radius: 50px;
                            border-bottom-left-radius: 50px;                           
                        }
                        input[type=submit] {
                            border-top-right-radius: 50px;
                            border-bottom-right-radius: 50px;

                        }
                    }
                    .btn-container {
                        .btn {
                            box-shadow: 0px 0px 46px rgba(0, 0, 0, .2);
                            background-image: $black-gradient;
                            padding: 0.8em 3em;
                            color: white;
                            border-radius: 2em;
                        };
                    }
                }
            }
        }
        .grey-wrapper {
            height: 400px;
            background-color: $background-grey;
        }
    }


</style>