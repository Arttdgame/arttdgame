<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Halloween Horripilante</title>
    <link href="https://fonts.googleapis.com/css2?family=Creepster&display=swap" rel="stylesheet"> <!-- Fonte assustada -->
    <style>
        body {
            background-color: black;
            color: orange;
            font-family: 'Arial', sans-serif;
            text-align: center;
        }
        h1 {
            font-size: 3em;
            margin-top: 50px;
            font-family: 'Creepster', cursive; /* Aplicando a fonte assustadora */
        }
        p {
            font-size: 1.5em;
            margin: 20px;
        }
        @keyframes sway {
            0% { transform: rotate(0deg); }
            25% { transform: rotate(10deg); }
            50% { transform: rotate(0deg); }
            75% { transform: rotate(-10deg); }
            100% { transform: rotate(0deg); }
        }
        .pumpkin {
            font-size: 5em;
            animation: sway 1.5s ease-in-out infinite; /* Animação de balançar */
        }
        .social-button {
            display: inline-block;
            margin: 15px;
            padding: 7px 15px; /* Diminuindo o padding */
            background-color: orange;
            color: black;
            border: none;
            border-radius: 10px;
            font-size: 0.75em; /* Diminuindo o tamanho da fonte */
            font-weight: bold; /* Texto em negrito */
            cursor: pointer;
            text-decoration: none;
            position: relative;
        }
        .icon {
            font-size: 1.5em; /* Tamanho do ícone reduzido */
            margin-right: 5px; /* Espaço entre o ícone e o texto */
            vertical-align: middle; /* Alinha o ícone com o texto */
        }
        footer {
            margin-top: 50px;
            font-size: 1em;
        }
        a {
            color: orange;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <audio autoplay loop>
        <source src="caminho/para/sua-musica.mp3" type="audio/mpeg">
        Seu navegador não suporta o elemento de áudio.
    </audio>

    <h1>Feliz Halloween!</h1>
    <p class="pumpkin">🎃</p>
    <p>Prepare-se para uma noite de assombrações!</p>
    <p>Vista-se de forma assustadora e saia para coletar doces!</p>

    <div>
        <a href="https://www.instagram.com/arttdgame" class="social-button">
            <span class="icon">🧛‍♂️</span>Instagram
        </a>
        <a href="https://www.kwai.com" class="social-button">
            <span class="icon">🎃</span>Kwai
        </a>
        <a href="https://www.tiktok.com" class="social-button">
            <span class="icon">💀</span>TikTok
        </a>
        <a href="https://www.hotmart.com" class="social-button">
            <span class="icon">🦇</span>Hotmart
        </a>
        <a href="https://www.facebook.com" class="social-button">
            <span class="icon">🕷️</span>Facebook
        </a>
        <a href="https://www.seusite.com" class="social-button">
            <span class="icon">👻</span>Site
        </a>
    </div>

    <footer>
        <p>&copy; 2024 Halloween Horripilante. Todos os direitos reservados.</p>
        <p><a href="#">Voltar ao topo</a></p>
    </footer>
</body>
</html>
