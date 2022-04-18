# Html-project
Repositório para o desenvolvimetno do desafio de HTML do DIo 
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel = "stylesheet" href="style\main.css">
    <link rel="stylesheet"   href="style/own/owl.carousel.min.css">
    <link rel="stylesheet"   href="style/own/owl.theme.default.min.css">
    <link rel="stylesheet"   href="style/responsive.css" >


    <title class="titulo" > NETFLIX</title>
</head>
<body> 
    <header>
        <div class ="container">
            <h2 class="Logo "> NETFLIX </h2>
            <nav>
                <a href="#"> Início</a>
                <a href="https://www.netflix.com/br/browse/genre/83"> séries</a>
                <a href="https://www.netflix.com/br/browse/genre/1365"> Filmes</a>
                <a href="https://www.netflix.com/br/browse/genre/2243108"> Documentários</a>
            </nav>
        </div>
    </header>
    <main>
        <div class="filme-principal">
            <div class="containere">
                <h3 class="titulo2">PRISON BREAK</h3>
                <p class="description">
                Lincoln Burrows é condenado injustamente à pena de morte. Só lhe resta confiar no irmão Michael Scofield, que executa
                     um plano de fuga e se vê no meio de uma perigosa conspiração.
                </p>

            </div>
            <div class="Botoes">
   
            <button role="button" class="Botão">
               <a href="https://www.youtube.com/watch?v=C2ssQOyVJqQ" target="blank">ASSISTIR AGORA</a> 

                
            </button>
            <button role = "button" class="Botão">
                <a href="style\sub.html"> MAIS INFORMAÇÕES</a>    

            </button>
        </div>
        </div>
    
    </main>

    <div class="carrosel-filmes">
      <div class="owl-carousel owl-theme">
          <div class="item">
              <img class="box-filme" src="img\Filme img 3.jpg" alt="" srcset="">
          </div>
          <div class="item">
            <img class="box-filme" src="img\Filme img 2.jpg" alt="" srcset="">
        </div>
        <div class="item">
            <img class="box-filme" src="img/imagem 60.jpg" alt="" srcset="">
        </div>
        <div class="item">
            <img class="box-filme" src="img\Filme img 5.jpg" alt="" srcset="">
        </div>
        <div class="item">
            <img class="box-filme" src="img/imagem 50.jpg" alt="" srcset="">
        </div>
        <div class="item">
            <img class="box-filme" src="img\Filme im 7.jpg" alt="" srcset="">
        </div>
      </div>

    </div>

<script src="own/jquery.min.js"></script>
<script src="own/owl.carousel.min.js"></script>
<script src="own/setup.js"></script>

</body>
</html>
