<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8">
  <title>Primeira Guerra Mundial</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f2f2f2;
      margin: 0;
      padding: 0;
    }
    header, footer {
      background-color: #1a1a1a;
      color: white;
      text-align: center;
      padding: 20px 0;
    }
    main {
      max-width: 900px;
      margin: auto;
      padding: 20px;
    }
    section {
      background-color: white;
      padding: 20px;
      margin-bottom: 20px;
      border-radius: 8px;
    }
    h2 {
      color: #333;
    }
    ul {
      padding-left: 20px;
    }
    img, iframe {
      max-width: 100%;
      border-radius: 5px;
    }
    .quiz label {
      display: block;
      margin: 10px 0;
    }
    .quiz button {
      margin-top: 10px;
      padding: 8px 12px;
      background-color: #1a1a1a;
      color: white;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }
    .quiz button:hover {
      background-color: #333;
    }
    .quiz-result {
      margin-top: 10px;
[26/05, 20:16] Chat Gpt: font-weight: bold;
    }
  </style>
</head>
<body>
  <header>
    <h1>Primeira Guerra Mundial</h1>
    <p>1914 - 1918</p>
  </header>

  <main>
    <section>
      <h2>Resumo Histórico</h2>
      <p>A Primeira Guerra Mundial foi um conflito global que ocorreu entre 1914 e 1918, envolvendo as principais potências mundiais da época. O estopim foi o assassinato do arquiduque Francisco Ferdinando da Áustria em Sarajevo, em 28 de junho de 1914. O conflito resultou em cerca de 20 milhões de mortos, entre militares e civis, e transformou profundamente o cenário político e econômico mundial. [1] </p>
    </section>

    <section>
      <h2>Causas do Conflito</h2>
      <ul>
        <li><strong>Imperialismo:</strong> Disputas por colônias e recursos na África e Ásia entre as potências europeias. [2] </li>
        <li><strong>Militarismo:</strong> Corrida armamentista e aumento dos gastos militares.</li>
        <li><strong>Alianças Militares:</strong> Formação da Tríplice Aliança (Alemanha, Áustria-Hungria, Itália) e Tríplice Entente (França, Reino Unido, Rússia).</li>
        <li><strong>Nacionalismo:</strong> Tensões étnicas e territoriais, especialmente nos Bálcãs.</li>
[26/05, 20:17] Chat Gpt: <li><strong>Estopim:</strong> Assassinato do arquiduque Francisco Ferdinando por um nacionalista sérvio. [2] </li>
      </ul>
    </section>

    <section>
      <h2>Consequências</h2>
      <ul>
        <li>Assinatura do Tratado de Versalhes em 1919, impondo severas sanções à Alemanha. [3] </li>
        <li>Queda de impérios: Austro-Húngaro, Otomano, Alemão e Russo. [4] </li>
        <li>Redesenho do mapa europeu com o surgimento de novos países.</li>
        <li>Ascensão dos Estados Unidos como potência mundial.</li>
        <li>Criação da Liga das Nações para promover a paz mundial.</li>
        <li>Precedente para a Segunda Guerra Mundial devido às tensões não resolvidas. [4] </li>
      </ul>
    </section>

    <section>
      <h2>Linha do Tempo</h2>
      <ul>
        <li><strong>28 de junho de 1914:</strong> Assassinato do arquiduque Francisco Ferdinando.</li>
        <li><strong>28 de julho de 1914:</strong> Início oficial da guerra com a declaração da Áustria-Hungria à Sérvia.</li>
        <li><strong>1915:</strong> Itália entra na guerra ao lado da Tríplice Entente.</li>
        <li><strong>1917:</strong> Entrada dos EUA na guerra; Revolução Russa leva à saída da Rússia do conflito.</li>
[26/05, 20:17] Chat Gpt: <li><strong>11 de novembro de 1918:</strong> Assinatura do armistício e fim da guerra.</li>
        <li><strong>1919:</strong> Assinatura do Tratado de Versalhes. [3] </li>
      </ul>
    </section>

    <section>
      <h2>Vídeo Explicativo</h2>
      <iframe width="560" height="315" src="https://www.youtube.com/embed/6P89N-WrnLk" title="Primeira Guerra Mundial: Resumo | Quer Que Desenhe?" frameborder="0" allowfullscreen></iframe>
    </section>

    <section>
      <h2>Quiz Rápido</h2>
      <form class="quiz" id="quizForm">
        <p><strong>Qual país saiu da guerra após uma revolução interna?</strong></p>
        <label><input type="radio" name="q1" value="França"> França</label>
        <label><input type="radio" name="q1" value="Alemanha"> Alemanha</label>
        <label><input type="radio" name="q1" value="Rússia"> Rússia</label>
        <label><input type="radio" name="q1" value="Reino Unido"> Reino Unido</label>
        <button type="button" onclick="checkAnswer()">Verificar Resposta</button>
        <div class="quiz-result" id="quizResult"></div>
      </form>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 - Site Educativo sobre a Primeira Guerra Mundial</p>
  </footer>

  <script>
    function checkAnswer() {
