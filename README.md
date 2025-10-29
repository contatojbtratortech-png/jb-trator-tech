<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>JB Trator Tech — Peças e Soluções para Tratores</title>
  <meta name="description" content="Peças novas, usadas, originais e paralelas para tratores de diversas marcas. Qualidade, garantia e entrega rápida para todo o Brasil.">
  <style>
    :root {
      --verde:#2d6a4f;
      --amarelo:#ffca3a;
      --bg:#f5f6fa;
      --card:#ffffff;
      --muted:#5c677d;
      --radius:14px;
      font-family: "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
    }
    *{box-sizing:border-box}
    body {
      margin: 0;
      background: linear-gradient(180deg, var(--bg), #eef2fb);
      color: #1a1a1a;
      line-height: 1.6;
    }
    header {
      background: var(--verde);
      color: white;
      padding: 20px;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    }
    header img {
      height: 60px;
    }
    header h1 {
      font-size: 1.6rem;
      margin: 0;
    }
    .container {
      max-width: 1100px;
      margin: 40px auto;
      padding: 0 20px;
    }
    section {
      background: var(--card);
      margin-bottom: 30px;
      padding: 30px;
      border-radius: var(--radius);
      box-shadow: 0 4px 20px rgba(0,0,0,0.06);
    }
    h2 {
      color: var(--verde);
      margin-top: 0;
    }
    ul {
      list-style: none;
      padding: 0;
    }
    ul li {
      margin-bottom: 10px;
    }
    .diferenciais li::before {
      content: ⚙️ ";
    }
    .catalogo {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 15px;
    }
    .item {
      background: #fbfdff;
      padding: 15px;
      border-radius: 10px;
      border: 1px solid #e1e6ec;
    }
    footer {
      background: var(--verde);
      color: white;
      text-align: center;
      padding: 15px;
      font-size: 0.9rem;
    }
    a.btn {
      display: inline-block;
      margin-top: 10px;
      background: var(--amarelo);
      color: #1a1a1a;
      text-decoration: none;
      padding: 10px 16px;
      border-radius: 10px;
      font-weight: 600;
      transition: 0.2s;
    }
    a.btn:hover {
      background: #ffd54f;
    }
    @media (max-width:600px){
      header{flex-direction:column;text-align:center;}
    }
  </style>
</head>
<body>

  <header>
    <img src="logo.png" alt="Logo JB Trator Tech" />
    <h1>JB Trator Tech — Peças e Soluções para Tratores</h1>
  </header>

  <div class="container">

    <section id="inicio">
      <p>
        Fornecemos peças novas, usadas, originais e paralelas para tratores de diversas marcas.<br>
        <strong>Qualidade, garantia e entrega rápida para todo o Brasil.</strong>
      </p>
    </section>

    <section id="diferenciais">
      <h2>Nossos Diferenciais</h2>
      <ul class="diferenciais">
        <li>⚙️ Peças originais e paralelas — opções para todos os orçamentos</li>
        <li>🚛 Entrega rápida — enviamos para todo o Brasil</li>
        <li>👨‍🔧 Atendimento especializado — suporte técnico de quem entende do assunto</li>
        <li>💳 Pagamento facilitado — PIX, cartão ou transferência</li>
      </ul>
    </section>

    <section id="quem-somos">
      <h2>Quem Somos</h2>
      <p>
        A <strong>JB Trator Tech</strong> é uma empresa especializada no fornecimento de peças para tratores e máquinas agrícolas.
        Nosso objetivo é garantir que o produtor rural e as oficinas agrícolas encontrem peças de qualidade com
        preço justo e entrega ágil.
      </p>
      <p>
        Trabalhamos com marcas reconhecidas no mercado e oferecemos atendimento personalizado
        para ajudar você a encontrar a peça certa.
      </p>
    </section>

    <section id="catalogo">
      <h2>Catálogo de Peças</h2>
      <div class="catalogo">
        <div class="item">
          <h3>Motor e Transmissão</h3>
          <p>Jogo de juntas, bombas de óleo, eixos, engrenagens e mais.</p>
          <a class="btn" href="https://wa.me/5511985124850?text=Olá!%20Quero%20saber%20sobre%20peças%20de%20motor%20e%20transmissão.">Falar no WhatsApp</a>
        </div>
        <div class="item">
          <h3>Elétrica e Sistema de Partida</h3>
          <p>Alternadores, motores de partida, relés e baterias.</p>
          <a class="btn" href="https://wa.me/5511985124850?text=Olá!%20Tenho%20interesse%20em%20peças%20elétricas.">Falar no WhatsApp</a>
        </div>
        <div class="item">
          <h3>Cabine e Estrutura</h3>
          <p>Vidros, portas, retrovisores e assentos.</p>
          <a class="btn" href="https://wa.me/5511985124850?text=Olá!%20Quero%20informações%20sobre%20peças%20de%20cabine.">Falar no WhatsApp</a>
        </div>
      </div>
    </section>

    <section id="contato">
      <h2>Entre em contato</h2>
      <p>📲 <strong>WhatsApp:</strong> (11) 98512-4850</p>
      <p>📧 <strong>E-mail:</strong> <a href="mailto:contatojbtratortech@gmail.com">contatojbtratortech@gmail.com</a></p>
      <p>📞 <strong>Telefone:</strong> (11) 98512-4850</p>
      <a class="btn" href="https://wa.me/5511985124850">💬 Falar no WhatsApp</a>
    </section>

  </div>

  <footer>
    © <span id="year"></span> JB Trator Tech — Todos os direitos reservados.
  </footer>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>

</body>
</html>
