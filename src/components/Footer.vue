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