<h1>
  Welcome to my blog
</h1>

<h3>
  This will be my learning doary!
</h3>
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Parágrafo com clique</title>
  <style>
    #texto-escondido {
      display: none;
      margin-top: 10px;
      color: #444;
    }

    #paragrafo {
      cursor: pointer;
      color: blue;
    }
  </style>
</head>
<body>

  <p id="paragrafo">Clique aqui para ver mais informações</p>
  <p id="texto-escondido">Este é o texto que aparece após o clique!</p>

  <script>
    const paragrafo = document.getElementById('paragrafo');
    const texto = document.getElementById('texto-escondido');

    paragrafo.addEventListener('click', () => {
      texto.style.display = 'block'; // ou 'none' para esconder de novo
    });
  </script>

</body>
</html>

