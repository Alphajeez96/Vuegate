<template>
  <div class="container-fluid">
    <div class="row">
    <div class=" col-12 welcome-image border-bottom">
      <div  class="col-12 col-md-6 mx-auto welcome-image-words text-center">
                    <h1 class="mt-5 mb-4">Modern Gate Management <br> That Makes Life Smarter</h1>
                    <p class="mb-4">A fully packaged gate management platform for any infrastructure <br>
                        (Home, Estate, or Office). This module increases your security <br>
                        without hassle.</p>
                    <v-btn small color="#49A347" class="white--text ml-2 ">Request Demo</v-btn>
      </div>
      </div>
    </div>
  </div>

</template>

<style scoped>

.welcome-image {
  min-height: 60vh;
  background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)),
    url("../../../public/welcome-image.png");
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}
.welcome-image-words {
  min-height: 50vh;
  margin-top: 13vh;
}
.welcome-image-words h1 {
  color: white;
  font-weight: bold;
  font-size: 30px;
}
.welcome-image-words p {
  color: white;
}
   
</style>