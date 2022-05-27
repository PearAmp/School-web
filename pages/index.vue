<template>
  <div class="container">
    <SigninPage />
    
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>
<style lang="scss" scoped>
.container {
  width: 50%;
}
@media screen and (max-width: 1880px) {
 .container {
  width: 80%;
  text-align: center;
} 
  
}
@media screen and (max-width: 1420px) {
 .container {
  width: 80%;
  text-align: center;
} 
  
}
@media screen and (max-width: 991px) {
 .container {
  width: 100%;
  text-align: center;
} 
  
}
@media screen and (max-width: 599px) {
 .container {
  width: 100%;
  text-align: center;
} 
  
}

</style>
