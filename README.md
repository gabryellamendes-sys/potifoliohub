<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>PortfolioHUB</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family: Arial, Helvetica, sans-serif;
    }

    body{
      background:#f4f4f4;
      color:#333;
    }

    header{
      background:#0d1117;
      color:white;
      padding:40px;
      text-align:center;
    }

    header h1{
      font-size:40px;
      margin-bottom:10px;
    }

    nav{
      background:#161b22;
      padding:15px;
      text-align:center;
    }

    nav a{
      color:white;
      text-decoration:none;
      margin:0 15px;
      font-weight:bold;
    }

    section{
      padding:40px;
    }

    .cards{
      display:flex;
      flex-wrap:wrap;
      gap:20px;
      justify-content:center;
    }

    .card{
      background:white;
      width:300px;
      padding:20px;
      border-radius:10px;
      box-shadow:0 0 10px rgba(0,0,0,0.1);
      transition:0.3s;
    }

    .card:hover{
      transform:scale(1.03);
    }

    .card h3{
      margin-bottom:10px;
      color:#0d1117;
    }

    footer{
      background:#0d1117;
      color:white;
      text-align:center;
      padding:20px;
      margin-top:30px;
    }

    .btn{
      display:inline-block;
      margin-top:15px;
      padding:10px 15px;
      background:#238636;
      color:white;
      text-decoration:none;
      border-radius:5px;
    }

    .btn:hover{
      background:#2ea043;
    }

    .contato a{
      color:#238636;
      text-decoration:none;
      font-weight:bold;
    }
  </style>
</head>

<body>

  <header>
    <h1>PortfolioHUB</h1>
    <p>Meu Portifolio profissional acadêmico</p>
  </header>

  <nav>
    <a href="#sobre">Sobre</a>
    <a href="#projetos">Projetos</a>
    <a href="#contato">Contato</a>
  </nav>

  <section id="sobre">
    <h2>Sobre Mim</h2>
    <br>

    <p>
      Olá! Meu nome é Gabryella Mendes Ferreira.
      Sou estudante de Engenharia de Software.
      Este site foi desenvolvido para apresentar meus projetos acadêmicos
      e profissionais utilizando GitHub e GitHub Pages.
    </p>
  </section>

  <section id="projetos">
    <h2>Meu Projeto</h2>
    <br>

    <div class="cards">

      <div class="card">
        <h3>Portfólio Acadêmico</h3>

        <p>
          Projeto desenvolvido para apresentar atividades,
          projetos acadêmicos e evolução profissional na área
          de Engenharia de Software.
        </p>

        <a href="https://github.com/gabryellamendes-sys/PortfolioHub/blob/main/PortifolioHub.pdf"
           target="_blank"
           class="btn">
          Ver Projeto
        </a>
      </div>

    </div>
  </section>

  <section id="contato" class="contato">
    <h2>Contato</h2>
    <br>

    <p>
      Email:
      gabryella.mendes@sempreceub.com
    </p>

    <br>

    <p>
      LinkedIn:
      <a href="https://www.linkedin.com/in/gabryella-mendes-4926ab3b8?utm_source=share_via&utm_content=profile&utm_medium=member_ios"
         target="_blank">
         Meu LinkedIn
      </a>
    </p>

    <br>

    <p>
      GitHub:
      <a href="https://github.com/gabryellamendes-sys"
         target="_blank">
         Meu GitHub
      </a>
    </p>

  </section>

  <footer>
    <p>© 2026 - PortfolioHUB</p>
  </footer>

</body>
</html>
