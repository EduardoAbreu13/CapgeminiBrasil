<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LK Bolsas e Acessórios</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="path/to/logo.png" alt="LK Bolsas e Acessórios">
        </div>
        <nav>
            <ul>
                <li><a href="#inicio">Início</a></li>
                <li><a href="#produtos">Produtos</a></li>
                <li><a href="#sobre">Sobre Nós</a></li>
                <li><a href="#contato">Contato</a></li>
                <li><a href="#carrinho">Carrinho</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="inicio">
            <h1>Bem-vindo à LK Bolsas e Acessórios</h1>
            <p>Encontre os melhores produtos aqui!</p>
        </section>
        <section id="produtos">
            <h2>Produtos</h2>
            <div class="produtos-lista">
                <!-- Lista de produtos -->
            </div>
        </section>
        <section id="sobre">
            <h2>Sobre Nós</h2>
            <p>Informações sobre a loja.</p>
        </section>
        <section id="contato">
            <h2>Contato</h2>
            <form>
                <label for="nome">Nome:</label>
                <input type="text" id="nome" name="nome" required>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                <label for="mensagem">Mensagem:</label>
                <textarea id="mensagem" name="mensagem" required></textarea>
                <button type="submit">Enviar</button>
            </form>
        </section>
        <section id="carrinho">
            <h2>Carrinho</h2>
            <div class="carrinho-lista">
                <!-- Lista de itens no carrinho -->
            </div>
            <button type="button">Finalizar Compra</button>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 LK Bolsas e Acessórios. Todos os direitos reservados.</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
