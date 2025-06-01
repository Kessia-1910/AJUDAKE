<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Site</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f4f4f4;
            padding: 50px;
        }
        h1 {
            color: #333;
        }
        .container {
            max-width: 400px;
            margin: auto;
            background: white;
            padding: 20px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        input {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
        }
        button {
            background-color: #28a745;
            color: white;
            padding: 10px;
            border: none;
            cursor: pointer;
            width: 100%;
        }
        button:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>
    <h1>Bem-vindo ao Meu Site!</h1>

    <div class="container">
        <h2>Login</h2>
        <input type="text" id="username" placeholder="Usuário">
        <input type="password" id="password" placeholder="Senha">
        <button onclick="login()">Entrar</button>
    </div>

    <div class="container">
        <h2>Pesquisar</h2>
        <input type="text" id="searchBox" placeholder="Digite para pesquisar...">
        <button onclick="search()">Pesquisar</button>
    </div>

    <script>
        function login() {
            let user = document.getElementById("username").value;
            let pass = document.getElementById("password").value;
            
            if (user === "admin" && pass === "1234") {
                alert("Login bem-sucedido!");
            } else {
                alert("Usuário ou senha inválidos.");
            }
        }

        function search() {
            let query = document.getElementById("searchBox").value;
            alert("Você pesquisou por: " + query);
        }
    </script>
</body>
</html>
