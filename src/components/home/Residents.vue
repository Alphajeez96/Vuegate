<template>
    <div class="col-12 feature-breakdown">
                <div class="col-12 col-md-11 mx-auto row mx-0 breakdown-con">
                    <div class="col-12 col-md">
                        <div class="col-12 col-md-10 mt-4">
                            <h3 class="breakdown-header">Residents</h3>
                            <hr class="green-underline mt-2 ml-0">
                            <div class="col-12 row mx-0 px-0 breakdown-feature">

                                
                                <ul class="pt-2 col-12">
                                    <li class="pt-2 col-12 list-star">Residents can update "Expected Visitor" details on
                                        GateGuard mobile app.</li>
                                    <li class="pt-2 col-12 list-star">Get real time notifications on visitors coming to
                                        your home.</li>

                                    <li class="pt-2 col-12 list-star">Staff management service (Cook, Maid, Nanny,
                                        Driver) hire through the app.</li>

                                    <li class="pt-2 col-12 list-star">Residents get alerts whenever their staff checks
                                        in/out the gate.</li>

                                </ul>
                            </div>
                            
                            <div class="col-12">
                                 <v-btn small color="#49A347" class="white--text ml-2 ">Learn More</v-btn>
                            </div>
                        </div>
                    </div>
                    <div class="col-12 col-md">
                        <div class="col-12 col-md-10 mt-5 breakdown-image mx-auto px-0">
                            <img src="../../../public/mansion.png" alt="">
                        </div>
                    </div>
                </div>
                <div class="col-12 col-md-11 mx-auto row mx-0 breakdown-con">
                    <div class="col-12 col-md">
                        <div class="col-12 col-md-10 mt-5 breakdown-image mx-auto px-0">
                            <img src="../../../public/gate.png" alt="">
                        </div>
                    </div>
                    <div class="col-12 col-md">
                        <div class="col-12 col-md-10 mt-4 ml-auto">
                            <h3 class="breakdown-header">Security Guards</h3>
                            <hr class="green-underline mt-2 ml-0">
                            <div class="col-12 row mx-0 px-0 breakdown-feature">

                                <ul class="pt-2 col-12">
                                    <li class="pt-2 col-12 list-star">Guards can view "Expected Visitors" details on
                                        GateGuard mobile app.</li>

                                    <li class="pt-2 col-12 list-star">Guards real time notifications on visitors coming
                                        to visit.</li>

                                    <li class="pt-2 col-12 list-star">Guards will now have access to the list of
                                        blacklisted staffs to
                                        prevent entry.</li>

                                    <li class="pt-2 col-12 list-star">Faster check-ins at the gate which has eliminated
                                        the long queues.</li>

                                </ul>
                            </div>
                           
                            <div class="col-12">
                                <v-btn small color="#49A347"  class="white--text ">Learn More</v-btn>
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
.feature-breakdown {
  min-height: 100vh;
  background: #e5e5e5;
}
.breakdown-con {
  min-height: 60vh;
}
.breakdown-header {
  color: #49a347;
  font-weight: bold;
}

.breakdown-feature img {
  height: 5vh;
  width: 5vh;
}
.breakdown-feature p {
  font-size: 10px;
  font-weight: bold;
}

.breakdown-image {
  height: 45vh;
}
.breakdown-image img {
  height: 100%;
  width: 100%;
  object-fit: cover;
}
.list-star {
  list-style-image: url('../../../public/star.png');    
}


</style>