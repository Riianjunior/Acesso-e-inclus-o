# Acesso-e-inclus-o

<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Projeto de acessibilidade digital para uma experiência mais inclusiva.">
  <title>Acessibilidade Digital</title>
  <link rel="stylesheet" href="style.css">
  <script src="script.js" defer></script>
</head>
<body>
  <a class="skip-link" href="#conteudo">Pular para o conteúdo</a>

  <header>
    <h1>Acessibilidade Digital</h1>
    <p>Tecnologia mais simples, acessível e inclusiva.</p>
  </header>

  <main id="conteudo">
    <section class="painel" aria-labelledby="titulo-acessibilidade">
      <h2 id="titulo-acessibilidade">Personalize sua experiência</h2>
      <p>Utilize as opções abaixo para facilitar a leitura.</p>

      <div class="controles">
        <button id="contraste" type="button"
          aria-pressed="false">Ativar alto contraste</button>
        <button id="aumentar" type="button">Aumentar fonte (+)</button>
        <button id="diminuir" type="button">Diminuir fonte (-)</button>
        <button id="restaurar" type="button">Restaurar padrão</button>
      </div>

      <p id="mensagem" role="status" aria-live="polite">
        Configurações padrão ativadas.
      </p>
    </section>

    <section class="conteudo" aria-labelledby="titulo-conteudo">
      <h2 id="titulo-conteudo">Inclusão começa com o acesso</h2>
      <p>
        Este projeto demonstra como recursos simples podem melhorar
        a experiência digital de pessoas com baixa visão, idosos
        e usuários que precisam de uma interface mais legível.
      </p>
      <p>
        O alto contraste e o ajuste do tamanho da fonte ajudam
        cada pessoa a adaptar a leitura às suas necessidades.
      </p>
    </section>
  </main>

  <footer>
    <p>Projeto acadêmico demonstrativo de acessibilidade digital.</p>
    <p>ODS 10 — Redução das Desigualdades.</p>
  </footer>
</body>
</html>
