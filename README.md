<!DOCTYPE html>
<html>
<head>
    <title>Contador de Cliques</title>
    <script type="text/javascript">
        var clicks = 0;
        function countClicks() {
            clicks += 1;
            document.getElementById("clicks").innerHTML = clicks;
        }
    </script>
</head>
<body>
    <h1>Contador de Cliques</h1>
    <p>Clique no botão abaixo para contar os cliques:</p>
    <button type="button" onclick="countClicks()">Clique Aqui!</button>
    <p>Quantidade de Cliques: <span id="clicks">0</span></p>
</body>
</html>
