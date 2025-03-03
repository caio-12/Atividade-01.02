<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Página de Contato</title>
</head>
<body>
    <h1>Contato</h1>
    <form action="#" method="post">
        <label for="nome">Nome:</label><br>
        <input type="text" id="nome" name="nome" placeholder="Exemplo: João da Silva" required><br><br>
        
        <label for="email">E-mail:</label><br>
        <input type="email" id="email" name="email" placeholder="Exemplo: joao@email.com" required><br><br>
        
        <label for="mensagem">Mensagem:</label><br>
        <textarea id="mensagem" name="mensagem" rows="5" cols="33" placeholder="Exemplo: Escreva sua mensagem aqui..." required></textarea><br><br>
        
        <button type="submit">Enviar</button>
    </form>
</body>
</html>
