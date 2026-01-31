<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Meu Primeiro Site</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Olá, Mundo! 🚀</h1>
    <p>Este é o meu primeiro site hospedado no GitHub.</p>
    <script src="script.js"></script>
 const botao = document.querySelector('#meuBotao');

botao.addEventListener('click', () => {
    // Isso faz o navegador "navegar" para o novo endereço
    window.location.href = "pagina2.html";
})
</body>
</html>
