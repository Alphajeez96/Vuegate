<template>
     <footer class="border col-12 app-footer">
                    <div class="col-11 mx-auto row mx-0 mt-5">
                        <div class="col-12 col-md">
                            <ul class="list-group footer-list">
                                <li class="list-group-item pb-2 list-header">Features</li>
                                <li class="list-group-item py-1 footer-links"
                                    onclick="location.href='residents learn more.html'">Residents</li>
                                <li class="list-group-item py-1 footer-links"
                                    onclick="location.href='guards learn.html'">Guards</li>
                            </ul>
                        </div>
                        <div class="col-12 col-md">
                            <ul class="list-group footer-list">
                                <li class="list-group-item pb-2 list-header">Company</li>
                                <li class="list-group-item py-1 footer-links" onclick="location.href='aboutus.html'">
                                    About Us</li>
                                <li class="list-group-item py-1 footer-links" onclick="location.href='contactus.html'">
                                    Contact Us</li>
                                <li class="list-group-item py-1 footer-links" onclick="location.href='faq.html'">
                                    Frequently Asked Questions</li>
                                <li class="list-group-item py-1 footer-links"
                                    onclick="location.href='termsandconditions.html'">Terms and Conditions</li>
                            </ul>
                        </div>
                        <div class="col-12 col-md">
                            <ul class="list-group footer-list">
                                <li class="list-group-item pb-2 list-header">Contact</li>
                                <li class="list-group-item py-1 footer-links" style="cursor: initial;">3 Birrel Avenue,
                                    Sabo. <br>
                                    Yaba, Lagos State, <br>
                                    Nigeria</li>
                                <li class="list-group-item py-1 footer-links" style="cursor: initial;">+234 705 784 3748
                                </li>
                                <li class="list-group-item py-1 footer-links" style="cursor: initial;">
                                    contact@gateguard.co</li>
                            </ul>
                        </div>
                        <div class="col-8 col-sm-6 col-md">
                            <div class="col-12 col-md-8 footer-logo">
                                <img src="../../public/gateguard-white.png" alt="">
                            </div>
                            <div class="col-12 mt-5 social-links footer-download">
                                 <img class="mx-2" src="../../public/instagram.png" alt=""
                                    onclick="location.href='https://instagram.com'">
                                <img class="mx-2" src="../../public/twitter.png" alt=""
                                    onclick="location.href='https://twitter.com/hnginternship/'">
                                <img class="mx-2" src="../../public/facebook.png" alt=""
                                    onclick="location.href='https://facebook.com'">
                                <p class="mb-1 d-none d-sm-none d-md-flex d-sm-flex">Download App</p>

                                <div class="col-12 row mx-0 px-0">
                                    <div class="col px-0 app-cons mr-2 d-none d-sm-none d-md-flex d-sm-flex">
                                        <img src="../../public/playstore.png" style="cursor: pointer" alt="playstore"
                                            onclick="location.href='https://play.google.com/store/apps/details?id=com.hng.xgateapp'">
                                    </div>
                                    <div class="col px-0 app-cons d-none d-sm-none d-md-flex d-sm-flex">
                                        <img src="../../public/appstore.png" alt="">
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </footer>
</template>

<style scoped>
    .app-footer{
    min-height: 40vh;
    background: #49a347;
}
.list-header{
    background: inherit;
    color: white;
    border: none;
    font-size: 16px;
    font-weight: bold;
}
.footer-links {
    background: inherit;
    color: white;
    border: none;
    font-size: 12px;
    cursor: pointer;
}
.footer-logo{
    height: 3vh;
    /* padding-bottom: 50px */
}
.footer-logo img{
    /* height: 100%; */
    width: 100%;
}
.social-links img{
    height: 2vh;
    width: 2vh;
    cursor: pointer;
}
.footer-download{
    height: 10vh;
}
.footer-download p{
    color: white;
    font-size: 12px;
}
/* .app-cons {
    height: 10vh;
} */
.app-cons img{
    height: 5vh;
    width: 100%;
}

.login{
    background: #fff;
    height: 250px;
    margin-top: 80px;
    margin-bottom: 60px;
    border-radius: 5px;
    display: flex;
    flex-flow: column nowrap;
}

.login h3{
    font-weight: bold;
    padding: 20px 0px;
    text-align: center;
}
li{
    list-style: none;
}

</style>