<template>
    <div class="container-fluid">
        <div class="wrapper w-85 mx-auto d-flex">
            <div class="footer-box w-25">
                <div class="box-wrapper">
                    <img src="../assets/img/cropped-Group-39-2x.png" alt="">
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quibusdam odit cumque repudiandae hic sed, dolorum accusamus laborum, ipsam maxime vero obcaecati, consequatur necessitatibus error repellendus alias illo magni. Suscipit, deleniti?</p>
                </div>
            </div>
            <div class="footer-box w-25">
                <div class="box-wrapper">
                    <div class="main-title">
                        <h1 class="mt-black text-uppercase">Quick Links</h1>   
                    </div>
                    <div class="jumbo-line"></div>
                    <div class="ul-wrapper d-flex justify-content-center">
                        <ul class="text-center">
                            <li>Careers</li>
                            <li>News</li>
                            <li>Terms of use</li>
                            <li>Privacy Projects</li>
                            <li>About</li>
                            <li>Contact</li>
                        </ul>
                    </div>
                </div>
            </div>
            <div class="footer-box w-25">
                <div class="box-wrapper">
                    <div class="main-title">
                        <h1 class="mt-black text-uppercase">Contact</h1>   
                    </div>
                    <div class="jumbo-line"></div>
                    <p class="contact-name">Patricia C.Amedee 4401 Waldeck Street Grapevine Nashville, TX 76051</p>
                    <p>info@yourdomain.com</p>
                    <p>+99 (0) 1010000 888</p>
                </div>
            </div>
            <div class="footer-box w-25">
                <div class="box-wrapper">
                    <div class="main-title">
                        <h1 class="mt-black text-uppercase">Location on Map</h1>   
                    </div>
                    <div class="jumbo-line"></div>
                    <img src="../assets/img/map.png" alt="">
                </div>
            </div>
        </div>
        <div class="footer-bottom">
            <div class="footer-bottom-container w-85 mx-auto d-flex justify-content-between align-items-center">
                <div class="text-uppercase">&#169; phlox business theme.</div>
                <div class="social-box">
                    <i class="fab fa-facebook-f"></i>
                    <i class="fab fa-twitter"></i>
                    <i class="fab fa-pinterest-p"></i>
                </div>
            </div>
        </div>
    </div>

</template>

<script>
export default {
    name: 'Footer',
}
</script>

<style lang="scss">
    @import "../assets/scss/partials/_variables.scss";
    .footer-bottom {
        background-image: $black-gradient;
        .footer-bottom-container {
            color: $light-grey-text;
            div {
                padding: 2.5em 0;
            }
            .social-box i {
                padding-right: 1.5em;
            }
        }

    }
    .footer-box {
        .box-wrapper {
            padding: 0 1em;
            p {
                padding-top: 1.5em;
            }
            .main-title {
                font-size: 0.5em;
            }
            .jumbo-line {
                margin: 1.5em 0;
            }
            .ul-wrapper {
                ul {
                    list-style-type: none;
                }
            }
            .contact-name {
                width: 80%;
                padding-top: 0;
            }
        }
    }
</style>