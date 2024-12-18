<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>General Vision</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #333;
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #bbb 1px solid;
        }
        header a {
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        header nav {
            float: right;
            margin-top: 10px;
        }
        header nav a {
            margin-left: 20px;
        }
        .main-content {
            background: #fff;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            margin-top: 20px;
        }
        .contact-info {
            margin-top: 30px;
        }
        .contact-info p {
            font-size: 18px;
        }
        .contact-info a {
            color: #333;
            text-decoration: none;
            font-weight: bold;
        }
        .qr-code {
            margin-top: 20px;
            text-align: center;
        }
    </style>
</head>
<body>

<header>
    <div class="container">
        <h1>General Vision</h1>
        <nav>
            <a href="#sobre">Sobre</a>
            <a href="#contato">Contato</a>
        </nav>
    </div>
</header>

<div class="container">
    <div class="main-content" id="sobre">
        <h2>Bem-vindo à General Vision</h2>
        <p><strong>General Vision</strong> é uma empresa especializada em integrar tecnologias avançadas a veículos comerciais, máquinas pesadas e equipamentos operacionais. Utilizamos <strong>câmeras 360°, sensores e inteligência artificial</strong> para proporcionar soluções que eliminam pontos cegos, melhoram a visibilidade e reduzem significativamente os acidentes. Nosso foco é unir tecnologia de ponta aos equipamentos já existentes, aumentando a segurança, a produtividade e a eficiência das operações. Oferecemos instalação de sistemas de monitoramento inteligente, adaptados às necessidades específicas de cada cliente, seja em frotas de transporte, veículos utilitários ou maquinário pesado.</p>
    </div>

    <div class="contact-info" id="contato">
        <h3>Entre em Contato</h3>
        <p>Se você deseja mais informações ou quer solicitar nossos serviços, entre em contato conosco:</p>
        <p><strong>WhatsApp:</strong> <a href="https://api.whatsapp.com/send?phone=5534991195042&text=Ol%C3%A1,%20gostaria%20de%20entrar%20em%20contato%20com%20voc%C3%AA">+55 34 99119-5042</a></p>
        <p><strong>E-mail:</strong> <a href="mailto:henriquepaivacontact@icloud.com">henriquepaivacontact@icloud.com</a></p>
    </div>

    <div class="qr-code">
        <h3>Escaneie o QR Code para mais detalhes de contato</h3>
        <img src="https://api.qrserver.com/v1/create-qr-code/?data=tel%3A%2B5534991195042%0Aemail%3A%20henriquepaivacontact%40icloud.com&size=200x200" alt="QR Code de Contato" />
    </div>
</div>

</body>
</html>
