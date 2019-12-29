<template>
<div class="col-12 download-footer px-0">
                <div class="col-12 download-app row mx-0">
                    <div class="col-12 col-md-5">
                        <div class="col-12 col-md-9 download-image-con mt-5 mx-auto">
                            <img src="../../../public/download-app-image.png" alt="">
                        </div>
                    </div>
                    <div class="col-12 col-md-7 mb-2">
                        <div class="col-10 details-con mx-auto">
                            <h2>DOWNLOAD THE APP</h2>
                            <hr class="green-underline mt-2 ml-0">
                            <p>Worry less abot security saying goodbye to the old scary security <br>
                                system. Monitor every activity at your residence with just one click. <br>
                                GateGUARD is the perfect App that solves every of your security <br> worries.</p>
                            <div class="col-12 download-links row mx-0 px-0 mt-5">
                                <div class="col-12 col-sm-8 mt-2 col-md-5 store-link px-0">
                                    <img src="../../../public/playstore.png" style="cursor: pointer" alt=""
                                        onclick="location.href='https://play.google.com/store/apps/details?id=com.hng.xgateapp'">
                                </div>
                                <div class="col-12 col-sm-8 mt-2 col-md-5 store-link px-0">
                                    <img src="../../../public/appstore.png" alt="">
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
</div>
    
</template>
<style scoped>

.green-underline {
  width: 3vw;
  border-top: 4px solid #49a347;
  margin-left: 600px;
}
.download-app{
    min-height: 70vh;
    background: #e5e5e5;
}
.download-image-con {
    height: 55vh;
}
.download-image-con img{
    height: 100%;
    width: 100%;
    object-fit: contain;
}
.details-con{
    margin-top: 15vh;
}
.download-app h2{
    font-weight: bold;
}
.download-app p{
    font-size: 12px;
    font-weight: bold;
}
</style>