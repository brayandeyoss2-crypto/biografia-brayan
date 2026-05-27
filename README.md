[index (2).html](https://github.com/user-attachments/files/28290034/index.2.html)
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Minha Biografia | Brayan Deyos</title>
  
  <link rel="icon" href="data:image/svg+xml,<svg xmlns=%22http://www.w3.org/2000/svg%22 viewBox=%220 0 100 100%22><text y=%22.9em%22 font-size=%2290%22>🚀</text></svg>">
  
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

  <style>
    /* Estilos Gerais / Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background: linear-gradient(135deg, #0f172a 0%, #1e1b4b 100%);
      color: #f8fafc;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 20px;
    }

    /* Cabeçalho animado */
    header {
      text-align: center;
      margin: 40px 0;
      animation: fadeInDown 0.8s ease-in-out;
    }

    header h1 {
      font-size: 2.5rem;
      background: linear-gradient(to right, #38bdf8, #a855f7);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      margin-bottom: 10px;
    }

    /* Container Principal */
    main {
      width: 100%;
      max-width: 800px;
      display: grid;
      grid-template-columns: 1fr;
      gap: 25px;
      margin-bottom: 40px;
    }

    @media (min-width: 768px) {
      main {
        grid-template-columns: 1fr 1fr;
      }
      .full-width {
        grid-column: span 2;
      }
    }

    /* Cartões (Seções) */
    section {
      background: rgba(30, 41, 59, 0.7);
      backdrop-filter: blur(10px);
      border: 1px solid rgba(255, 255, 255, 0.1);
      border-radius: 16px;
      padding: 25px;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      box-shadow: 0 4px 30px rgba(0, 0, 0, 0.2);
    }

    section:hover {
      transform: translateY(-5px);
      box-shadow: 0 10px 30px rgba(56, 189, 248, 0.15);
      border-color: rgba(56, 189, 248, 0.4);
    }

    h2 {
      font-size: 1.3rem;
      color: #38bdf8;
      margin-bottom: 15px;
      border-bottom: 2px solid rgba(56, 189, 248, 0.2);
      padding-bottom: 8px;
      display: flex;
      align-items: center;
      gap: 10px;
    }

    /* Seção Perfil */
    .perfil-container {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 20px;
      text-align: center;
    }

    @media (min-width: 500px) {
      .perfil-container {
        flex-direction: row;
        text-align: left;
      }
    }

    .foto-perfil {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid #a855f7;
      box-shadow: 0 0 15px rgba(168, 85, 247, 0.5);
    }

    .dados-texto p {
      margin-bottom: 8px;
      color: #cbd5e1;
      font-size: 0.95rem;
    }

    .dados-texto strong, .dados-texto b {
      color: #ffffff;
    }

    /* Listas Estilizadas */
    ul, ol {
      list-style: none;
    }

    li {
      background: rgba(15, 23, 42, 0.6);
      padding: 10px 15px;
      margin-bottom: 8px;
      border-radius: 8px;
      font-size: 0.95rem;
      transition: background 0.2s;
      text-transform: capitalize; /* Deixa a primeira letra maiúscula automaticamente */
    }

    li:hover {
      background: rgba(56, 189, 248, 0.1);
      padding-left: 20px;
    }

    /* Badges de Tecnologia */
    .tech-badges {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      justify-content: center;
      margin-top: 15px;
    }

    .tech-badges img {
      transition: transform 0.2s, filter 0.2s;
      border-radius: 4px;
    }

    .tech-badges img:hover {
      transform: scale(1.1);
      filter: drop-shadow(0 0 8px rgba(255,255,255,0.3));
    }

    /* Rodapé */
    footer {
      text-align: center;
      color: #64748b;
      font-size: 0.85rem;
      margin-top: auto;
      padding: 20px;
    }

    /* Animação inicial */
    @keyframes fadeInDown {
      from {
        opacity: 0;
        transform: translateY(-20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Minha Biografia 🚀</h1>
  </header>

  <main>
    <section class="full-width">
      <h2>👤 Dados Pessoais</h2>
      <div class="perfil-container">
        <img src="minhafoto.png" alt="Brayan Deyos" class="foto-perfil" onerror="this.src='https://images.unsplash.com/photo-1535713875002-d1d0cf377fde?auto=format&fit=crop&w=150&q=80'">
        <div class="dados-texto">
          <p>Meu nome é <strong>Brayan Deyos de Jesus</strong></p>
          <p>Estudo na <b>Universidade Anhanguera de Arapongas</b></p>
          <p>Alguns hobbies pessoais: <b>Jogar video game, assistir séries e filmes, dar um rolê</b></p>
        </div>
      </div>
    </section>

    <section>
      <h2>🎵 Top Músicas / Artistas</h2>
      <ul>
        <li>Nirvana</li>
        <li>Legião Urbana</li>
        <li>Guns N' Roses</li>
        <li>MC Hariel</li>
        <li>MC Tuto</li>
      </ul>
    </section>

    <section>
      <h2>🎮 Top 5 Jogos Favoritos</h2>
      <ol>
        <li>Free Fire</li>
        <li>Call of Duty (COD)</li>
        <li>Valorant</li>
        <li>Minecraft</li>
        <li>God of War</li>
      </ol>
    </section>

    <section>
      <h2>🚫 Coisas que Eu Odeio</h2>
      <ol>
        <li>Que mintam para mim</li>
        <li>Falsidade</li>
        <li>Que não me devolvam dinheiro</li>
      </ol>
    </section>

    <section>
      <h2>💻 Minhas Tecnologias</h2>
      <div class="tech-badges">
        <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
        <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
        <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
        <img src="https://img.shields.io/badge/Bitcoin-000000?style=for-the-badge&logo=bitcoin&logoColor=white" alt="Bitcoin">
      </div>
    </section>
  </main>

  <footer>
    <p>Desenvolvido com 💜 por Brayan Deyos</p>
  </footer>

</body>
</html>
