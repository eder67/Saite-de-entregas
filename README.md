# Saite-de-entregas<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Entrega Rápida</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
    }

    header {
      background-color: #007bff;
      color: white;
      padding: 20px;
      text-align: center;
    }

    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      padding: 40px 20px;
    }

    .sobre, .servicos, .contato, .pedido {
      background-color: #f4f4f4;
      margin-bottom: 20px;
    }

    form {
      max-width: 500px;
      margin: auto;
    }

    input, textarea {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      box-sizing: border-box;
    }

    button {
      background-color: #007bff;
      color: white;
      padding: 10px 20px;
      border: none;
      cursor: pointer;
    }

    iframe {
      width: 100%;
      height: 300px;
      border: 0;
    }

    footer {
      background-color: #222;
      color: white;
      text-align: center;
      padding: 15px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Entrega Rápida</h1>
    <nav>
      <a href="#sobre">Sobre</a>
      <a href="#servicos">Serviços</a>
      <a href="#pedido">Pedido</a>
      <a href="#contato">Contato</a>
    </nav>
  </header>

  <section id="sobre" class="sobre">
    <h2>Sobre Nós</h2>
    <p>Somos uma empresa especializada em entregas rápidas e seguras em toda a cidade. Atuamos com motoboys e veículos para atender diversos tipos de demanda.</p>
  </section>

  <section id="servicos" class="servicos">
    <h2>Nossos Serviços</h2>
    <ul>
      <li>Entregas expressas</li>
      <li>Coleta e envio de documentos</li>
      <li>Serviços para empresas e comércios locais</li>
    </ul>
  </section>

  <section id="pedido" class="pedido">
    <h2>Solicitar Entrega</h2>
    <form action="#" method="post">
      <input type="text" name="nome" placeholder="Seu nome" required>
      <input type="text" name="endereco" placeholder="Endereço de coleta" required>
      <input type="text" name="destino" placeholder="Endereço de entrega" required>
      <textarea name="detalhes" rows="4" placeholder="Informações adicionais"></textarea>
      <button type="submit">Enviar Pedido</button>
    </form>
  </section>

  <section id="contato" class="contato">
    <h2>Fale Conosco</h2>
    <p>WhatsApp: (54) 996637814 ou 54999441816 </p>
    <p>Email: contato@entregarapida.com</p>
    <h3>Nosso Local</h3>
    <iframe
      src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3656.8552410592276!2d-46.65657418502558!3d-23.576006584669213!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x94ce59c7555c3bfb%3A0xc5402f94fa58df2e!2sAv.%20Paulista%2C%20S%C3%A3o%20Paulo!5e0!3m2!1spt-BR!2sbr!4v1714437832541"
      allowfullscreen=""
      loading="lazy">
    </iframe>
  </section>

  <footer>
    <p>&copy; 2025 Entrega Rápida. Todos os direitos reservados.</p>
  </footer>

</body>
</html>
