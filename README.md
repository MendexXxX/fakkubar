# fakkubar
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fakku Bar</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(180deg, #000000, #ff0000);
            color: #fff;
        }
        header {
            background-color: #000;
            text-align: center;
            padding: 20px;
        }
        header img {
            max-width: 200px;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #ff0000;
            padding: 10px 0;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .banner {
            text-align: center;
            padding: 50px 20px;
        }
        .banner img {
            max-width: 300px;
            border: 2px solid #fff;
        }
        .content {
            text-align: center;
            padding: 20px;
        }
        .content h2 {
            color: #ffcc00;
        }
        footer {
            background-color: #000;
            text-align: center;
            padding: 20px;
            color: #fff;
        }
        footer a {
            color: #ffcc00;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <img src="logo-fakku.png" alt="Logo Fakku Bar">
    </header>
    <nav>
        <a href="#sobre">Sobre</a>
        <a href="#eventos">Eventos</a>
        <a href="#contato">Contato</a>
    </nav>
    <div class="banner">
        <img src="banner-pagode.png" alt="Banner Pagode no Fakku">
        <h1>Bem-vindo ao Fakku Bar!</h1>
        <p>O melhor bar com música ao vivo e pagode de sexta a domingo!</p>
    </div>
    <div class="content">
        <section id="sobre">
            <h2>Sobre Nós</h2>
            <p>O Fakku Bar é o lugar perfeito para quem ama boa música, um ambiente descontraído e ótimo atendimento. Localizado em Vila Buarque, São Paulo, trazemos o melhor do pagode ao vivo para você e seus amigos curtirem o final de semana!</p>
        </section>
        <section id="eventos">
            <h2>Próximos Eventos</h2>
            <p>🎵 Pagode ao vivo toda sexta, sábado e domingo a partir das 20h.</p>
            <p>🎤 Bandas locais e convidados especiais trazendo os maiores sucessos do pagode.</p>
        </section>
        <section id="contato">
            <h2>Contato</h2>
            <p>📍 Rua Dr. Cesário Mota Júnior, 629 - Vila Buarque, São Paulo</p>
            <p>📞 Telefone: (11) 1234-5678</p>
            <p>📧 E-mail: contato@fakkubar.com</p>
        </section>
    </div>
    <footer>
        <p>&copy; 2025 Fakku Bar. Todos os direitos reservados.</p>
        <p>Desenvolvido por <a href="mailto:otavio@fakkubar.com">otavio</a>.</p>
    </footer>
</body>
</html>
