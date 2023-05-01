<!DOCTYPE html>
<html>

<head>
    <meta charset="UTF-8">
    <title>README.md com Bootstrap</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-0evHe/X+R7YkIZDRvuzKMRqM+OrBnVFBL6DOitfPri4tjfHxaWutUpFmBp4vmVor" crossorigin="anonymous">
    <link rel="icon" type="icon" href="images/github.png">

    <link rel="stylesheet" href="styleGit.css">
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.3.1/css/all.css"
        integrity="sha384-mzrmE5qonljUremFsqc01SB46JvROS7bZs3IO2EmfFsd15uHvIt+Y8vEf7N7fWAU" crossorigin="anonymous">

    <script src="https://cdn.jsdelivr.net/npm/showdown@1.9.1/dist/showdown.min.js"></script>
    <script>
        window.onload = function () {
            var converter = new showdown.Converter();
            var readmeContent = document.getElementById("readme-content");
            fetch("https://raw.githubusercontent.com/mano3queijos/mano3queijos/master/README.md")
                .then(response => response.text())
                .then(text => {
                    readmeContent.innerHTML = converter.makeHtml(text);
                });
        }
    </script>
    <style>

    </style>
</head>

<body style="background-color: #000000;">

    <header>
        <nav class="navbar navbar-light navbar-expand-md navbar mx-auto bar-dark opacity-75  text-center">
            <div class="container-fluid">
                <!-- <a href="index.html" class="nav-link"><img src="images/" alt=""></a>-->

                <a href="index.html" class="nav-link"> <img style="margin-top: -5px;" src="./images/bonfire.gif"
                        width=" 50em" alt=""></a>

                <button class="navbar-toggler" data-toggle="collapse" data-target="#nav-principal">
                    <i class="fas fa-bars text-white"></i>
                </button>
                <!-- 
                <img src="https://em-content.zobj.net/source/microsoft-teams/337/smiling-face-with-sunglasses_1f60e.png" -->
                <div class="collapse navbar-collapse justify-content-center" id="nav-principal">
                    <ul class="navbar-nav text-center">
                        <li class="nav-item"></li>
                        <!-- <li class="nav-item"><a href="#" class="nav-link"> <img src="./images/github.png" width="90em"
                                    alt=""></a></li> -->
                        <li class="nav-item"><a href="github.html" class="nav-link"> <img src="./images/github.png"
                                    width=" 65em" alt=""></a></li>

                        <li class="nav-item"><a href="heart/heart.html" class="nav-link">
                                <img src="./images/hearth.png" width=" 60em" alt=""></a>
                            </a></li>
                        <li class="nav-item"><a href="#" class="nav-link"><img style="margin-top: -10px;"
                                    src="./images/tdsotm.png" width=" 120em" alt=""></a></li>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>


    <div class="container">
        <div class="row">
            <div class="col-md-12">
                <div id="readme-content"></div>
            </div>

            <div>

                <h2>Hi, Emanuel Here</h2>
                <ul>
                    <li>- 💻I'm proficient in Java, HTML, CSS, and Bootstrap.</li>
                    <li>- 🌱 I'm studying java web and data structure</li>
                    <li>- 👨‍🎓 studying software engineering at ucsal</li>
                </ul>

            </div>

            <div>
                <h2> Speak to me </h2>

                <a style="text-decoration: none;" href="https://github.com/mano3queijos">

                    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"
                        alt="">
                </a>

                <a style="text-decoration: none;" href="https://wa.me/5571983838579">

                    <img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white&link"
                        alt="">
                </a>
                <a style="text-decoration: none;" href="mailto:emanuel.almeida@ucsal.edu.br"><img
                        src="https://camo.githubusercontent.com/927d6b3961fa048ff7303daf291cb5869dfa25018997cf8c1373c2f6a85b1458/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f2d476d61696c2d2532333333333f7374796c653d666f722d7468652d6261646765266c6f676f3d676d61696c266c6f676f436f6c6f723d7768697465"
                        data-canonical-src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&amp;logo=gmail&amp;logoColor=white"
                        style="max-width: 100%;"></a>
                <a style="text-decoration: none;" href="https://youtube.com/@emanuelalmeida7723">
                    <img src="https://camo.githubusercontent.com/d79c5549652f9c7690992eb49571d216a70a480681561cbd93bfbfc77c491e54/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f596f75547562652d4646303030303f7374796c653d666f722d7468652d6261646765266c6f676f3d796f7574756265266c6f676f436f6c6f723d7768697465"
                        data-canonical-src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&amp;logo=youtube&amp;logoColor=white"
                        style="max-width: 100%;"></a>
            </div>


            <div>
                <h2>Pages online</h2>

                <a style="text-decoration: none;" href="https://mano3queijos.github.io/heart/heart.html">
                    <img height="90px"
                        src="https://user-images.githubusercontent.com/101946589/235334767-6ee68318-2daf-483a-8f83-c22e23cd7454.png">
                </a>
                <a href="https://mano3queijos.github.io/heart/heart.html">
                    <img height="100px" src="images/bonfire.gif">
                </a>
            </div>






            <div>
                <h2>Languages and Tools:
                </h2>

                <a>
                    <img height="175em"
                        src="https://github-readme-stats.vercel.app/api?username=mano3queijos&show_icons=true&theme=radical">


                </a>

                <a>
                    <img height="175em"
                        src="https://github-readme-stats.vercel.app/api/top-langs/?username=mano3queijos&langs_count=8&theme=radical">
                </a>


                <a>
                    <img height="175em" width="100em" src="https://media.tenor.com/8wBCqZH60U8AAAAC/computer-cat.gif">
                </a>





            </div>


        </div>
        <img style="align-items: center;" height="25m"
            src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
        <img style="align-items: center;" height="25m"
            src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
        <img style="align-items: center;" height="25m"
            src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white">
        <img style="align-items: center;" height="25m"
            src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white">

    </div>


    </div>
    </div>

    <script src="https://cdnjs.cloudflare.com/ajax/libs/typed.js/2.0.11/typed.min.js"></script>

    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"
        integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo"
        crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js"
        integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49"
        crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js"
        integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy"
        crossorigin="anonymous"></script>

</body>

</html>
