<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Educação de Qualidade - ODS</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to right, #e0f7fa, #ffffff);
      color: #000000;
    }

    .container {
      max-width: 600px;
      margin: 80px auto;
      background-color: #ffffff;
      border-radius: 10px;
      padding: 30px;
      box-shadow: 0 0 20px rgb(0, 0, 0);
    }

    h1 {
      text-align: center;
      color: #000000;
    }

    p {
      text-align: center;
      font-size: 1.1em;
      margin-bottom: 30px;
    }

    label {
      display: block;
      margin-top: 15px;
      font-weight: 600;
    }

    select, textarea, input[type="submit"] {
      width: 100%;
      padding: 12px;
      margin-top: 10px;
      border: 2px solid #b2dfdb;
      border-radius: 5px;
      font-size: 16px;
      background-color: #e0f2f1;
      color: #000000;
    }

    input[type="submit"] {
      background-color: #000879;
      color: white;
      font-weight: bold;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    input[type="submit"]:hover {
      background-color: #000000;
    }

    footer {
      text-align: center;
      font-size: 1em;
      color: #043194;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <div class="container">
    <h1>ODS - >Objetivo de Desenvolvimento Sustentável</h1>
    <p>Quais ações você acredita que podem contribuir para uma ação de Educação de Qualidade ?</p>

    <form id="formulario">
      <label for="mensagem">Escreva sua Opinião:</label>
      <textarea id="mensagem" name="mensagem" rows="5" placeholder="Digite aqui sua mensagem..." required></textarea>

      <label for="tema">Escolha o Tema:</label>
      <select id="tema" name="tema" required>
        <option value="">Selecione uma opção</option>
        <option value="educacao">Educação de Qualidade</option>
      </select>

      <input type="submit" value="Enviar">
    </form>
      </div>

  <footer>
    © 2025 - Projeto ODS Educacional
  </footer>

  <script>
    document.getElementById('formulario').addEventListener('submit', function(event) {
      event.preventDefault(); // Evita o recarregamento da página
      const mensagem = document.getElementById('mensagem').value;
      const tema = document.getElementById('tema').value;

      if (mensagem && tema) {
        alert(`Obrigado pela sua contribuição!\nTema: ${tema}\nMensagem: ${mensagem}`);
        // Aqui você pode enviar para um backend ou API futuramente
        this.reset(); // Limpa o formulário
      } else {
        alert('Por favor, preencha todos os campos.');
      }
    });
  </script>

</body>
</html>
