<template>
  <div class="container d-flex justify-space-center">
    <v-row class="text-center">
      <v-col cols="12" md="6" sm="12">
        <v-container fill-height fluid>
          <v-row align="center" justify="center">
            <v-col>
              <h1>เข้าสู่ระบบ</h1>
              <form action="" class="text-left form-login">
                <label for="email">Email</label>
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

                <v-row class="justify-end">
                  <p class="lotPassword">ลืมรหัสผ่าน</p>
                </v-row>
                <v-row class="justify-space-between">
                  <button class="login">เข้าสู่ระบบ</button>

                  <button class="signin signinbutton">สมัครสมาชิก</button>
                </v-row>
              </form>
            </v-col>
          </v-row>
        </v-container>
      </v-col>

      <v-col cols="12" md="6" sm="12" class="imgeBg"> </v-col>
    </v-row>
  </div>
</template>

<script>
export default {
  name: 'SigninPage',
}
</script>

<style lang="scss" scoped>
.container {
  width: 100%;
  height: 100%;
  background-color: #fff;
  padding: 0;
}
h1 {
  color: #22a45d;
  font-family: 'DM Sans', sans-serif;
  font-family: 'Mitr', sans-serif;
  font-family: 'Prompt', sans-serif;
}
.lotPassword {
  color: #22a45d;
  font-family: 'DM Sans', sans-serif;
  font-family: 'Mitr', sans-serif;
  padding-top: 20px;
  padding-right: 10px;
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

.imgeBg {
  background-image: url('https://nationaltoday.com/wp-content/uploads/2021/07/shutterstock_1518533924-min.jpg');
  height: cover;
}

.signinbutton {
    background-color: white;
    color: #22a45d;
    border: 2px solid #22a45d;
    font-family: 'DM Sans';
    font-style: normal;
    text-align: center;
    border-radius: 50px;
    padding-top: 10px;
    padding-bottom: 10px;
    padding-right: 20px;
    padding-left: 20px;
    margin-right: 10px;
    width: 40%;
  }

  .login {
    border: none;
    color: white;
    text-align: center;
    border-radius: 50px;
    background-color: #22a45d;
    font-family: 'DM Sans';
    font-style: normal;
    padding-top: 10px;
    padding-bottom: 10px;
    padding-right: 20px;
    padding-left: 20px;
    margin-left: 10px;
    width: 40%;
  }
  .form-login {
    margin-left: 60px;
    margin-right: 60px;
  }

@media screen and (max-width: 1420px) {
  .form-login {
    margin-left: 60px;
    margin-right: 60px;
  }
  .signinbutton {
    background-color: white;
    color: #22a45d;
    border: 2px solid #22a45d;
    font-family: 'DM Sans';
    font-style: normal;
    text-align: center;
    border-radius: 50px;
    padding-top: 10px;
    padding-bottom: 10px;
    padding-right: 20px;
    padding-left: 20px;
    margin-right: 10px;
    width: 40%;
  }

  .login {
    border: none;
    color: white;
    text-align: center;
    border-radius: 50px;
    background-color: #22a45d;
    font-family: 'DM Sans';
    font-style: normal;
    padding-top: 10px;
    padding-bottom: 10px;
    padding-right: 20px;
    padding-left: 20px;
    margin-left: 10px;
    width: 40%;
  }
}
@media screen and (min-width: 300px) and (max-width: 599px) {
  .imgeBg {
    display: none;
  }
  .signinbutton {
    background-color: white;
    color: #22a45d;
    border: 2px solid #22a45d;
    font-family: 'DM Sans';
    font-style: normal;
    font-size: 0.6rem;
    text-align: center;
    border-radius: 50px;
    padding-top: 10px;
    padding-bottom: 10px;
    // padding-right: 10px;
    // padding-left: 10px;
    margin-right: 0px;
    width: 100px;
  }

  .login {
    border: none;
    color: white;
    text-align: center;
    border-radius: 50px;
    background-color: #22a45d;
    font-family: 'DM Sans';
    font-style: normal;
    font-size: 0.6rem;
    padding-top: 10px;
    padding-bottom: 10px;
    // padding-right: 10px;
    // padding-left: 10px;
    margin-right: 0px;
    width: 100px;
  }

  label {
    color: #4caf50;
    font-family: 'DM Sans';
    font-style: normal;
    font-weight: 700;
    font-size: 0.7rem;
  }

  .lotPassword {
    color: #22a45d;
    font-family: 'DM Sans', sans-serif;
    font-family: 'Mitr', sans-serif;
    padding-top: 20px;
    padding-right: 10px;
    font-size: 0.7rem;
  }

  h1 {
    color: #22a45d;
    font-family: 'DM Sans', sans-serif;
    font-family: 'Mitr', sans-serif;
    font-family: 'Prompt', sans-serif;
    font-size: 1.5rem;
  }

  input[type='text'] {
    border: 1px solid #cfd8dc;
    font-size: 0.7rem;
    height: 50px;
    width: 100%;
    //   padding: 10px;
    border-radius: 50px;
    padding-left: 20px;
    margin: 10px 0px 10px 0px;
  }
}

@media screen and (min-width: 768px) and (max-width: 991px) {
  .imgeBg {
    display: none;
  }
  .signinbutton {
    background-color: white;
    color: #22a45d;
    border: 2px solid #22a45d;
    font-family: 'DM Sans';
    font-style: normal;
    text-align: center;
    border-radius: 50px;
    padding-top: 10px;
    padding-bottom: 10px;
    padding-right: 20px;
    padding-left: 20px;
    margin-right: 10px;
    width: 35%;
  }

  .login {
    border: none;
    color: white;
    text-align: center;
    border-radius: 50px;
    background-color: #22a45d;
    font-family: 'DM Sans';
    font-style: normal;
    padding-top: 10px;
    padding-bottom: 10px;
    padding-right: 20px;
    padding-left: 20px;
    margin-left: 10px;
    width: 35%;
  }
}
</style>
