<template>
    <div>
        <div class="header-top container-fluid d-flex">
            <div class="header-wrapper container-85 d-flex justify-content-between">
                <div class="phone-number d-flex align-items-center">
                    <i class="fas fa-phone-alt"></i>
                    <div>(001) 88451234  88455438</div>
                </div>
                <div class="social-nav d-flex align-items-center">
                    <i class="fab fa-facebook-f"></i>
                    <i class="fab fa-twitter"></i>
                    <i class="fab fa-pinterest-p"></i>
                </div>
            </div>
        </div>
        <div class="header-navbar container-fluid">

        </div>
    </div>
</template>

<script>
export default {
    name: 'Header',
}
</script>

<style lang="scss">
    .container-85 {
        width: 85%;
    }
    .header-top {
        height: 40px;
        background-color: #3D3D3D;
        .header-wrapper {
            margin: 0 auto;
        };
        .phone-number {
            i {
                padding-right: 0.7em;
            };
            div {
                font-size: 1.5em;
                margin-top: 0.3em;
            } 
        };
        .social-nav i {
            padding: 0 0.5em;
        }
    }

</style>