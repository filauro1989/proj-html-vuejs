<template>
    <div class="container-fluid sixth-form d-flex justify-content-center align-items-center">
        <div class="sixth-form-box w-60 d-flex flex-column justify-content-center align-items-center">
            <i class="fas fa-quote-left"></i>
            <h2 class="text-center">When it comes to barbequing, there are two main schools of thought for the techniques that you can use. Freshly scambled eggs with applewood smoked bacon - are amazing!</h2>
            <div class="img-wrapper rounded-circle"></div>
            <h4 class="text-uppercase">Lissa Durbin</h4>
            <p>Client</p>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Sixthform',
}
</script>

<style lang="scss">
    @import "../assets/scss/partials/_variables.scss";

    .sixth-form {
        padding: 10em;
        background-image:
        linear-gradient(to top right, rgba(0,0,0, 0.9), rgba(75, 75, 75, 0.9)),
        url('../assets/img/four-businesspeople-in-a-boardroom-with-paperwork-PC4V8H4.jpg');
        background-repeat: no-repeat;
        background-size: cover;
        background-position: center;
        .sixth-form-box {
            color: $white-text;
            i {
                font-size: 3.5em;
                color: $green-text;
                margin-bottom: 1em;
            }
            .img-wrapper {
                width: 100px;
                height: 100px;
                margin-bottom: 2em;
                border: 3px solid white;
                background-image: url('../assets/img/businesswoman-analysing-document-P8WSNMC-1024x820.jpg');
                background-repeat: no-repeat;
                background-size: cover;
                background-position-x: -15px;
            }
            h2 {
                font-weight: normal;
                font-style: italic;
                margin-bottom: 2em;
            }
            h4 {
                color: $green-text;
                font-weight: normal;
            }
            p {
                font-weight: bold;
            }
        }
    }

</style>