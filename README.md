# projeto_portfolio
<!DOCTYPE html>
<html lang="pt-BR">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Portifólio Felippe Fardin Andreata</title>

    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/normalize/8.0.1/normalize.min.css"
      integrity="sha512-NhSC1YmyruXifcj/KFRWoC561YpHpc5Jtzgvbuzx5VozKpWvQ+4nXhPdFgmx8xqexRcpAglTj9sIBWINXa8x5w=="
      crossorigin="anonymous"
      referrerpolicy="no-referrer" />

    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Open+Sans:ital@0;1&display=swap"
      rel="stylesheet" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,700;1,700&display=swap"
      rel="stylesheet" />

    <link rel="stylesheet" href="fonts/NeueMachina-Regular.otf" />

    <link rel="stylesheet" href="css/header.css" />
    <link rel="stylesheet" href="css/global.css" />
    <link rel="stylesheet" href="css/acordeon.css" />
    <link rel="stylesheet" href="css/languages.css" />
    <link rel="stylesheet" href="css/portfolio.css" />
    <link rel="stylesheet" href="/css/experience.css">
    <link rel="stylesheet" href="/css/skills.css">
  </head>

  <body>
    <main class="main">
      <header class="header">
        <img
          src="/img/Captura perfil 2.png"
          alt="Foto do perfil"
          class="photo profile.photo" id="profile.photo" />

        <h1 class="title">
          Olá,<br />
          eu sou <span id="profile.name">Felippe Fardin</span>
        </h1>

        <div class="informations">
          <p class="job"><span id="profile.job">Estudante</span></p>
          <p class="location"><span id="profile.location">Vila Velha/ES</span></p>
          <p class="phone">
            <a href="tel:(27)998642716"><span id="profile.phone">(27) 9 9964-2716</span></a>
          </p>
          <p class="email">
            <a href="mailto:felippefardin@gmail.com"><span cid="profile.email">felippefardin@gmail.com</span></a>
          </p>
        </div>
      </header>

      <section class="acordeon">
        <button class="trigger" type="button">
          <h2>Idiomas</h2></button>

        <div class="content">
          <ul class="languages" id="profile.languages">
            <li>Português (BR)</li>
            <li>Inglês</li>
            <li>Espanhol</li>
            <li>Italino</li>
          </ul>
        </div>
      </section>

      <section class="acordeon">
        <button class="trigger" type="button">
          <h2>Portfolio</h2></button>

        <div class="content">
          <ul class="portfolio">
            <li>
              <h3 class="title github">Criando um app de lembrete</h3>
              <a href="https://www.google.com" target="_blank"
                >www.google.com.br/</a
              >
            </li>
            <li>
              <h3 class="title github">Criando um app de lembrete</h3>
              <a href="https://www.google.com" target="_blank"
                >www.google.com.br</a
              >
            </li>
            <li>
              <h3 class="title">Criando um app de lembrete</h3>
              <a href="https://www.google.com" target="_blank"
                >www.google.com.br</a
              >
            </li>
          </ul>
        </div>
      </section>

      <section class="acordeon">
        <button class="trigger" type="button">
          <h2>Experiência Profissional</h2></button>

        <div class="content">
          <ul class="experience">
            <li>
              <h3 class="title">JavaScript / dio.com</h3>
              <span class="period">Jan 2024 - Current</span>
              <p>
                Em progresso para finalização do curso.
                Não tive oportunidade de atuar na área por enquanto.
            
              </p>              
            </li>
            <li>
              <h3 class="title">Aministrativo</h3>
              <span class="period">Agos 2013 - Nov 2020</span>
              <p>
                Experiência de mais de 10 anos na área administrativa empresarial.
              </p>              
            </li>
          </ul>
        </div>
      </section>

      <section class="acordeon">
        <button class="trigger" type="button">
          <h2>Skills</h2>
        </button>
        <div class="content"> 
          <div class="skills">
          <section class="tools">
            <h3>Ferramentas</h3>
            <ul id="profile.skills.hardSkills">
              <li><img src="/img/icons/tools/js.svg" alt="JavaScript" title="JavaScript">
              </li>
              <li><img src="/img/icons/tools/html.svg" alt="html" title="html">
              </li>
              <li><img src="/img/icons/tools/css.svg" alt="css" title="css">
              </li>
              <li><img src="/img/icons/tools/phyton.svg" alt="phyton" title="phyton">
              </li>
            </ul>
          </section>
          <section class="personal">
            <h3>Pessoal:</h3>
            <ul id="profile.skills.softSkills">
              <li>Adaptável a mudança</li>
              <li>Facilidade de comunicação</li>
              <li>Organização</li>
              <li>Trabalho em equipe</li>
              <li>Flexibilidade</li>
            </ul>
          </section>
        </div>
      </section>
    </div>

    </main>

    <script src="js/acordeon.js"></script>
   <script src="/js/api.js"></script>
   <script src="/js/main.js"></script>
  </body>
</html>
