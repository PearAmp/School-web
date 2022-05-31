<template>
<div class="container">
    <v-row class="text-center">
        <v-col cols="12" md="6" sm="12" class="topcontent">
            <h1>เข้าสู่ระบบ</h1>
            <div class="formInput mt-10">
                <form action="" class="text-left">
                    <label for="email">Email</label>
                    <div class="mt-10"></div>
                <input type="text" name="email" id="email"  placeholder="ชื่อผู้ใช้ของคุณ"/>
                </form>

                 <form action="" class="text-left mt-10">
                    <label for="password">Password</label>
                    <div class="mt-10"></div>
                <input type="text" name="password" id="password"  placeholder="รหัสผ่านของคุณ" class="text" />
                </form>
            </div>
            <div class="ignor mt-5">
                <p>ลืมรหัสผ่าน</p>
            </div>

            <div class="botton mt-10">
                <v-row class="d-flex justify-center">
                    <button class="login">เข้าสู่ระบบ</button>
                    <div class="space pl-10"></div>
                    <button class="signin signinbutton">สมัครสมาชิก</button> 
                </v-row>
            </div>
        </v-col>
        <v-col cols="12" md="6" sm="12" class="imgeBg"></v-col>
    </v-row>
    
</div>
  
</template>

<script>
export default {
    name: 'SigninPage'

}
</script>

<style lang="scss" scoped>
.container {
  width: 100%;
  background-color: #fff;
  padding: 0;
}
h1 {
    color: #22A45D;
   font-family: 'DM Sans', sans-serif;
font-family: 'Mitr', sans-serif;
font-family: 'Prompt', sans-serif;

}
.topcontent {
    margin-top: 15%;
    margin-bottom: 15%;
}
input[type=text] {
    border: 1px solid #CFD8DC;
    height: 50px;
    width: 100%;
    padding: 10px;
    border-radius: 50px;
    padding-left: 20px;
    
}

label {
    color: #4CAF50;
     font-family: 'DM Sans';
font-style: normal;
     font-weight: 700;
}
.imgeBg {
    background-image: url('https://i.guim.co.uk/img/media/39ee6db292459621464387d6a8d23cafdb2f8dc1/0_171_5120_3072/master/5120.jpg?width=1200&height=1200&quality=85&auto=format&fit=crop&s=d3aabb1d61cd1dde4068013746b6a7f0');
    height: auto;
}
.formInput {
    margin-left: 120px;
    margin-right: 120px;
    font-family: 'DM Sans';
}
.ignor {
    text-align: right;
    margin-right: 20%;
    p {
        font-size: 1rem;
        color: #4CAF50;
         font-family: 'DM Sans';
font-style: normal;
         font-weight: 700;
    }
  
}
.signin {
  border: none;
  color: white;
  padding: 16px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 0.8rem;
  margin: 4px 2px;
  transition-duration: 0.4s;
  cursor: pointer;
  border-radius: 50px;
  width: 25%;
}

.signinbutton {
  background-color: white; 
  color: #22A45D; 
  border: 2px solid #22A45D;
  font-family: 'DM Sans';
font-style: normal;
}

.signinbutton:hover {
  background-color: #22A45D;
  color: white;
}
.login {
  border: none;
  color: white;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 0.8rem;
  margin: 4px 2px;
  cursor: pointer;
  border-radius: 50px;
  width: 25%;
  background-color: #22A45D;
  font-family: 'DM Sans';
font-style: normal;
}


@media screen and (max-width: 1420px){
    .container {
        padding: 0;
    }
    .formInput {
    margin-left: 50px;
    margin-right: 50px;
}
.login {
    width: 30%;
    padding: 0;
    margin: 0;
    height: 50px;
}
.signin {
    width: 30%;
    padding: 0;
    margin: 0;
    height: 50px;
}

} 
@media screen and (max-width: 599px) {
    .container {
        padding: 0;
    }
    .imgeBg {
        display: none;
    }
    .formInput {
    margin-left: 20px;
    margin-right: 20px;
}
.login {
    width: 30%;
    padding: 0;
    margin: 0;
    height: 50px;
}
.signin {
    width: 30%;
    padding: 0;
    margin: 0;
    height: 50px;
}
.ignor {
    margin-right: 10%;
}
.container {
  width: 100%;
  height: 100%;
  display: flex;

  
}

}

@media screen and (min-width: 768px) and (max-width: 991px) {
    .container {
        padding: 0;
        margin: 0;;
    }
   .imgeBg {
        display: none;
    } 
    .topcontent {
        padding-left: 100px;
        padding-right: 100px;
    }
    
}
</style>