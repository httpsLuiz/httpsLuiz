<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Luiz Fernando Gonzaga Martins - Portfólio Sinistro</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Creepster&family=Roboto&display=swap');

  /* Reset básico */
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  body {
    background: #0a0a0a;
    color: #eee;
    font-family: 'Roboto', sans-serif;
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 2rem;
  }

  header {
    font-family: 'Creepster', cursive;
    font-size: 3rem;
    color: #d72631;
    text-shadow: 0 0 10px #d72631;
    margin-bottom: 1rem;
    text-align: center;
  }

  blockquote {
    font-style: italic;
    color: #888;
    margin-bottom: 3rem;
    text-align: center;
    max-width: 600px;
  }

  section {
    max-width: 700px;
    width: 100%;
  }

  h2 {
    color: #d72631;
    border-bottom: 2px solid #d72631;
    padding-bottom: 0.3rem;
    margin-bottom: 1rem;
    font-family: 'Creepster', cursive;
  }

  .project {
    background: #111;
    border: 1px solid #d72631;
    border-radius: 8px;
    padding: 1rem 1.5rem;
    margin-bottom: 1.5rem;
    transition: box-shadow 0.3s ease;
  }

  .project:hover {
    box-shadow: 0 0 15px #d72631;
  }

  .project a {
    color: #f24e4e;
    font-weight: bold;
    text-decoration: none;
  }

  .project a:hover {
    text-decoration: underline;
  }

  ul.tech-list {
    list-style-type: none;
    display: flex;
    gap: 1rem;
    padding-left: 0;
    margin-bottom: 3rem;
    justify-content: center;
  }

  ul.tech-list li {
    background: #d72631;
    padding: 0.4rem 1rem;
    border-radius: 20px;
    font-weight: bold;
    color: #111;
    font-family: 'Roboto', sans-serif;
  }

  footer {
    margin-top: auto;
    padding-top: 2rem;
    text-align: center;
    font-size: 0.9rem;
    color: #555;
  }

  footer a {
    color: #d72631;
    text-decoration: none;
  }

  footer a:hover {
    text-decoration: underline;
  }

  @media (max-width: 480px) {
    body {
      padding: 1rem;
    }

    header {
      font-size: 2.2rem;
    }

    section {
      max-width: 100%;
    }
  }
</style>
</head>
<body>

<header>Luiz Fernando Gonzaga Martins</header>
<blockquote>“No silêncio das sombras, o código ganha vida...”</blockquote>

<section>
  <h2>⚰️ Meus Projetos Sinistros</h2>

  <div class="project">
    <a href="https://seulink.com/websitedeterror" target="_blank" rel="noopener noreferrer">🕸️ WebSite De Terror (Sombroso)</a>
    <p>Um site macabro e sombrio, perfeito para quem gosta do lado obscuro da web.</p>
  </div>

  <div class="project">
    <a href="https://seulink.com/jogodeterror" target="_blank" rel="noopener noreferrer">🔪 Jogo de Terror (Crônicas de Luiz)</a>
    <p>Mergulhe em uma aventura arrepiante com puzzles, mistérios e sustos na pele.</p>
  </div>
</section>

<section>
  <h2>🧙‍♂️ Tecnologias que uso</h2>
  <ul class="tech-list">
    <li>HTML</li>
    <li>CSS</li>
    <li>Python</li>
  </ul>
</section>

<section>
  <h2>📬 Contato</h2>
  <p>Email: <a href="mailto:luizfernando@email.com">luizfernando@email.com</a></p>
  <p>GitHub: <a href="https://github.com/seuusuario" target="_blank" rel="noopener noreferrer">github.com/seuusuario</a></p>
</section>

<footer>
  “O verdadeiro terror está em linhas de código que só você ousa desvendar.”
</footer>

</body>
</html>
