<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BetMaster - Seu site de apostas</title>
    <style>
        /* CSS */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
        }

        header {
            background-color: #1e90ff;
            color: white;
            padding: 1rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header .logo {
            font-size: 1.5rem;
            font-weight: bold;
        }

        header nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
            gap: 1rem;
        }

        header nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        .banner img {
            width: 100%;
            height: auto;
        }

        section {
            padding: 2rem;
        }

        section#bets img {
            width: 100%;
            height: auto;
            margin-top: 20px;
        }

        footer {
            text-align: center;
            background-color: #1e90ff;
            color: white;
            padding: 1rem;
            margin-top: 2rem;
        }
    </style>
</head>
<body>
    <!-- Cabeçalho -->
    <header>
        <div class="logo">BetMaster</div>
        <nav>
            <ul>
                <li><a href="#home">Início</a></li>
                <li><a href="#bets">Apostas</a></li>
                <li><a href="#promotions">Promoções</a></li>
                <li><a href="#contact">Contato</a></li>
            </ul>
        </nav>
    </header>

    <!-- Banner principal -->
    <section id="home" class="banner">
        <img src="/mnt/data/A_promotional_banner_for_a_betting_website_designe.png" 
             alt="Promoção: Ganhe até R$500 no Primeiro Depósito!">
    </section>

    <!-- Seção de apostas -->
    <section id="bets">
        <h2>Apostas Disponíveis</h2>
        <ul>
            <li>Futebol - Jogos ao vivo</li>
            <li>Basquete - Próximos eventos</li>
            <li>E-sports - Competição global</li>
        </ul>
        <img src="/mnt/data/A_promotional_banner_for_a_betting_website_designe.png" 
             alt="Aposte Agora e Multiplique Seus Ganhos!">
    </section>

    <!-- Seção de promoções -->
    <section id="promotions">
        <h2>Promoções</h2>
        <p>Aproveite o bônus de 100% no seu primeiro depósito!</p>
    </section>

    <!-- Rodapé -->
    <footer id="contact">
        <p>© 2025 BetMaster. Todos os direitos reservados.</p>
        <p>Entre em contato: suporte@betmaster.com</p>
    </footer>
</body>
</html>
