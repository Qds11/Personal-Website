<template>

    <div class="row justify-content-center myprojects ">
        <div class="col-lg-2 col-1"></div>
        <div class="col-lg-8 col-10 myproj">

            <h1 class="mb-5">My Projects</h1>
            <div class="flex-container projcontainer">
                <div class="proj-item  align-self-center">
                    <div class="proj-content">
                        <div class="info">
                            <h5 class="mt-3 ">Smart Medicine Box</h5>
                            <h6 class="mb-3">2020</h6>
                            <ul class="mainUl">
                                <li>
                                    Inspired by IoT
                                </li>
                                <li>
                                    Raspberry pi based medicine box that automates dispensing of pills
                                </li>
                                <li>
                                    Three user interfaces used to control the medicine box: <ul>
                                        <li>Tkinter GUI</li>
                                        <li> web application </li>
                                        <li>Andriod application</li>
                                    </ul>
                                </li>
                            </ul>
                        </div>
                        <footer class="githublink">
                            <p class="small">Click <a href="https://github.com/Qds11/Smart-Medicine-Box">here</a> to
                                view the
                                web app on GitHub</p>
                        </footer>
                    </div>

                </div>
                <div class=" proj-item align-self-start">
                    <div class="proj-content">
                        <div class="info">
                            <h5 class="mt-3 ">SingHealth Hackathon</h5>
                            <h6 class="mb-3">2021</h6>
                            <ul class="mainUl">
                                <li>
                                    Web application for SingHealth auditors to digitally manage and perform audits
                                </li>
                                <li>
                                    Express JS, Node JS, Firebase, HTML ,CSS, Javascript
                                </li>
                            </ul>
                        </div>
                        <footer class="githublink">
                            <p class="small">Click <a href="https://github.com/Qds11/Audit-Web-App">here</a> to view
                                it on GitHub</p>
                        </footer>
                    </div>

                </div>
                <div class=" proj-item  align-self-center">
                    <div class="proj-content">
                        <div class="info">
                            <h5 class="mt-3 ">Educational Web App</h5>
                            <span class="small"> In Progress</span>
                            <h6 class="mb-3">2022 </h6>
                            <ul class="mainUl">
                                <li>
                                    Web application for secondary school students to improve on their grades
                                </li>
                                <li>
                                    Features:
                                    <ul>
                                        <li>
                                            Forum - shared learning
                                        </li>
                                        <li>
                                            Progress Tracker - track grades
                                        </li>
                                        <li>
                                            Flash cards & quizzes
                                        </li>
                                    </ul>
                                </li>
                                <li>
                                    Firebase, HTML, CSS, Javascript, Vue JS
                                </li>
                            </ul>
                        </div>
                        <!-- <footer class="githublink">
                            <p class="small">Click <a href="https://github.com/tanyipeng834/WAD-2---PROJECT">here</a> to
                                see
                                web app on GitHub</p>
                        </footer> -->
                    </div>

                </div>


            </div>
        </div>
        <div class="col-lg-2 col-1"></div>
        <hr>
    </div>

</template>

<script>
    export default {
        name: 'Projects',
    }
</script>


<style scoped>
hr{
  width: 70%;
  margin-top: 100px;
  color: rgb(208, 206, 206);
}
    ul {
        font-size: small;
        text-align: left;
    }

    .mainUl {
        list-style-type: "+ ";
    }

    .proj-item {
        width: 100%;

      

        /* animation: 2s slide-up 0.5s forwards;
        transform: translateY(150%); */


    }

    .info {
        margin-bottom: 50px;
    }

    .githublink {

        bottom: 0;
        font-size: small;
        text-align: left;
    }

    .proj-content {
        padding: 5px;

    }



    .flex-container {
        padding: 0;
        margin: 0;
        list-style: none;
        height: 400px;
        display: flex;

    }



    .center {
        align-self: center;
    }

    .proj-item:nth-of-type(1) {
        background-image: linear-gradient(to bottom right, rgba(255, 0, 0, 0), rgb(11, 21, 214, 0.5));
    }

    .proj-item:nth-of-type(2) {
        background-image: linear-gradient(to bottom right, rgba(255, 0, 0, 0), rgb(246, 0, 193, 0.5));
    }

    .proj-item:nth-of-type(3) {
        background-image: linear-gradient(to bottom right, rgba(255, 0, 0, 0), rgb(0, 246, 70, 0.5));


    }

    @keyframes slide-up {
        to {
            transform: translateY(0);
        }
    }


    a {
        color: orangered;
          text-decoration: none;
    }



    a:hover {
        text-decoration: underline;
        color: orangered;
    }

    @media (max-width: 1219px) {
        .proj-item {
            height: auto;
            font-size: xx-small;
        }

        .flex-container {
            height: auto;

        }

    }

    @media (max-width: 925px) {
        .proj-item {
            height: auto;
            font-size: small;
            width: 100%;
        }

        .flex-container {
            display: block;
        }

    }
</style>