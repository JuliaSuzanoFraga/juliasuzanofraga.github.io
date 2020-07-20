<!DOCTYPE html>
<html lang="pt-br">

<head>
    <!-- Meta tags Obrigatórias -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">

    <style>
        img {
            max-width: 98%;
            width: auto;
            height: auto;
        }
        
        .dropdown-menu {
            min-width: 0px !important;
        }
    </style>
    <title>Professor Francisco Boldt</title>
    <link rel="icon" href="images/fbicon.png" type="image/png">
</head>

<body>
    <!--================Header Menu Area =================-->
    <header>
        <nav class="navbar navbar-expand-lg navbar-light">
            <div class="container">
                <a class="navbar-brand align-self-start" href="http://www.serra.ifes.edu.br"><img src="images/serra-horizontal-preto.png" alt=""></a>
                <div>
                    <button class="navbar-toggler mr-5" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
						<span class="navbar-toggler-icon"></span>
					</button>

                    <div class="collapse navbar-collapse" id="navbarSupportedContent">
                        <ul class="navbar-nav mr-auto">
                            <li class="nav-item">
                                <a class="nav-link" href="index-pt.html">Início</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#education">Formação</a>
                            </li>
                            <li class="dropdown">
                                <a class="nav-link dropdown-toggle" href="#" data-toggle="dropdown">
									Ensino
								</a>
                                <div class="dropdown-menu dropdown-menu-right">
                                    <a class="dropdown-item p-2" href="#disciplines">Disciplinas</a>
                                    <div class="dropdown-divider"></div>
                                    <a class="dropdown-item p-2" href="#technical">Técnico</a>
                                    <a class="dropdown-item p-2" href="#master">Mestrado</a>
                                </div>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#research">Pesquisa</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#presentations">Apresentações</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="csppdserra">CSPPD</a>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </nav>
    </header>
    <!--================Header Menu Area =================-->

    <!-- Content Area -->

    <!--================Footer Area =================-->
    <footer class="footer_area p_120 my-5">
        <div class="container">
            <h2>Contato: <img src="images/email.png"></h2>
        </div>
    </footer>
    <!--================End Footer Area =================-->

    <!-- JavaScript (Opcional) -->
    <!-- jQuery primeiro, depois Popper.js, depois Bootstrap JS -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
    <script>
        $.get("homebanner-pt.html", function(data, status) {
            $("header").after(data);
        });
        $.get("education-pt.html", function(data, status) {
            $("footer").before(data);
        });
        $.get("research-pt.html", function(data, status) {
            $("footer").before(data);
        });
        $.get("disciplines-pt.html", function(data, status) {
            $("footer").before(data);
        });
        $.get("presentations-pt.html", function(data, status) {
            $("footer").before(data);
        });
    </script>
</body>

</html>
