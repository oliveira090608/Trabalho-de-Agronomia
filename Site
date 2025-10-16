<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>OmniBot - Inteligência Artificial e o Agronegócio 4.0</title>
<style>
  body {
    font-family: 'Segoe UI', sans-serif;
    margin: 0;
    background: #000;
    color: #fff;
    overflow-x: hidden;
  }

  header {
    text-align: center;
    padding: 3rem 2rem;
    display: none;
  }
  header h1 {
    margin: 0;
    font-size: 3rem;
    color: #00e676;
    text-shadow: 0 0 10px #00e676;
  }
  header p {
    font-size: 1.3rem;
    margin-top: 0.5rem;
    color: #90caf9;
    text-shadow: 0 0 6px #90caf9;
  }

  .hero {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    flex-direction: column;
  }

  @keyframes roboPulse {
    0%,100% { transform: translateY(0); filter: drop-shadow(0 0 5px #00e676) drop-shadow(0 0 10px #00e676); }
    50% { transform: translateY(-15px); filter: drop-shadow(0 0 20px #00e676) drop-shadow(0 0 40px #00e676); }
  }
  .hero img {
    width: 220px;
    animation: roboPulse 3s infinite ease-in-out;
  }
  .hero p {
    color: #90caf9;
    text-shadow: 0 0 6px #90caf9;
  }

  section {
    max-width: 1100px;
    margin: auto;
    padding: 2rem;
    display: none;
  }

  .card {
    background: #111;
    border-radius: 15px;
    padding: 2rem;
    margin-bottom: 2rem;
    transition: transform 0.2s;
    animation: borderPulse 2s infinite;
  }
  .card:hover {
    transform: scale(1.02);
  }
  .card h2 {
    color: #00e676;
    text-shadow: 0 0 8px #00e676;
  }

  .grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 1.5rem;
  }

  @keyframes neonPulse {
    0%,100% { text-shadow: 0 0 5px currentColor, 0 0 10px currentColor; }
    50% { text-shadow: 0 0 15px currentColor, 0 0 30px currentColor; }
  }
  .grid h3 {
    animation: neonPulse 2s infinite;
  }

  @keyframes borderPulse {
    0%,100% { box-shadow: 0 0 10px currentColor; }
    50% { box-shadow: 0 0 25px currentColor; }
  }

  details {
    margin: 1rem 0;
    background: #222;
    padding: 1rem;
    border-radius: 8px;
    border: 1px solid #00e676;
    box-shadow: 0 0 10px #00e676;
  }
  details summary {
    cursor: pointer;
    color: #90caf9;
    text-shadow: 0 0 6px #90caf9;
  }

  footer {
    background: #111;
    color: #ccc;
    text-align: center;
    padding: 1rem;
    margin-top: 2rem;
    font-size: 0.9rem;
  }

  .banner {
    display: none;
    text-align: center;
    margin: 2rem 0;
    opacity: 0;
    transition: opacity 2s ease-in-out;
  }
  .banner img {
    width: 80%;
    max-width: 600px;
    border-radius: 12px;
    box-shadow: 0 0 30px #00e676;
  }
  .banner.show {
    display: block;
    opacity: 1;
  }
  
  /* Estilo para o Slogan (novo) */
  .slogan-card {
      background: #0d47a1; /* Azul Escuro */
      color: #90caf9;
      text-align: center;
      padding: 3rem 2rem;
      border: 3px solid #90caf9;
      box-shadow: 0 0 20px #90caf9;
  }
  .slogan-card p {
      margin: 0;
      font-size: 2.2rem;
      font-weight: bold;
      letter-spacing: 2px;
      text-shadow: 0 0 10px #90caf9;
  }


  #music-btn {
    position: fixed;
    bottom: 20px;
    right: 20px;
    background: #00e676;
    color: #000;
    border: none;
    border-radius: 50%;
    width: 50px;
    height: 50px;
    font-size: 1.2rem;
    cursor: pointer;
    box-shadow: 0 0 15px #00e676, 0 0 30px #00e676;
    transition: transform 0.2s, background 0.2s;
  }
  #music-btn:hover {
    transform: scale(1.1);
    background: #00c853;
  }

  /* Responsividade */
  @media (max-width: 768px) {
    .grid { grid-template-columns: 1fr; gap: 1rem; }
    .hero img { width: 150px; }
    header h1 { font-size: 2rem; }
    header p { font-size: 1rem; }
    .card { padding: 1rem; }
    .banner img { width: 95%; }
    .slogan-card p { font-size: 1.5rem; }
  }

  @media (max-width: 480px) {
    #music-btn { width: 40px; height: 40px; font-size: 1rem; }
    .hero img { width: 120px; }
    .slogan-card p { font-size: 1.2rem; }
  }
</style>
</head>
<body>

<audio id="bg-music" loop>
  <source src="https://cdn.pixabay.com/download/audio/2023/03/02/audio_b0bde45ef4.mp3?filename=ambient-futuristic-140795.mp3" type="audio/mpeg">
  Seu navegador não suporta áudio.
</audio>
<button id="music-btn">▶️</button>

<div class="hero" id="hero">
  <img src="https://cdn-icons-png.flaticon.com/512/4712/4712100.png" alt="Robo OmniBot">
  <p><em>Carregando inteligência...</em></p>
</div>

<header id="header">
  <h1>OmniBot</h1>
  <p>Inteligência Aérea e Terrestre para o Agronegócio 4.0</p>
</header>

<section id="conteudo">
  <div class="card">
    <h2>O que é o OmniBot?</h2>
    <p>O <strong>OmniBot</strong> é o futuro da agricultura de precisão. Um sistema dual que combina a vigilância aérea de um drone com a autonomia terrestre de um robô, especializado em monitoramento de lavouras. Equipado com Inteligência Artificial avançada, ele consolida o trabalho de múltiplos sensores em um só dispositivo, realizando diagnósticos completos sobre pragas, umidade do solo e necessidades nutricionais das plantas, otimizando o manejo e reduzindo custos na plantação.</p>
  </div>

  <div class="card">
    <h2>Funcionalidades Chave</h2>
    <div class="grid">
      <div class="card" style="border: 2px solid #00e676; color:#00e676;">
        <h3>🌱 Monitoramento Aéreo & Terrestre</h3>
        <p>Realiza o sobrevoo inteligente para análise de grandes áreas, e ao pousar, assume o modo robô terrestre para análises de solo de alta precisão. Diagnóstico de pragas e doenças em tempo real.</p>
      </div>
      <div class="card" style="border: 2px solid #ff3d00; color:#ff3d00;">
        <h3>🔬 Análise Multissensorial</h3>
        <p>Graças à sua capacidade de consolidar dados, elimina a necessidade de múltiplos sensores físicos na lavoura, agilizando a coleta de informações cruciais para a tomada de decisões.</p>
      </div>
      <div class="card" style="border: 2px solid #2962ff; color:#2962ff;">
        <h3>🧠 IA de Alto Nível</h3>
        <p>Integração com uma Inteligência Artificial Renomada, que não apenas coleta dados, mas também sugere as melhores intervenções de manejo, aumentando a produtividade e a sustentabilidade.</p>
      </div>
      <div class="card" style="border: 2px solid #ffea00; color:#ffea00;">
        <h3>⚡ Otimização e Produtividade</h3>
        <p>Permite a rápida identificação de estresses hídricos e deficiências nutricionais, garantindo que o agrônomo aja de forma pontual e eficiente, economizando recursos e tempo.</p>
      </div>
      <div class="card" style="border: 2px solid #d500f9; color:#d500f9;">
        <h3>🌐 Versatilidade e Autonomia</h3>
        <p>Desenvolvido para ser o braço direito do profissional de Agronegócio, o OmniBot oferece dados confiáveis, alta autonomia e um design conversível que garante o monitoramento de cada metro quadrado da plantação.</p>
      </div>
    </div>
  </div>

  <div class="card faq">
    <h2>Perguntas Frequentes</h2>
    <details>
      <summary>O OmniBot serve só para agrônomos?</summary>
      <p>Sim, ele foi projetado e especializado para o Agronegócio, oferecendo funcionalidades específicas para o manejo de lavouras e análise de solo.</p>
    </details>
    <details>
      <summary>Precisa de internet para funcionar?</summary>
      <p>A coleta de dados primários pode ser feita offline, mas a análise avançada da IA e o envio de relatórios dependem da conexão para máxima eficiência.</p>
    </details>
    <details>
      <summary>O OmniBot substitui profissionais?</summary>
      <p>Não! Ele é uma ferramenta de suporte essencial para o Agrônomo, otimizando o tempo, cobrindo grandes áreas com rapidez e fornecendo dados de alta precisão que o olho humano não consegue captar.</p>
    </details>
  </div>
  
  <div class="card slogan-card">
    <p>Omnibot — onde o campo e a tecnologia se encontram.</p> 
  </div>

  <div class="banner" id="banner">
    <img src="omnibot_banner.png" alt="Omnibot - Robô e Drone de Monitoramento">
  </div>
</section>

<footer>
  &copy; 2025 Semana Técnica do Agronegócio
</footer>

<script>
  setTimeout(() => {
    document.getElementById('hero').style.display = 'none';
    document.getElementById('header').style.display = 'block';
    document.getElementById('conteudo').style.display = 'block';
  }, 3000);

  setTimeout(() => {
    document.getElementById('banner').classList.add('show'); 
  }, 120000);

  const music = document.getElementById("bg-music");
  const musicBtn = document.getElementById("music-btn");
  musicBtn.addEventListener("click", () => {
    if (music.paused) {
      music.play();
      music.volume = 0.2;
      musicBtn.textContent = "🔊";
    } else {
      music.pause();
      musicBtn.textContent = "▶️";
    }
  });
</script>

</body>
</html>
