# projeto-rubra
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Projeto Rubra - Combate à Pobreza Menstrual</title>

  <!-- CSS incorporado -->
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth; /* Rolagem suave */
    }

    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      background: #fff5f5;
      color: #333;
    }

    /* Animações */
    @keyframes fadeInUp {
      from {
        opacity: 0;
        transform: translateY(30px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    .animate {
      opacity: 0;
      animation: fadeInUp 1s forwards;
    }

    .animate-delay-1 {
      animation-delay: 0.3s;
    }

    .animate-delay-2 {
      animation-delay: 0.6s;
    }

    .animate-delay-3 {
      animation-delay: 0.9s;
    }

    /* Navbar */
    .navbar {
      position: fixed;
      top: 0;
      width: 100%;
      background: #d4809c;
      color: white;
      display: flex;
      justify-content: space-between;
      padding: 1rem 2rem;
      z-index: 1000;
    }

    .navbar .menu {
      list-style: none;
      display: flex;
    }

    .navbar .menu li {
      margin-left: 1rem;
    }

    .navbar .menu a {
      color: white;
      text-decoration: none;
      transition: 0.3s;
    }

    .navbar .menu a:hover {
      color: #ffd6e0;
    }

    /* Hero */
    .hero {
      height: 100vh;
      background: linear-gradient(135deg, #ce6085, #ff4d6d);
      color: white;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 2rem;
    }

    .hero h1 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
    }

    .hero p {
      font-size: 1.2rem;
      margin-bottom: 2rem;
    }

    .btn {
      background: white;
      color: #6e1983;
      padding: 0.7rem 1.5rem;
      border-radius: 25px;
      text-decoration: none;
      font-weight: bold;
    }

    .btn:hover {
      background: #ffd6e0;
    }

    /* Seções */
    .section {
      padding: 4rem 2rem;
    }

    .section.alt {
      background: #ffe6eb;
    }

    .section h2 {
      text-align: center;
      color: #b3003c;
      margin-bottom: 2rem;
    }

    .center {
      text-align: center;
      margin-bottom: 2rem;
    }

    /* Grid */
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 2rem;
      align-items: center;
    }

    .grid img {
      max-width: 100%;
      border-radius: 10px;
    }

    /* Cards */
    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
    }

    .card {
      background: white;
      border-radius: 12px;
      padding: 1.5rem;
      box-shadow: 0px 2px 8px rgba(0,0,0,0.15);
      text-align: center;
    }

    .card h3 {
      color: #b3003c;
      margin: 1rem 0;
    }

    .card.destaque {
      background: #fff0f5;
      border: 2px solid #c96d8c;
    }

    /* Listas */
    .lista {
      margin-top: 1rem;
    }

    .lista li {
      margin-bottom: 0.5rem;
    }

    /* Footer */
    footer {
      background: #b3003c;
      color: white;
      text-align: center;
      padding: 1rem;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar">
    <div class="logo">Projeto Rubra</div>
    <ul class="menu">
      <li><a href="#home">Início</a></li>
      <li><a href="#pobreza">Pobreza Menstrual</a></li>
      <li><a href="#objetivo">Nosso Objetivo</a></li>
      <li><a href="#rubra">Projeto Rubra</a></li>
      <li><a href="#local">Local Físico</a></li>
      <li><a href="#ajudar">Como Ajudar</a></li>
      <li><a href="#contato">Contato</a></li>
    </ul>
  </nav>

  <!-- Hero -->
  <header id="home" class="hero">
    <div class="hero-text animate">
      <h1>Dignidade Menstrual é um Direito</h1>
      <p>Milhões de meninas e mulheres sofrem com a pobreza menstrual. O Projeto Rubra luta para mudar essa realidade.</p>
      <a href="#ajudar" class="btn">Apoie a Causa</a>
    </div>
  </header>

  <!-- Pobreza Menstrual -->
  <section id="pobreza" class="section">
    <h2 class="animate">O que é Pobreza Menstrual?</h2>
    <div class="grid">
      <div class="animate animate-delay-1">
        <p>
          A pobreza menstrual é a falta de acesso a produtos de higiene, saneamento básico e informação durante a menstruação.
          Esse problema afeta milhões de pessoas no mundo, gerando evasão escolar, constrangimento e problemas de saúde.
          A menstruação é um processo natural e faz parte da vida de milhões de meninas, mulheres e pessoas que menstruam em todo o mundo. No entanto, para muitas delas, esse período ainda é marcado por dificuldades, vergonha e falta de acesso a itens básicos de higiene.

A pobreza menstrual acontece quando não há acesso a absorventes, coletores, banheiros adequados ou mesmo informações seguras sobre o ciclo menstrual. Esse problema afeta diretamente a saúde, a educação e a dignidade. No Brasil, milhares de adolescentes já deixaram de frequentar a escola por não terem como se cuidar durante o período menstrual.

A pobreza menstrual não é apenas uma questão de higiene — é uma questão de direitos humanos. Todas as pessoas merecem viver esse processo com dignidade, sem constrangimento ou exclusão.

Falar sobre menstruação é quebrar tabus, combater preconceitos e garantir igualdade.
Apoiar essa causa significa lutar pela dignidade, educação e saúde de milhares de pessoas.

Juntos, podemos transformar realidades. Apoie, compartilhe e faça parte dessa mudança.
        </p>
        <ul class="lista">
          <li>🚫 Falta de absorventes e itens básicos</li>
          <li>🚫 Ausência de banheiros adequados</li>
          <li>🚫 Tabus e falta de informação</li>
        </ul>
      </div>
      <img class="animate animate-delay-2" src="https://assets.brasildefato.com.br/2024/09/image_processing20211018-12769-1xe46s2.jpeg" alt="Pobreza menstrual">
    </div>
  </section>

  <!-- Dados -->
  <section class="section alt">
    <h2 class="animate">Dados que Impressionam</h2>
    <div class="cards">
      <div class="card destaque animate animate-delay-1">
        <h3>1 a cada 4 adolescentes</h3>
        <p>No Brasil já deixou de ir à escola por não ter acesso a absorventes.</p>
      </div>
      <div class="card destaque animate animate-delay-2">
        <h3>4 milhões</h3>
        <p>De meninas não têm acesso a itens de higiene menstrual básicos.</p>
      </div>
      <div class="card destaque animate animate-delay-3">
        <h3>500 milhões</h3>
        <p>De pessoas no mundo sofrem com pobreza menstrual.</p>
      </div>
    </div>
  </section>

  <!-- Nosso Objetivo -->
  <section id="objetivo" class="section">
    <h2 class="animate">Nosso Objetivo</h2>
    <p class="center animate">Combater a pobreza menstrual por meio de doações, oficinas sustentáveis e educação.</p>
    <div class="cards">
      <div class="card animate animate-delay-1">
        <h3>Dignidade</h3>
        <p>Garantir que todas tenham acesso a itens básicos de higiene menstrual.</p>
      </div>
      <div class="card animate animate-delay-2">
        <h3>Educação</h3>
        <p>Promover conhecimento e quebrar tabus sobre a menstruação.</p>
      </div>
      <div class="card animate animate-delay-3">
        <h3>Impacto Social</h3>
        <p>Reduzir evasão escolar e melhorar a qualidade de vida das pessoas.</p>
      </div>
    </div>
  </section>

  <!-- Projeto Rubra -->
  <section id="rubra" class="section alt">
    <h2 class="animate">O Projeto Rubra</h2>
    <div class="grid">
      <img class="animate animate-delay-1" src="https://assets.brasildefato.com.br/2024/09/image_processing20211018-12769-w3pl3y.jpeg" alt="Projeto Rubra em ação">
      <div class="animate animate-delay-2">
        <p>
          O Projeto Rubra nasceu do desejo de mudar a realidade da pobreza menstrual. 
          Trabalhamos em três frentes principais:
        </p>
        <ul class="lista">
          <li> Arrecadação de absorventes e kits de higiene</li>
          <li> Oficinas de absorventes reutilizáveis</li>
          <li>Palestras e campanhas de conscientização</li>
          <li>Cada absorvente doado, cada oficina realizada e cada conversa aberta é um passo rumo à dignidade menstrual.
O Rubra não é apenas um projeto — é um movimento de empatia, igualdade e transformação.
Junte-se a nós e seja a mudança que garante mais respeito, saúde e futuro para milhares de pessoas.</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- Local Físico -->
  <section id="local" class="section">
    <h2 class="animate">Nosso Espaço</h2>
    <p class="center animate">
      Nosso espaço físico está sendo desenvolvido no Tinkercad, pensado para acolher a comunidade e oferecer oficinas educativas.
    </p>
    <div class="center animate animate-delay-1">
  src=<iframe width="725" height="453" src="http://www.tinkercad.com/embed/fQds1H1QaMP?editbtn=1&simlab=1" frameborder="0" marginwidth="0" marginheight="0" scrolling="no"></iframe>" 
</iframe>
  <!-- Como Ajudar -->
  <section id="ajudar" class="section alt">
    <h2 class="animate">Como Você Pode Ajudar</h2>
    <div class="cards">
      <div class="card animate animate-delay-1">
        <h3>Doações</h3>
        <p>Contribua com absorventes ou recursos financeiros.</p>
      </div>
      <div class="card animate animate-delay-2">
        <h3>Voluntariado</h3>
        <p>Participe das oficinas e ajude a comunidade.</p>
      </div>
      <div class="card animate animate-delay-3">
        <h3>Divulgação</h3>
        <p>Compartilhe informações e ajude a conscientizar mais pessoas e sempre que possível ajude meninas que passam por iso.</p>
      </div>
    </div>
  </section>

  <!-- Contato -->
  <section id="contato" class="section">
    <h2 class="animate">Contato</h2>
    <p class="card animate">Entre em contato com o Projeto Rubra para saber mais:</p>
    <p class="card animate">📧 contato@projetorubra.org</p>
    <p class="card animate">📍 Rua 1a, 123 - Cuiabá-MT</p>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 Projeto Rubra | Todos os direitos reservados</p>
  </footer>

  <!-- Script para ativar as animações ao rolar -->
  <script>
    const elementos = document.querySelectorAll('.animate');
    const mostrarAoRolar = () => {
      const trigger = window.innerHeight * 0.85;
      elementos.forEach(el => {
        const topo = el.getBoundingClientRect().top;
        if (topo < trigger) {
          el.style.animationPlayState = "running";
        }
      });
    };
    window.addEventListener('scroll', mostrarAoRolar);
    mostrarAoRolar();
  </script>

</body>
</html>
<style>
  /* Media Query para telas menores que 768px (celulares) */
@media (max-width: 768px) {
    .navbar {
        padding: 1rem;
    }

    .navbar .logo {
        position: relative;
        z-index: 1001; /* Garante que o logo fique por cima */
    }

    .navbar .menu {
        display: none; /* Esconde o menu por padrão */
        flex-direction: column;
        width: 100%;
        position: absolute;
        top: 0;
        left: 0;
        background: #b3003c;
        padding-top: 5rem; /* Espaço para o logo */
        text-align: center;
        transition: transform 0.3s ease-in-out;
        transform: translateY(-100%);
    }
    
    .navbar .menu li {
        margin: 0;
        padding: 1rem 0;
        border-bottom: 1px solid rgba(255, 255, 255, 0.2);
    }
    
    .navbar .menu li:last-child {
        border-bottom: none;
    }

    .navbar .menu.ativo {
        display: flex; /* Mostra o menu quando a classe 'ativo' é adicionada */
        transform: translateY(0);
    }

    /* Ícone do menu hambúrguer */
    .menu-toggle {
        display: block; /* Mostra o ícone */
        cursor: pointer;
        font-size: 2rem;
        position: relative;
        z-index: 1001;
    }
}

/* Ícone do menu hambúrguer (escondido em telas grandes) */
.menu-toggle {
    display: none;
}
</style>
<nav menu-toggle>
  <body><div class="menu-toggle" onclick="toggleMenu()">
    &#9776; </div>

<script>
    function toggleMenu() {
        const menu = document.querySelector('.navbar .menu');
        menu.classList.toggle('ativo');
    }
</script>
</body>
<style>
  .navbar {
    position: fixed;
    top: 0;
    width: 100%;
    background: transparent; /* começa transparente */
    color: white;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem 2rem;
    z-index: 1000;
    transition: background 0.3s, box-shadow 0.3s;
  }

  .navbar.scrolled {
    background: #d4809c; /* cor sólida ao rolar */
    box-shadow: 0 2px 8px rgba(0,0,0,0.3);
  }

  /* deixa o logo visível no topo */
  .navbar .logo {
    font-weight: bold;
    font-size: 1.2rem;
    color: white;
  }

  /* Links */
  .navbar .menu li a {
    color: white;
    text-decoration: none;
    transition: 0.3s;
  }

  .navbar .menu li a:hover,
  .navbar .menu li a.ativo {
    color: #ffd6e0;
    font-weight: bold;
  }
</style>

<script>
  // navbar muda de estilo ao rolar
  window.addEventListener('scroll', () => {
    const navbar = document.querySelector('.navbar');
    if (window.scrollY > 50) {
      navbar.classList.add('scrolled');
    } else {
      navbar.classList.remove('scrolled');
    }
  });
</script>
