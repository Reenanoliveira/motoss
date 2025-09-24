<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mundo das Motos - Paixão em Duas Rodas</title>
    
    <style>
        /* RESET BÁSICO */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box; 
        }

        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f4f4f4;
            color: #333;
        }

        /* ESTILO DO CABEÇALHO (HEADER) */
        header {
            background-color: #1a1a1a;
            color: white;
            padding: 20px 0;
            text-align: center;
            border-bottom: 5px solid #d9534f;
        }

        header h1 {
            margin-bottom: 10px;
        }

        /* ESTILO DA NAVEGAÇÃO (NAV) */
        nav ul {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: center;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            padding: 5px 10px;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: #d9534f;
        }

        /* ESTILO DA SEÇÃO HERO (Banner principal) */
        .hero {
            /* IMPORTANTE: Substitua 'moto_background.jpg' pela sua imagem real, ou remova esta linha se não tiver uma. */
            background: url('moto_background.jpg') no-repeat center center/cover;
            color: white;
            text-align: center;
            padding: 100px 20px;
            margin-bottom: 30px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
            /* Se não tiver imagem, use uma cor sólida como backup: */
            /* background-color: #333; */
        }

        .hero h2 {
            font-size: 3em;
            margin-bottom: 10px;
        }

        .hero p {
            font-size: 1.2em;
            margin-bottom: 20px;
        }

        .btn {
            display: inline-block;
            background-color: #d9534f;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            transition: background-color 0.3s;
        }

        .btn:hover {
            background-color: #c9302c;
        }

        /* ESTILO DAS SEÇÕES DE CONTEÚDO */
        .content-section {
            max-width: 1000px;
            margin: 0 auto 40px auto;
            padding: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        .content-section h3 {
            color: #1a1a1a;
            border-bottom: 2px solid #eee;
            padding-bottom: 10px;
            margin-bottom: 20px;
            text-align: center;
        }

        /* ESTILO DOS CARDS DE MOTO */
        #modelos {
            text-align: center;
        }

        .moto-card {
            display: inline-block;
            width: 30%; 
            min-width: 250px; /* Garante que não fiquem pequenos demais */
            margin: 10px;
            padding: 20px;
            background-color: #f9f9f9;
            border: 1px solid #ddd;
            border-radius: 5px;
            text-align: left;
            transition: transform 0.3s;
        }

        .moto-card:hover {
            transform: translateY(-5px); 
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }

        .moto-card h4 {
            color: #d9534f;
            margin-bottom: 10px;
        }

        /* ESTILO DO RODAPÉ (FOOTER) */
        footer {
            background-color: #1a1a1a;
            color: #aaa;
            text-align: center;
            padding: 20px 0;
            margin-top: 30px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Mundo das Motos</h1>
        <nav>
            <ul>
                <li><a href="#">Início</a></li>
                <li><a href="#modelos">Modelos</a></li>
                <li><a href="#historia">História</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="hero">
            <h2>Sinta a Liberdade da Estrada</h2>
            <p>Descubra a adrenalina e a paixão por trás de cada máquina de duas rodas. De esportivas a custom, o seu próximo destino está aqui.</p>
            <a href="#modelos" class="btn">Ver Modelos</a>
        </section>

        <section id="modelos" class="content-section">
            <h3>Modelos em Destaque</h3>
            <div class="moto-card">
                <h4>Esportivas</h4>
                <p>Velocidade e performance no asfalto, projetadas para a máxima adrenalina.</p>
            </div>
            <div class="moto-card">
                <h4>Custom</h4>
                <p>Estilo clássico, cromados e conforto para longas viagens pela estrada.</p>
            </div>
            <div class="moto-card">
                <h4>Trail/Aventura</h4>
                <p>Prontas para qualquer terreno, do asfalto à trilha mais desafiadora.</p>
            </div>
        </section>

        <section id="historia" class="content-section">
            <h3>A História das Duas Rodas</h3>
            <p>Conheça a evolução das motocicletas desde as primeiras invenções no século XIX até as máquinas modernas e tecnológicas de hoje. Uma jornada fascinante!</p>
        </section>

        <section id="contato" class="content-section">
            <h3>Fale Conosco</h3>
            <p>Envie sua sugestão, crítica ou compartilhe sua paixão por motos. Nosso time responderá o mais breve possível.</p>
            </section>
    </main>

    <footer>
        <p>&copy; 2024 Mundo das Motos. Todos os direitos reservados. Feito com paixão!</p>
    </footer>

</body>
</html>
