<template>
    <section class="customers col-11 col-md-11 mx-auto">
                <div class="col-12 customer-review mt-4">
                    <h2 class="text-center customer-header">WHAT OUR CUSTOMERS SAY</h2>
                    <hr class="green-underline mt-2">
                    <div class="customers">
                        <div class="indiv-review">
                            <div class="customer-image mt-5 mx-auto">
                                <img src="../../../public/12.jpeg" alt="">
                            </div>
                            <div class="customer-words mx-auto text-center mt-4 col-12 col-md-6">
                                <p>Great App I must say!!! this solution, definitely makes me feel very <br>
                                    comfortable, confident and in control of the security of my family. <br>
                                    Now we can track who/what goes in or out. NICE!!!</p>
                                <h4 class="review-author mb-0">- Mompha James</h4>
                                <span class="review-location">GamesVille Estate</span>
                            </div>
                        </div>
                      
                        </div>
                    </div>
                    <div class="col-12 col-md-10 partners-showcase row mx-0 px-0 mx-auto mt-3">
                        <div class="col-6 col-md pt-5">
                            <img src="../../../public/Alex.png" alt="">
                        </div>
                        <div class="col-6 col-md pt-5">
                            <img src="../../../public/real.png" alt="">
                        </div>
                        <div class="col-6 col-md pt-3">
                            <img src="../../../public/fortis.png" alt="">
                        </div>
                        <div class="col-6 col-md pt-5">
                            <img src="../../../public/king.png" alt="">
                        </div>
                        <div class="col-6 col-md pt-5">
                            <img src="../../../public/John.png" alt="">
                        </div>
                        <div class="col-6 col-md pt-5">
                            <img src="../../../public/windermere.png" alt="">
                        </div>
                    </div>
              

            </section>
</template>

<style scoped>
    .green-underline {
  width: 3vw;
  border-top: 4px solid #49a347;
  margin-left: 530px;
}
.customers {
}
.customer-review {
  min-height: 100vh;
}
.customer-header {
  font-weight: bold;
}
.customer-image {
  height: 25vh;
  width: 25vh;
}
.customer-image img {
  height: 100%;
  width: 100%;
  border-radius: 50%;
}
.customer-words p {
  font-size: 14px;
  font-weight: bold;
  line-height: 4vh;
}
.review-author {
  color: #49a347;
  font-weight: bold;
}
.review-location {
  color: #49a347;
  font-size: 10px;
}
.partners-showcase div {
  height: 18vh;
}
.partners-showcase div img {
  width: 100%;
  vertical-align: middle;
}
</style>