<template>
<div class="container">
    <div class="heading">
        <div>
            <h1>Create an Account</h1>
<div class="textContent">
    <p>Lorem ipsum dolor </p>
<p>sit amet consectetur</p>
</div>
        </div>
<div class="inputItems pt-5">
    <v-row>
    <v-col cols="12">
    <input type="text" name="name" id="name"  placeholder="Name"/>

</v-col>
 <v-col cols="12" class="pt-10">
    <input type="text" name="email" id="email"  placeholder="email"/>

</v-col>
 <v-col cols="12" class="pt-10">
    <input type="text" name="password" id="password"  placeholder="password"/>

</v-col>
<v-col cols="12" class="pt-10">
    <input type="text" name="confirmpassword" id="confirmpassword"  placeholder="confirm password"/>

</v-col>
</v-row>
<div class="submit pt-10">
     <v-row>
         <v-col cols="4">
             <v-btn class="textBotton" color="black" width="120" height="50">
      SIGN UP
    </v-btn>
         </v-col>
         <v-col cols="8">
             <p>Lorem ipsum dolor sit amet consectetur</p>
         </v-col>
     </v-row>
</div>
</div>


    </div>
</div>
  
</template>
<script>
export default {
    name: 'CreateaccountPage'

}
</script>

<style lang="scss" scoped>
.container {
  max-width: 1320px;
  
}

input {
    border: 1px solid #000;
    height: 50px;
    width: 80%;
    padding: 10px;
}
.botton {
    background-color: #000;
    color: #ffff;
    width: 100%;
}
.textContent {
    padding-top: 50px;
    line-height: 0.5;
}
.textBotton {
    color: #fff;
}
@media screen and (max-width: 599px) {
    .heading {
        text-align: left;
    }
}

</style>