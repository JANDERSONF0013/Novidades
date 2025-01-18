<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Site</title>
    <link rel="stylesheet" href="styles2.css">
</head>
<body>
    <div class="container">
        <button id="main-button">SÃO NOVAS?</button>
        <div class="options">
            <button id="sim">SIM</button>
            <button id="nao">NÃO</button>
        </div>
        <p id="mensagem"></p>
        <div id="links"></div>
       </div>
       </footer>
             <img src="cap1.PNG" alt="" ID="CAP1.PNG"
       </footer>

    <script>
        document.getElementById('sim').addEventListener('click', function() {
            document.getElementById('mensagem').textContent = "SE SÃO NOVAS PODE PERGUNTAR";
            document.getElementById('links').innerHTML = `
                <a href="https://wa.me/553121187010" target="_blank">  Setor Cadastro </a><br>

                <a href="https://wa.me/553121181011" target="_blank">  Setor Estoque </a><br>

                <a href="https://wa.me/553188698068" target="_blank">  Deivison (cortin) </a><br>

                <a href="https://wa.me/553191563116" target="_blank">  Emerson (Clodovil) </a><br>

                <a href="https://wa.me/553175604846" target="_blank">  Wanglen (Tio Pit)  </a><br>

                <a href="https://wa.me/553188323218" target="_blank">  Marcelo ( Marcelão) </a><br>

                <a href="https://wa.me/553175374293" target="_blank">  Gênio (Fafá de Belém)   </a>
            `;
        });

        document.getElementById('nao').addEventListener('click', function() {
            document.getElementById('mensagem').textContent = "CADÊ AS ANOTAÇÕES BARALHO";
            document.getElementById('links').innerHTML = "";
        });
    </script>
</body>
</html>
