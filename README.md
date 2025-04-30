<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfólio | Seu Nome</title>
  <link rel="stylesheet" href="style.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
  <!-- Cabeçalho -->
  <header>
    <nav>
      <ul>
        <li><a href="#sobre">Sobre</a></li>
        <li><a href="#habilidades">Habilidades</a></li>
        <li><a href="#projetos">Projetos</a></li>
        <li><a href="#contato">Contato</a></li>
      </ul>
    </nav>
  </header>

  <!-- Seção Hero -->
  <section class="hero">
    <h1>Olá, eu sou <span class="destaque">[Seu Nome]</span></h1>
    <p>Desenvolvedor Full-Stack | Python & JavaScript</p>
    <a href="#projetos" class="btn">Ver Projetos</a>
  </section>

  <!-- Sobre Mim -->
  <section id="sobre" class="sobre">
    <h2>Sobre Mim</h2>
    <p>Sou um desenvolvedor apaixonado por criar soluções tecnológicas eficientes. Tenho experiência em X, Y, Z...</p>
  </section>

  <!-- Habilidades -->
  <section id="habilidades" class="habilidades">
    <h2>Habilidades Técnicas</h2>
    <div class="habilidades-container">
      <div class="habilidade-item">
        <i class="fab fa-js"></i>
        <p>JavaScript</p>
      </div>
      <div class="habilidade-item">
        <i class="fab fa-react"></i>
        <p>React</p>
      </div>
      <!-- Adicione mais habilidades aqui -->
    </div>
  </section>

  <!-- Projetos -->
  <section id="projetos" class="projetos">
    <h2>Projetos</h2>
    <div class="projeto-card">
      <h3>Nome do Projeto</h3>
      <p>Descrição breve do projeto e tecnologias usadas.</p>
      <a href="#" class="btn">Código no GitHub</a>
    </div>
    <!-- Adicione mais projetos -->
  </section>

  <!-- Contato -->
  <section id="contato" class="contato">
    <h2>Contato</h2>
    <div class="contato-links">
      <a href="mailto:seu@email.com"><i class="fas fa-envelope"></i> Email</a>
      <a href="https://github.com/seuuser"><i class="fab fa-github"></i> GitHub</a>
      <a href="https://linkedin.com/in/seuuser"><i class="fab fa-linkedin"></i> LinkedIn</a>
    </div>
  </section>

  <footer>
    <p>© 2024 [Seu Nome]. Todos os direitos reservados.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
