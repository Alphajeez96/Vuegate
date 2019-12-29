<template>
    <div class="col-12 subscribe row mx-0">
                    <div class="col-12 col-sm-8 col-md-6 subscribe-words mx-auto">
                        <div class="col-12 col-md-8 mt-5 mx-auto">
                            <h2>SUBSCRIBE TO OUR <br> NEWSLETTER</h2>
                            <hr class="green-underline mt-2 ml-0">
                            <div class="col-12 row mx-0 px-0 breakdown-feature">

                                <ul class="pt-2 col-12">
                                    <li class="pt-2 col-12 list-star">Guards real time notifications on visitors coming
                                        to visit.</li>

                                    <li class="pt-2 col-12 list-star">Get real time notifications on visitors coming to
                                        your home.</li>

                                </ul>
                            </div>
                        </div>
                    </div>
                    <div class="col-12 col-md-6 subscribe-form mb-5">
                        <div class="col-12 col-sm-8 col-md-10 mx-auto">
                            <form id="form-submit">
                                <div class="form-group">
                                    <input type="text" id="name" class=""  placeholder="   Name">
                                </div>
                                <div class="form-group">
                                    <input type="email" id="email" class="p" placeholder="   Email">
                                </div>
                               <v-btn small color="#49A347"  class="white--text mt-2 newsletter-btn"> Submit</v-btn>
                            </form>
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
.subscribe {
  min-height: 60vh;
}
.subscribe h2{
  font-weight: bold;
}
.subscribe-form > div {
  margin-top: 15vh;
}
.subscribe-form input {
  color: black;
  border-radius: 0px;
  border: 1px solid black;
}
.subscribe-form input::placeholder {
  color: black;
}
.subscribe-form input:focus {
  box-shadow: none;
  border: 1px solid black;
}
.subscribe-form button {
  background: #49a347;
  color: white;
  border: none;
  /* border-radius: 0px; */
}
/* .subscribe-form button:hover {
  background: white;
  color: #49a347;
  border: 1px solid #49a347;
  border-radius: 0px;
} */
.subscribe-form button:focus {
  background: #49a347;
}
.list-star {
  list-style-image: url('../../../public/star.png');    
}
.newsletter-btn{
    width: 350px
}
#email{
    width:350px;
    border: 1px groove grey;
    margin-bottom: 5px;
    border-radius: 5px
}
#name{
    width:350px;
    border: 1px groove grey;
    margin-bottom: 5px;
    border-radius: 5px;  
}
#form-submit{
    margin-top: 20px;
}

</style>