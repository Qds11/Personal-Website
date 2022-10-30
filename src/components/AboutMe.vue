<template>
  <div class="AboutMe row mt-5 justify-content-center">
    <h1 class="mb-5">About Me</h1>
    <div class="col-lg-2"></div>
<div class="col-lg-4 col-10"><img src="../assets/profilepic.jpg" alt=""></div>
<div class="col-lg-4 col-10 details d-flex align-items-center">

  Hi! I am Qi Qing, a SMU Information Systems undergraduate who is an aspiring
      web developer!
      <br><br>
      I enjoy critical thinking
      and problem solving through creative
      means and feel that web development is
      the perfect outlet for them.

</div>
 <div class="col-lg-2"></div>
 <hr>
  </div>
</template>

<script>
export default {
  name: 'AboutMe',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1{
 animation: fadeIn 4s;

}
img{
  width: 100%;
  height: auto;
  animation: 2s slide-right 0.5s forwards, fadeIn 6s;
    transform:translateX(-200%);
}

.details{
  height: auto;
  width: 100;


 background-image:linear-gradient(to bottom right, rgba(255,0,0,0), rgba(20, 22, 72, 0.532));
  text-align: justify;

  font-size: 1em;
 animation: fadeIn 5s;
}
hr{
  width: 70%;
  margin-top: 100px;
    color: rgb(208, 206, 206);
}
@keyframes fadeIn {
  0% { opacity: 0; }
  100% { opacity: 1; }
}

    @media (max-width: 822px) {
      .topbar{
       font-size: small;
      }

    }
@keyframes slide-right {
  to {
    transform:translateX(0);
  }
}

</style>
