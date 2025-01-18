<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Site</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <button id="main-button">SÃO NOVAS?</button>
        <div class="options">
            <button id="sim">SIM</button>
            <button id="nao">NÃO</button>
        </div>
        <p id="mensagem"></p>
    </div>

    <script>
        document.getElementById('sim').addEventListener('click', function() {
            document.getElementById('mensagem').textContent = "PODE PERGUNTAR, TÁ ANOTANDO?";
        });

        document.getElementById('nao').addEventListener('click', function() {
            document.getElementById('mensagem').textContent = "CADÊ AS ANOTAÇÕES BARALHO";
        });
    </script>
</body>
</html>
