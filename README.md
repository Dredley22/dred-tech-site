<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dred Tech - Soluções em Eletrotécnica e Automação</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #000;
            color: #fff;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #001f3f;
            padding: 20px;
            text-align: center;
            color: #fff;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #003366;
            padding: 10px 0;
        }
        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
            font-size: 1.1em;
        }
        nav a:hover {
            text-decoration: underline;
        }
        main {
            padding: 20px;
        }
        section {
            margin-bottom: 40px;
        }
        .products, .services {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .product, .service {
            background-color: #00264d;
            border: 1px solid #004080;
            border-radius: 10px;
            margin: 15px;
            padding: 20px;
            width: 300px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
        }
        .product img, .service img {
            width: 100%;
            border-radius: 10px;
        }
        footer {
            background-color: #001f3f;
            text-align: center;
            padding: 20px 0;
            position: relative;
            width: 100%;
            bottom: 0;
        }
        .social-links a {
            color: #fff;
            margin: 0 10px;
            text-decoration: none;
            font-size: 1.2em;
        }
    </style>
</head>
<body>
    <header>
        <h1>Dred Tech</h1>
        <p>Soluções em Eletrotécnica e Automação</p>
    </header>
    <nav>
        <a href="#venda">Venda de Material</a>
        <a href="#servicos">Serviços</a>
        <a href="#contato">Contato</a>
    </nav>
    <main>
        <section id="venda">
            <h2>Venda de Material Elétrico e Eletrodomésticos</h2>
            <div class="products">
                <div class="product">
                    <img src="https://via.placeholder.com/300" alt="Produto 1">
                    <h3>Produto 1</h3>
                    <p>Descrição do produto 1. Alta qualidade e eficiência.</p>
                    <p><strong>Preço: R$100,00</strong></p>
                </div>
                <div class="product">
                    <img src="https://via.placeholder.com/300" alt="Produto 2">
                    <h3>Produto 2</h3>
                    <p>Descrição do produto 2. Ideal para uso residencial.</p>
                    <p><strong>Preço: R$150,00</strong></p>
                </div>
                <div class="product">
                    <img src="https://via.placeholder.com/300" alt="Produto 3">
                    <h3>Produto 3</h3>
                    <p>Descrição do produto 3. Eficiência energética garantida.</p>
                    <p><strong>Preço: R$200,00</strong></p>
                </div>
            </div>
        </section>
        <section id="servicos">
            <h2>Serviços de Eletrotécnica e Automação</h2>
            <div class="services">
                <div class="service">
                    <img src="https://via.placeholder.com/300" alt="Serviço 1">
                    <h3>Instalações Elétricas</h3>
                    <p>Realizamos instalações elétricas seguras e eficientes.</p>
                </div>
                <div class="service">
                    <img src="https://via.placeholder.com/300" alt="Serviço 2">
                    <h3>Sistemas de Segurança</h3>
                    <p>Oferecemos soluções completas para segurança residencial e industrial.</p>
                </div>
                <div class="service">
                    <img src="https://via.placeholder.com/300" alt="Serviço 3">
                    <h3>Automação Residencial</h3>
                    <p>Transforme sua casa em uma casa inteligente com nossos sistemas de automação.</p>
                </div>
            </div>
        </section>
        <section id="contato">
            <h2>Contato</h2>
            <p>Para mais informações sobre nossos produtos e serviços, entre em contato conosco através das redes sociais:</p>
            <div class="social-links">
                <a href="https://www.instagram.com/dred.tech22?igsh=MWJ1MTgxemp1bjFmcQ==">Instagram</a>
                <a href="https://youtube.com/@dredtech22?si=1rd5tSmc9SRQJDd1">YouTube</a>
            </div>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Dred Tech. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
