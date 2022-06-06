<template>

  <div class="container d-flex justify-space-center">
    <v-row class="text-center">
      <v-col cols="12" md="6" sm="12 mt-10">
        <div class="texthead">
          <h1>สมัครสมาชิก</h1>
          <div class="formregister">
            <form action="" class="text-left form-login">
                <label  for="email">Email</label>
                <input
                  type="text"
                  name="email"
                  id="email"
                  placeholder="ชื่อผู้ใช้ของคุณ"
                />
                <label for="email">Password</label>
                <input
                  type="text"
                  name="password"
                  id="password"
                  placeholder="รหัสผ่านของคุณ"
                />
                <label for="email">Confirm Password</label>
                <input
                  type="text"
                  name="password"
                  id="password"
                  placeholder="รหัสผ่านของคุณ"
                />

                <v-row class="justify-end">
                  <p class="lotPassword">ลืมรหัสผ่าน</p>
                </v-row>
                <v-row class="justify-space-between">
                  <button class="login">เข้าสู่ระบบ</button>

                  <button class="signin signinbutton"><NuxtLink to="/register">สมัครสมาชิก</NuxtLink></button>
                </v-row>
              </form>
          </div>
        </div>
        
      </v-col>

      <v-col cols="12" md="6" sm="12" class="imgeBg"> </v-col>
    </v-row>
  </div>
</template>

<script>
export default {
    name: 'registerpage',

}
</script>

<style lang="scss" scoped>
.container {
  max-width: 100%;
  height: 100%;
  background-color: #fff;
  padding: 0;
}

.imgeBg {
  background-image: url('https://images.unsplash.com/photo-1560145725-8cbf9768b73a?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1000&q=80');
  height: 1000px;
}
.formregister {
  margin-top: 50px;
}
.texthead {
  font-family: 'DM Sans';
font-style: normal;
text-align: center;
letter-spacing: -0.4px;
color: #22A45D;
margin-top: 150px;
padding: 100px;
form {
  text-align: left;
}
}
input[type='text'] {
  border: 1px solid #cfd8dc;
  height: 50px;
  width: 100%;
  //   padding: 10px;
  border-radius: 50px;
  padding-left: 20px;
  margin: 20px 0px 20px 0px;
}

label {
  color: #4caf50;
  font-family: 'DM Sans';
  font-style: normal;
  font-weight: 700;
}

@media screen and (max-width: 1420px) {
  
}
@media screen and (min-width: 300px) and (max-width: 599px) {
  
}

@media screen and (min-width: 768px) and (max-width: 991px) {
  
}
</style>
