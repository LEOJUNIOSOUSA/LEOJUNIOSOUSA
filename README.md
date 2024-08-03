<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Leo Junio Sousa - Blog & Contato</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: url('background.jpg') no-repeat center center fixed;
            background-size: cover;
            color: #333;
        }
        header {
            background-color: #1e1e1e;
            padding: 20px;
            text-align: center;
            color: white;
        }
        header h1 {
            margin: 0;
        }
        nav {
            text-align: center;
            margin: 20px 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        .content {
            max-width: 800px;
            margin: auto;
            padding: 20px;
            background-color: rgba(255, 255, 255, 0.8);
        }
        .blog-post {
            border-bottom: 1px solid #ccc;
            padding: 20px 0;
        }
        .blog-post h2 {
            margin: 0;
        }
        .blog-post p {
            margin: 10px 0 0 0;
        }
        .comments-section {
            margin-top: 20px;
        }
        .comments-section h3 {
            margin-bottom: 10px;
        }
        .comment {
            margin-bottom: 15px;
            padding: 10px;
            background-color: #f9f9f9;
            border-radius: 5px;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #1e1e1e;
            color: white;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .social-links a {
            color: white;
            margin: 0 10px;
            text-decoration: none;
            font-size: 20px;
        }
        .contact-form {
            display: flex;
            flex-direction: column;
        }
        .contact-form input, .contact-form textarea {
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .contact-form button {
            padding: 10px;
            background-color: #1e1e1e;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <header>
        <h1>Leo Junio Sousa</h1>
        <nav>
            <a href="#blog">Blog</a>
            <a href="#contato">Contato</a>
        </nav>
    </header>

    <section id="blog" class="content">
        <h2>Blog</h2>

        <article class="blog-post">
            <h2>Primeiro Post do Blog</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin vel hendrerit nulla.</p>

            <div class="comments-section">
                <h3>Comentários:</h3>
                <div class="comment">
                    <strong>Usuário 1:</strong>
                    <p>Ótimo post!</p>
                </div>
                <div class="comment">
                    <strong>Usuário 2:</strong>
                    <p>Obrigado por compartilhar!</p>
                </div>
                <form>
                    <textarea rows="3" placeholder="Adicione um comentário..."></textarea>
                    <button type="submit">Comentar</button>
                </form>
            </div>
        </article>

        <article class="blog-post">
            <h2>Segundo Post do Blog</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin vel hendrerit nulla.</p>

            <div class="comments-section">
                <h3>Comentários:</h3>
                <div class="comment">
                    <strong>Usuário 3:</strong>
                    <p>Informações muito úteis!</p>
                </div>
                <form>
                    <textarea rows="3" placeholder="Adicione um comentário..."></textarea>
                    <button type="submit">Comentar</button>
                </form>
            </div>
        </article>
    </section>

    <section id="contato" class="content">
        <h2>Contato</h2>
        <form class="contact-form">
            <input type="text" placeholder="Nome" required>
            <input type="email" placeholder="Email" required>
            <textarea rows="5" placeholder="Mensagem" required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <div class="social-links">
            <a href="#">LinkedIn</a>
            <a href="#">Twitter</a>
            <a href="#">GitHub</a>
        </div>
        <p>&copy; 2024 Leo Junio Sousa. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
