""CÓDIGO HTML""
<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Barra de navegação</title>
    <link rel="stylesheet" href="css/style.css">
</head>

<body>
    <section class="container">
        <nav>
            <ul>

                <li><a href="#Produtos"> Produtos</a></li>

                <li><a href="#Desafios"> Desafios</a></li>

                <li><a href="#Recursos"> Recursos</a></li>

                <li><a href="Outros links"> Outros links</a></li>

                <li><a href="#Entrar">Entrar</a></li>

                <button class="Retângulo_2">Experimente gratuitamente</button>
            </ul>
        </nav>

    </section>
    <section>
        <div class="Ondeck">
            <h1>Ondeck é sua ferramenta <br> de teleconferência remota</h1>
        </div>
        <div class="Ondeck_é_um_serviço_que_permite_criar_videocham">
            <p>
                Ondeck é um serviço que permite criar videochamadas
                <br> lindas, online e criptografadas para você e sua equipe remota.
            </p>
        </div>

        <button class="Retângulo_1">Experimente gratuitamente</button>
        <div class="Classificação_5_0_com_base_nas_visualizações_de">
            <p1>
                Classificação 5.0 com base nas visualizações de:
            </p1>
        </div>
    </section>


    <section>
        <div class="Sara_Oliver">
            <img src="img/Sara Oliver.png" />
        </div>
        <div class="Netflix_Logo">
            <img src="img/Netflix Logo.png" />
        </div>
        <div class="Spotify_Logo">
            <img src="img/Spotify Logo.png" />
        </div>
        <div class="Walmart_Logo">
            <img src="img/Walmart Logo.png" />
        </div>
        <div class="Shopify_Logo">
            <img src="img/Shopify Logo.png" />
        </div>
        <div class="Capterra_Logo">
            <img src="img/Capterra Logo.png" />
        </div>
        <div class="AlternativeTo_Logo">
            <img src="img/AlternativeTo Logo.png" />
        </div>
    </section>


</body>

</html>

""CÓDIGO CSS""


*{
    background-color: #f3ece4;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
.container{
    max-width: 1400px;
    padding: 3%;
    margin: 0 auto;
}
nav{
    display: flex;
    align-items: center;
    justify-content: space-between;
    
}
nav ul{
    list-style: none;
}
nav ul li{
    display: inline-block;
}
nav ul li a{
    padding: 10px 65px;
    text-decoration: none;
    font-size: 19px;
    color: #6d6d6d;
    border-radius: 30px;
    transition: 0.6s;
    left: 1062.172px;
    z-index: 25;
}
nav ul li a:hover{
    background-color: rgb(7, 173, 22);
}
.Sara_Oliver {
    background-image: url("Sara Oliver.png");
    position: absolute;
    left: 950px;
    top: 100px;
    width: 0px;
    height: 0px;
    z-index: 9;
  }
  .Netflix_Logo {
    background-image: url("Netflix Logo.png");
    position: absolute;
    left: 300px;
    top: 589px;
    width: 0px;
    height: 0px;
    z-index: 21;
  }
  .Shopify_Logo {
    background-image: url("Shopify Logo.png");
    position: absolute;
    left: 80px;
    top: 589px;
    width: 50px;
    height: 0px;
    z-index: 0;
  }
  .Walmart_Logo {
    background-image: url("Walmart Logo.png");
    position: absolute;
    left: 550px;
    top: 589px;
    width: 0px;
    height: 0px;
    z-index: 22;
  }
  .Spotify_Logo {
    background-image: url("Spotify Logo.png");
    position: absolute;
    left: 850px;
    top: 589px;
    width: 0px;
    height: 0px;
    z-index: 19;
  }
  .Capterra_Logo {
    background-image: url("Capterra Logo.png");
    position: absolute;
    left: 20px;
    top: 325px;
    width: 34px;
    height: 34px;
    z-index: 15;
  }
  .AlternativeTo_Logo {
  background-image: url("AlternativeTo Logo.png");
  position: absolute;
  left: 70px;
  top: 325px;
  width: 25px;
  height: 24px;
  z-index: 16;
}

  .Retângulo_2 {
    border-radius: 100px;
    background-color: rgb(7, 173, 22);
    position: absolute;
    left: 1135px;
    top: 25px;
    width: 155px;
    height: 60px;
    z-index: 27;
  }
  .Ondeck{
    font-size: 20px;
    font-family: "Montserrat";
    line-height: 1.2;
    position: absolute;
    top: 180px;
    left: 15px;
  }
  .Ondeck_é_um_serviço_que_permite_criar_videocham {
    font-size: 16px;
    font-family: "Montserrat";
    line-height: 1.2;
    text-align: left;
    position: absolute;
    left: 15px;
    top: 250px;
    z-index: 34;
  }
  .Classificação_5_0_com_base_nas_visualizações_de{
    font-size: 16px;
    font-family: "Montserrat";
    line-height: 1.2;
    text-align: left;
    position: absolute;
    left: 15px;
    top: 300px;
    z-index: 32;
  }
  
  .Retângulo_1{
    border-radius: 100px;
    background-color: rgb(7, 173, 22);
    position: absolute;
    left: 10px;
    top: 370px;
    width: 155px;
    height: 60px;
    z-index: 27;
  }
