<img src="logo.png"
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Yama Boat - Elétrica Naval em Bertioga-SP</title>
  <meta name="description" content="Yama Boat é especialista em elétrica e hidráulica naval em Bertioga-SP. Serviços de qualidade para sua embarcação." />
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #fdfdfd;
      color: #333;
    }
    header {
      background: #003f5c;
      color: white;
      text-align: center;
      padding: 20px;
    }
    header img {
      max-width: 150px;
      margin-bottom: 10px;
    }
    nav {
      background: #ffa600;
      text-align: center;
      padding: 10px;
    }
    nav a {
      color: white;
      margin: 0 15px;
      font-weight: bold;
      text-decoration: none;
    }
    section {
      max-width: 900px;
      margin: auto;
      padding: 30px 20px;
    }
    h2 {
      color: #003f5c;
    }
    ul {
      list-style: none;
      padding: 0;
    }
    ul li::before {
      content: "✔";
      margin-right: 8px;
      color: #ffa600;
    }
    form {
      display: flex;
      flex-direction: column;
      gap: 10px;
      margin-top: 20px;
    }
    input, textarea {
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 4px;
      font-size: 1rem;
    }
    button {
      background-color: #003f5c;
      color: white;
      padding: 10px;
      border: none;
      border-radius: 4px;
      font-size: 1rem;
      cursor: pointer;
    }
    button:hover {
      background-color: #002c42;
    }
    .whatsapp-button {
      display: inline-block;
      background-color: #25D366;
      color: white;
      padding: 10px 20px;
      text-decoration: none;
      border-radius: 4px;
      margin-top: 10px;
      font-weight: bold;
    }
    .whatsapp-button:hover {
      background-color: #1ebe57;
    }
    footer {
      background: #003f5c;
      color: white;
      text-align: center;
      padding: 15px;
    }
  </style>
</head>
<body>
  <header>
    <img src="logo.png" alt="Logotipo Yama Boat" />
    <h1>Yama Boat</h1>
    <p>Potência e precisão em elétrica e hidráulica naval.</p>
  </header>

  <nav>
    <a href="#quem-somos">Quem Somos</a>
    <a href="#servicos">Serviços</a>
    <a href="#contato">Contato</a>
  </nav>

  <section id="quem-somos">
    <h2>Quem Somos</h2>
    <p>A Yama Boat é especializada em elétrica naval em Bertioga-SP. Oferecemos manutenção, instalação e reparos para embarcações com qualidade e confiança.</p>
  </section>

  <section id="servicos">
    <h2>Serviços</h2>
    <ul>
      <li>Instalação de sistemas elétricos embarcados</li>
      <li>Reparo de falhas elétricas</li>
      <li>Instalação de painéis solares e baterias</li>
      <li>Projetos personalizados</li>
      <li>Consultoria técnica</li>
    </ul>
  </section>

  <section id="contato">
    <h2>Contato</h2>
    <p>Entre em contato para orçamentos ou dúvidas:</p>
    <ul>
      <li><strong>Telefone:</strong> (13) 99167-7893</li>
      <li><strong>WhatsApp:</strong> (13) 99207-8676</li>
      <li><strong>Email:</strong> guilhermefoxdias@gmail.com</li>
      <li><strong>Endereço:</strong> Rua Exemplo, 123 – Bertioga, SP</li>
    </ul>
    <a class="whatsapp-button" href="https://wa.me/5513992078676" target="_blank">Fale pelo WhatsApp</a>

    <form action="mailto:guilhermefoxdias@gmail.com" method="POST" enctype="text/plain">
      <label for="nome">Nome:</label>
      <input id="nome" name="nome" type="text" required placeholder="Seu nome" />

      <label for="email">Email:</label>
      <input id="email" name="email" type="email" required placeholder="Seu email" />

      <label for="mensagem">Mensagem:</label>
      <textarea id="mensagem" name="mensagem" rows="4" required placeholder="Digite sua mensagem"></textarea>

      <button type="submit">Enviar</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Yama Boat. Todos os direitos reservados.</p>
  </footer>
</body>
</html>
