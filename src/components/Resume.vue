<template>
    <div>
        <div class="row justify-content-center resume mt-5">
            <h1 class="mb-5">My Resume</h1>
            <div class="col-lg-2 col-"></div>
               <div class="col-lg-4 col-md-5 col-10 align-self-center">Click <a href="LimQiQing_resume.pdf" download>here</a>
                to download my resume</div>
            <div class="col-lg-4 col-md-5 col-10"><img src="../assets/ResumePic.jpg" alt=""></div>

                  <div class="col-lg-2 col-"></div>
        </div>
        <hr>
    </div>

</template>

<script>
    export default {
    name: 'Resume',

    }
</script>


<style scoped>
hr{
  width: 70%;
  margin: auto;

  color: rgb(208, 206, 206);
}
    img {
        width: 100%;
        height: auto;
        opacity: 0.75;

    }

    .resume {
        animation: 3s fadeIn;

        position: relative;
         padding-bottom: 100px;
         overflow-y:hidden;



    }

    img:hover {
        transition: 0.6s;
        transform: scale(1.35);
    }

    a:link {
        text-decoration: none;
        color: orangered;
        transition: 0.4s;
    }

    a:hover,
    a:focus {
        text-decoration: underline;
        transform: translateY(-0.25em);

    }
       @keyframes slide-up {
        to {
            transform: translateY(0);
        }

    }
    @keyframes fadeIn {
  0% { opacity: 0; }
  100% { opacity: 1; }
}
    @media (max-width: 767px) {
        img {
            display: none;
        }
        .resume{
            margin-bottom: 100px;
        }



    }
</style>