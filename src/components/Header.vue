<template>
    <div>
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
        padding: 1.5em 0;
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

</style>