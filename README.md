<!DOCTYPE html>
<html lang="pt-br"
<head>
<meta charset="UTF-8">
<title>Meu Primeiro Site</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<h1>Olá, Mundo! 🚀</h1>
<p>Este é o meu primeiro site hospedado no GitHub.</p>
<button id="botaoClique">Clique aqui!</button>
<p id="sucesso"></p>
<script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    text-align: center;
    background-color: #f0f2f5;
    padding-top: 50px;
}

h1 { color: #2b3137; }

button {
    padding: 10px 20px;
    font-size: 16px;
    cursor: pointer;
    background-color: #2ea44f;
    color: white;
    border: none;
    border-radius: 5px;
}
const botao = document.getElementById('botaoClique');
const texto = document.getElementById('mensagem');

botao.addEventListener('click', () => {
    texto.innerText = "O JavaScript está funcionando! Você clicou no botão.";
    botao.style.backgroundColor = "#ff4444";
});
