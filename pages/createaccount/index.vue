<template>
  <div class="container">
    <CreateaccountPage />
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
  layout: "DefaultLayout",
}
</script>
<style lang="scss" scoped>
.container {
  width: 50%;
}
@media screen and (max-width: 1880px) {
 .container {
  width: 80%;
} 
  
}
@media screen and (max-width: 1420px) {
 .container {
  width: 80%;
} 
  
}
@media screen and (max-width: 991px) {
 .container {
  width: 100%;
} 
  
}
@media screen and (max-width: 599px) {
 .container {
  width: 100%;
} 
  
}

</style>
