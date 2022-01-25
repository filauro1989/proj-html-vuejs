<template>
    <div class="position-relative">
        <!-- black top header -->
        <div class="header-top container-fluid d-flex">
            <div class="header-wrapper container-85 d-flex justify-content-between mx-auto">
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
        <!-- navbar -->
        <div class="header-navbar container-fluid">
            <div class="navbar container-85 mx-auto">
                <div class="logo">
                    <img src="../assets/img/cropped-Group-39-2x.png" alt="">
                </div>
                <div class="navbar-menu text-uppercase">
                    <ul class="navbar-nav d-flex flex-row">
                        <li class="nav-item">Home</li>
                        <li class="nav-item">About</li>
                        <li class="nav-item">Services</li>
                        <li class="nav-item">Showcase</li>
                        <li class="nav-item">Blog</li>
                        <li class="nav-item">Contact</li>
                    </ul>
                </div>
                <div class="nav-bar-search text-uppercase">
                    <div class="btn">Purchase</div>
                    <i class="fas fa-search"></i>
                </div>
            </div>
        </div>
        <!-- jumbotron -->
        <div class="jumbotroner container-fluid background-1">
            <div class="jumbo-left-box">
                <h6 class="text-uppercase">17 years of experience</h6>
                <div class="main-title">
                    <h1 class="mt-black">Focus on Your <span class="mt-green">Business</span></h1>   
                </div>
                <div class="jumbo-line"></div>
                <p>Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean. Separated theu live in Bookmarksgrove.</p>
                <div class="btn text-uppercase">Read More</div>
                <div class="jumbo-social text-uppercase">
                    <a href="">Facebook</a><span> - </span>
                    <a href="">Instagram</a><span> - </span>
                    <a href="">Youtube</a><span> - </span>
                    <a href="">Twitter</a>
                </div>
            </div>
        </div>
        <!-- slider sfondo -->
        <div class="jumbo-selector d-inline">
            <div class="selector-one">01</div>
            <div class="selector-two active">02</div>
            <div class="selector-three">03</div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Header',
}
</script>

<style lang="scss">
    @import "../assets/scss/partials/_variables.scss";

    .container-85 {
        width: 85%;
    }
    .header-top {
        height: 40px;
        background-color: #3D3D3D;
        color: white;
        .phone-number {
            i {
                padding-right: 0.7em;
            };
        };
        .social-nav i {
            padding: 0 0.5em;
        }
    }
    .header-navbar {
        padding: 1em 0;
        .navbar .logo img {
            height: 45px;
        };
        .btn {
            padding: 0.8em 3em;
            color: white;
            border-radius: 2em;
            background-image: linear-gradient(to right, #96E15F , #0CDAA2);
            box-shadow: 5px 10px 18px 5px #D2F8EF;
        };
        i {
            margin-left: 2em;
            color: #00D9A6;
        }
    }
    .navbar-nav {
        list-style-type: none;
        li {
            padding: 1.3em;
            font-size: 0.9em;
        }
    }
    .background-1 {
            background-image: url(../assets/img/Group-35-2x.png);
        };
    .jumbotroner {
        background-color: #FAFAFA;
        height: 100vh;
        background-position-y: 50%;
        background-position-x: 180%;
        background-repeat: no-repeat;
        .jumbo-left-box {
            width: 40%;
            margin-left: 8em;
            padding-top: 9em;
            .main-title {
                .mt-black {
                    font-size: 5em;
                    line-height: 1.1em
                };
            };
            h6 {
                letter-spacing: 8px;
                background: -webkit-linear-gradient(#96E15F, #0CDAA2);
                -webkit-background-clip: text;
                -webkit-text-fill-color: transparent;
            };
            .btn {
                background-image: $black-gradient;
                padding: 0.8em 3em;
                color: white;
                border-radius: 2em;
                margin-top: 5em;
            };
            .jumbo-social {
                padding-top: 8em;
                a {
                    text-decoration: none;
                    color: black;
                    font-weight: bold;
                }
            }
        };
    }
    .jumbo-selector {
            position: absolute;
            bottom: 12%;
            left: 40%;
            padding: 0.5em;
            background-image: linear-gradient(to right, #0E0E0EB3 , black);
            border-radius: 2em;
            > div{
                font-size: 1.2em;
                padding: 0.3em 1.1em;
                font-weight: bold;
                color: #9F9F9F;
                display: inline-block;
            };
            > div.active {
                background-image: linear-gradient(to right, #96E15F , #0CDAA2);
                border-radius: 2em;
            }
    }

</style>