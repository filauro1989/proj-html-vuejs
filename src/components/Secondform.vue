<template>
    <div class="container-fluid second-form">
        <div class="left-box w-35">
            <div class="img-wrap"></div>
        </div>
        <div class="right-box w-65">

        </div>
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
        padding: 13em 0;
        .left-box {
            .img-wrap {
                width: 750px;
                height: 700px;
                border-top-right-radius: 30px;
                border-bottom-right-radius: 30px;
                background-image:
                linear-gradient(to top right, rgba(150,225,95, 0.8) , rgba(12,218,162, 0.8)),
                url('../assets/img/busy-architect-PYVKWM4-1024x872.jpg');
                background-size: cover;

            };
            // img::after {
            //     position: absolute;
            //     top: 0;
            //     left: 0;
            //     content: "";
            //     width: 750px;
            //     height: 750px;
            //     background-image: $green-gradient;
            //     opacity: 0.8;
            // }
        }
    }

</style>