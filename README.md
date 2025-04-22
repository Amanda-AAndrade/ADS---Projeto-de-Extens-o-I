# ADS---Projeto-de-Extens-o-I
Landing Page

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

    select, input[type="submit"] {
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
      font-size: 0.9em;
      color: #000000;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <div class="container">
    <h1>ODS - Educação de Qualidade</h1>
    <p>Quais ações você acredita que podem contribuir para uma Educação de Qualidade?</p>
          <label for="mensagem">Escreva sua Opnião:</label>
  <textarea id="mensagem" name="mensagem" rows="5" placeholder="Digite aqui sua mensagem..." required></textarea>
    <form>
          <option value="educacao">Educação de Qualidade</option>
      </select>

      <input type="submit" value="Enviar">
    </form>
  </div>

  <footer>
    © 2025 - Projeto ODS Educacional
  </footer>

</body>
</html>
