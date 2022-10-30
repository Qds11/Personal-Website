<template>
  <div class="topbar row justify-content-center" >
    <div class="col-lg-3 col-"></div>
<div class="col-lg-2 col-4 link" ><a href='#about' class="float-end" style="color:white">&lt; About Me/&gt;</a></div>

    <div class="col-lg-2 col-4 link"><a href="#proj"  style="color:white">&lt; Projects/&gt;</a></div>
    <div class="col-lg-2 col-4 link"><a href="#resume" class="float-start" style="color:white">&lt; Resume/&gt;</a></div>
    <div class="col-lg-3 col-"></div>
    <hr>
  </div>

</template>

<script>
export default {
    name: 'TopBar',
    props: {
        about: String,
        project: String,
        resume:String

    },
    computed:{
        getlink(id) {
            return "#"+id

}
    }
}

</script>


<style scoped>
.topbar{

  animation: slidedown 3s;


}
hr{
  width: 70%;
  margin-top: 100px;
   color: rgb(208, 206, 206);
}

a:link{
    text-decoration: none;
}
.link:hover,.link:focus{
 text-shadow: 3px 3px 4px rgb(219, 255, 12);
transform: translateY(-0.25em);
     transition: 0.4s;
}
html,body{
   overflow-x: initial !important
}
@keyframes slidedown {
  from{
  transform:translateY(-200%);
  opacity: 0;
  }
  to{
 transform:translateY(0%);
 opacity: 1;
  }
}

    @media (max-width: 822px) {
      .topbar{
       font-size: small;
      }

    }
</style>
