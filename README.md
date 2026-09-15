<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ASSIM ASSADO - ESPETOS</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #0a0a0a;
            color: #f5f5f5;
            line-height: 1.6;
        }
        
        .container {
            max-width: 500px;
            margin: 0 auto;
            background: linear-gradient(to bottom, #1a1a1a, #0d0d0d);
            min-height: 100vh;
            box-shadow: 0 0 20px rgba(212, 175, 55, 0.1);
        }
        
        header {
            background: linear-gradient(135deg, #D4AF37, #B8860B);
            color: white;
            padding: 25px 20px;
            text-align: center;
            border-bottom-left-radius: 20px;
            border-bottom-right-radius: 20px;
            position: relative;
            overflow: hidden;
        }
        
        .logo-container {
            background-color: rgba(0, 0, 0, 0.3);
            padding: 15px;
            border-radius: 15px;
            margin-bottom: 15px;
            display: inline-block;
            border: 2px solid rgba(255, 255, 255, 0.2);
            max-width: 300px;
        }
        
        .logo-image {
            max-width: 100%;
            height: auto;
            display: block;
            margin: 0 auto;
            max-height: 120px;
            object-fit: contain;
        }
        
        .logo-text {
            font-size: 32px;
            font-weight: bold;
            line-height: 1.2;
            text-transform: uppercase;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }
        
        .logo-text span {
            display: block;
        }
        
        .logo-text .assim {
            font-size: 36px;
            letter-spacing: 2px;
            color: #D4AF37;
        }
        
        .logo-text .assado {
            font-size: 40px;
            letter-spacing: 3px;
            color: #FFD700;
        }
        
        .logo-text .espetos {
            font-size: 28px;
            letter-spacing: 1px;
            margin-top: 5px;
            color: #D4AF37;
        }
        
        .contact-info {
            margin-top: 15px;
            font-size: 14px;
            background-color: rgba(0, 0, 0, 0.4);
            padding: 10px;
            border-radius: 10px;
        }
        
        .contact-info p {
            margin: 5px 0;
        }
        
        h2 {
            color: #D4AF37;
            margin: 20px 0 15px;
            padding: 0 20px;
            font-size: 22px;
            display: flex;
            align-items: center;
        }
        
        h2 i {
            margin-right: 10px;
        }
        
        .section-divider {
            height: 2px;
            background: linear-gradient(to right, #D4AF37, transparent);
            margin: 10px 20px;
        }
        
        .menu-item {
            display: flex;
            justify-content: space-between;
            margin: 0 20px 15px;
            padding: 12px 15px;
            background: linear-gradient(to right, #1e1e1e, #2a2a2a);
            border-radius: 10px;
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.3);
            border-left: 4px solid #D4AF37;
            transition: transform 0.3s, box-shadow 0.3s;
        }
        
        .menu-item:hover {
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(212, 175, 55, 0.2);
        }
        
        .item-name {
            font-weight: 600;
            font-size: 16px;
        }
        
        .item-price {
            color: #FFD700;
            font-weight: bold;
            font-size: 16px;
        }
        
        .combo-item {
            background: linear-gradient(to right, #1e1e1e, #2a2a2a);
            margin: 15px 20px;
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.3);
            border: 1px dashed #D4AF37;
        }
        
        .combo-title {
            font-weight: bold;
            color: #D4AF37;
            font-size: 18px;
            margin-bottom: 10px;
            text-align: center;
        }
        
        .combo-description {
            font-size: 14px;
            color: #ccc;
            margin-bottom: 10px;
        }
        
        .combo-price {
            text-align: center;
            font-weight: bold;
            color: #FFD700;
            font-size: 20px;
            margin-top: 5px;
        }
        
        .whatsapp-btn {
            display: block;
            width: calc(100% - 40px);
            margin: 30px 20px 20px;
            padding: 16px;
            background: linear-gradient(135deg, #25D366, #128C7E);
            color: white;
            text-align: center;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            font-size: 18px;
            box-shadow: 0 4px 15px rgba(37, 211, 102, 0.4);
            transition: all 0.3s ease;
            position: sticky;
            bottom: 20px;
        }
        
        .whatsapp-btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 6px 20px rgba(37, 211, 102, 0.6);
        }
        
        .whatsapp-btn i {
            margin-right: 10px;
            font-size: 20px;
        }
        
        footer {
            text-align: center;
            padding: 20px;
            color: #999;
            font-size: 14px;
            background-color: #111;
            border-top: 1px solid #333;
        }
        
        .info-section {
            background: linear-gradient(to right, #1e1e1e, #2a2a2a);
            padding: 15px 20px;
            margin: 20px;
            border-radius: 10px;
            border-left: 4px solid #D4AF37;
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.3);
        }
        
        .info-section h3 {
            color: #D4AF37;
            margin-bottom: 10px;
            display: flex;
            align-items: center;
        }
        
        .info-section h3 i {
            margin-right: 10px;
        }
        
        .info-section p {
            margin-bottom: 5px;
            color: #ccc;
        }
        
        .social-icons {
            display: flex;
            justify-content: center;
            margin-top: 15px;
            gap: 15px;
        }
        
        .social-icons a {
            color: #D4AF37;
            font-size: 20px;
            transition: color 0.3s, transform 0.3s;
        }
        
        .social-icons a:hover {
            color: #FFD700;
            transform: scale(1.2);
        }
        
        .menu-category {
            margin-bottom: 25px;
        }
        
        .price-table {
            width: 100%;
            border-collapse: collapse;
            margin: 10px 0;
        }
        
        .price-table td {
            padding: 8px 15px;
            border-bottom: 1px solid #333;
        }
        
        .price-table tr:last-child td {
            border-bottom: none;
        }
        
        .price-table .item {
            text-align: left;
            color: #f5f5f5;
        }
        
        .price-table .price {
            text-align: right;
            color: #FFD700;
            font-weight: bold;
        }
        
        .flame-decoration {
            position: absolute;
            bottom: 0;
            left: 0;
            width: 100%;
            height: 10px;
            background: linear-gradient(90deg, 
                transparent, 
                #D4AF37, 
                #FFD700, 
                #D4AF37, 
                transparent);
            opacity: 0.7;
        }
        
        .grill-pattern {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-image: 
                linear-gradient(90deg, transparent 95%, rgba(212, 175, 55, 0.1) 95%),
                linear-gradient(0deg, transparent 95%, rgba(212, 175, 55, 0.1) 95%);
            background-size: 20px 20px;
            pointer-events: none;
        }
        
        .instagram-section {
            background: linear-gradient(to right, #1e1e1e, #2a2a2a);
            padding: 15px 20px;
            margin: 20px;
            border-radius: 10px;
            border-left: 4px solid #D4AF37;
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.3);
            text-align: center;
        }
        
        .instagram-btn {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            padding: 12px 25px;
            background: linear-gradient(45deg, #405DE6, #5851DB, #833AB4, #C13584, #E1306C, #FD1D1D);
            color: white;
            text-decoration: none;
            border-radius: 25px;
            font-weight: bold;
            transition: all 0.3s ease;
            margin-top: 10px;
        }
        
        .instagram-btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(225, 48, 108, 0.4);
        }
        
        .instagram-btn i {
            margin-right: 8px;
            font-size: 18px;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <div class="grill-pattern"></div>
            <div class="logo-container">
                <!-- Logo do Google Drive -->
                <img src="[https://drive.google.com/file/d/1AnVZw7czb0t0ha6-eFxSBcXCGpskyG1F/view?usp=drive_link](https://github.com/danilomoreiraagr2-lang/assim-assado-cardapio/blob/b736bcc39a4127249d1a32d66b2507fae417c377/LOGO.png)" alt="ASSIM ASSADO ESPETOS" class="logo-image" onerror="replaceWithTextLogo()">
                <!-- Texto de fallback que será mostrado se a imagem não carregar -->
                <div class="logo-text" style="display: none;">
                    <span class="assim">ASSIM</span>
                    <span class="assado">ASSADO</span>
                    <span class="espetos">ESPETOS</span>
                </div>
            </div>
            <div class="contact-info">
                <p><i class="fas fa-map-marker-alt"></i> Av. Paulista, 147 - Santa Cruz das Palmeiras/SP</p>
                <p><i class="fas fa-clock"></i> Quinta a Domingo - 18:00 às 23:00</p>
            </div>
            <div class="flame-decoration"></div>
        </header>
        
        <div class="info-section">
            <h3><i class="fas fa-info-circle"></i> Como fazer seu pedido</h3>
            <p>1. Escolha seus espetos favoritos</p>
            <p>2. Clique no botão do WhatsApp</p>
            <p>3. Envie sua lista de pedidos</p>
        </div>

        <!-- Nova seção do Instagram -->
        <div class="instagram-section">
            <h3><i class="fab fa-instagram"></i> Siga-nos no Instagram</h3>
            <p>Fique por dentro das novidades e promoções!</p>
            <a href="https://instagram.com/assimassadoespetos" class="instagram-btn" target="_blank">
                <i class="fab fa-instagram"></i> @assimassadoespetos
            </a>
        </div>
        
        <div class="menu-category">
            <h2><i class="fas fa-utensils"></i> ESPETOS TRADICIONAIS</h2>
            <div class="section-divider"></div>
            
            <div class="menu-item">
                <div class="item-name">Carne</div>
                <div class="item-price">R$ 7,00</div>
            </div>
            
            <div class="menu-item">
                <div class="item-name">Frango</div>
                <div class="item-price">R$ 6,00</div>
            </div>
            
            <div class="menu-item">
                <div class="item-name">Coração</div>
                <div class="item-price">R$ 6,00</div>
            </div>
            
            <div class="menu-item">
                <div class="item-name">Kafta</div>
                <div class="item-price">R$ 6,00</div>
            </div>
            
            <div class="menu-item">
                <div class="item-name">Linguiça</div>
                <div class="item-price">R$ 6,00</div>
            </div>
            
            <div class="menu-item">
                <div class="item-name">Panceta</div>
                <div class="item-price">R$ 6,00</div>
            </div>
            
            <div class="menu-item">
                <div class="item-name">Tulipa</div>
                <div class="item-price">R$ 6,00</div>
            </div>
        </div>
        
        <div class="menu-category">
            <h2><i class="fas fa-star"></i> ESPETOS ESPECIAIS</h2>
            <div class="section-divider"></div>
            
            <div class="menu-item">
                <div class="item-name">Medalhão de Frango</div>
                <div class="item-price">R$ 7,00</div>
            </div>
            
            <div class="menu-item">
                <div class="item-name">Medalhão de Mandioca</div>
                <div class="item-price">R$ 7,00</div>
            </div>
            
            <div class="menu-item">
                <div class="item-name">Coração c/ Parmesão</div>
                <div class="item-price">R$ 7,00</div>
            </div>
            
            <div class="menu-item">
                <div class="item-name">Romeu e Julieta</div>
                <div class="item-price">R$ 8,00</div>
            </div>
            
            <div class="menu-item">
                <div class="item-name">Kafta c/ Queijo</div>
                <div class="item-price">R$ 8,00</div>
            </div>
        </div>
        
        <div class="menu-category">
            <h2><i class="fas fa-concierge-bell"></i> JANTINHAS</h2>
            <div class="section-divider"></div>
            
            <div class="combo-item">
                <div class="combo-title">JANTINHA 01</div>
                <div class="combo-description">01 Espeto + Arroz, Farofa, Vinagrete, Mandioca, Batata Frita, Creme de Alho</div>
                <div class="combo-price">R$ 12,00</div>
            </div>
            
            <div class="combo-item">
                <div class="combo-title">JANTINHA 02</div>
                <div class="combo-description">02 Espetos + Arroz, Farofa, Vinagrete, Mandioca, Batata Frita, Creme de Alho</div>
                <div class="combo-price">R$ 18,00</div>
            </div>
            
            <div class="combo-item">
                <div class="combo-title">JANTINHA 03</div>
                <div class="combo-description">04 Espetos + Arroz, Farofa, Vinagrete, Mandioca, Batata Frita, Creme de Alho</div>
                <div class="combo-price">R$ 32,00</div>
            </div>
        </div>
        
        <div class="menu-category">
            <h2><i class="fas fa-drumstick-bite"></i> PORÇÕES E BARCA</h2>
            <div class="section-divider"></div>
            
            <div class="combo-item">
                <div class="combo-title">BARCA COMPLETA</div>
                <div class="combo-description">08 Espetos (Carne, Coração, Frango, Tulipa, Kafta, Linguiça, Panceta, Medalhão de Frango) + Acompanhamentos: Batata Frita, Pão de Alho, Farofa, Vinagrete</div>
                <div class="combo-price">R$ 75,00</div>
            </div>
            
            <div class="menu-item">
                <div class="item-name">Batata Frita</div>
                <div class="item-price">R$ 12,00</div>
            </div>
            
            <div class="menu-item">
                <div class="item-name">Mandioca Frita</div>
                <div class="item-price">R$ 12,00</div>
            </div>
            
            <div class="menu-item">
                <div class="item-name">Polenta Frita</div>
                <div class="item-price">R$ 10,00</div>
            </div>
        </div>
        
        <div class="menu-category">
            <h2><i class="fas fa-hamburger"></i> LANCHES</h2>
            <div class="section-divider"></div>
            
            <div class="menu-item">
                <div class="item-name">Carne</div>
                <div class="item-price">R$ 12,00</div>
            </div>
            
            <div class="menu-item">
                <div class="item-name">Frango</div>
                <div class="item-price">R$ 12,00</div>
            </div>
            
            <div class="menu-item">
                <div class="item-name">Kafta</div>
                <div class="item-price">R$ 12,00</div>
            </div>
            
            <div class="menu-item">
                <div class="item-name">Linguiça</div>
                <div class="item-price">R$ 10,00</div>
            </div>
            
            <div class="menu-item">
                <div class="item-name">Coração</div>
                <div class="item-price">R$ 12,00</div>
            </div>
            
            <div class="menu-item">
                <div class="item-name">Medalhão de Frango</div>
                <div class="item-price">R$ 13,00</div>
            </div>
        </div>
        
        <div class="menu-category">
            <h2><i class="fas fa-wine-bottle"></i> BEBIDAS</h2>
            <div class="section-divider"></div>
            
            <h3 style="padding: 0 20px; margin: 15px 0 10px; color: #D4AF37; font-size: 18px;">Refrigerantes / Sucos / Água</h3>
            <table class="price-table">
                <tr>
                    <td class="item">Coca Cola (LATA)</td>
                    <td class="price">R$ 6,00</td>
                </tr>
                <tr>
                    <td class="item">Coca Cola zero (LATA)</td>
                    <td class="price">R$ 7,00</td>
                </tr>
                <tr>
                    <td class="item">Itubaina (LATA)</td>
                    <td class="price">R$ 5,00</td>
                </tr>
                <tr>
                    <td class="item">Sprite (LATA)</td>
                    <td class="price">R$ 5,00</td>
                </tr>
                <tr>
                    <td class="item">Coca Cola (2L)</td>
                    <td class="price">R$ 13,00</td>
                </tr>
                <tr>
                    <td class="item">Coca Cola 1L</td>
                    <td class="price">R$ 12,00</td>
                </tr>
                <tr>
                    <td class="item">Coca Cola zero (2L)</td>
                    <td class="price">R$ 14,00</td>
                </tr>
                <tr>
                    <td class="item">Sprite (2L)</td>
                    <td class="price">R$ 12,00</td>
                </tr>
                <tr>
                    <td class="item">Jabuti (2L)</td>
                    <td class="price">R$ 8,00</td>
                </tr>
                <tr>
                    <td class="item">H2o</td>
                    <td class="price">R$ 12,00</td>
                </tr>
                <tr>
                    <td class="item">Ice</td>
                    <td class="price">R$ 12,00</td>
                </tr>
                <tr>
                    <td class="item">Suco Nativo</td>
                    <td class="price">R$ 4,00</td>
                </tr>
            </table>
            
            <h3 style="padding: 0 20px; margin: 20px 0 10px; color: #D4AF37; font-size: 18px;">Cervejas</h3>
            <table class="price-table">
                <tr>
                    <td class="item">Original (300ML)</td>
                    <td class="price">R$ 7,00</td>
                </tr>
                <tr>
                    <td class="item">Brahma (300ML)</td>
                    <td class="price">R$ 6,00</td>
                </tr>
                <tr>
                    <td class="item">Antartica (300ML)</td>
                    <td class="price">R$ 6,00</td>
                </tr>
                <tr>
                    <td class="item">Antartica (LATA)</td>
                    <td class="price">R$ 7,00</td>
                </tr>
                <tr>
                    <td class="item">Heineken (350ML)</td>
                    <td class="price">R$ 9,00</td>
                </tr>
            </table>
        </div>
        
        <div class="menu-category">
            <h2><i class="fas fa-plus-circle"></i> ADICIONAIS</h2>
            <div class="section-divider"></div>
            
            <div class="menu-item">
                <div class="item-name">Vinagrete</div>
                <div class="item-price">R$ 5,00</div>
            </div>
            
            <div class="menu-item">
                <div class="item-name">Farofa</div>
                <div class="item-price">R$ 5,00</div>
            </div>
            
            <div class="menu-item">
                <div class="item-name">Arroz</div>
                <div class="item-price">R$ 5,00</div>
            </div>
            
            <div class="menu-item">
                <div class="item-name">Creme de Alho</div>
                <div class="item-price">R$ 7,00</div>
            </div>
        </div>
        
        <a href="https://wa.me/5519982010243?text=Olá! Gostaria de fazer um pedido do ASSIM ASSADO ESPETOS:" class="whatsapp-btn">
            <i class="fab fa-whatsapp"></i> Fazer Pedido pelo WhatsApp
        </a>
        
        <footer>
            <p>ASSIM ASSADO - ESPETOS</p>
            <p>Delivery e Retirada no Local</p>
            <p>Tel: (19) 9 8201-0243</p>
            <div class="social-icons">
                <!-- SUBSTITUA O LINK ABAIXO PELO SEU INSTAGRAM REAL -->
                <a href="https://instagram.com/assimassadoespetos" target="_blank">
                    <i class="fab fa-instagram"></i>
                </a>
                <a href="#">
                    <i class="fab fa-facebook"></i>
                </a>
            </div>
        </footer>
    </div>

    <script>
        // Função para substituir a imagem por texto se não carregar
        function replaceWithTextLogo() {
            const logoImage = document.querySelector('.logo-image');
            const logoText = document.querySelector('.logo-text');
            
            if (logoImage && logoText) {
                logoImage.style.display = 'none';
                logoText.style.display = 'block';
            }
        }
        
        // Tenta carregar a imagem e verifica se há erro
        document.addEventListener('DOMContentLoaded', function() {
            const logoImage = document.querySelector('.logo-image');
            if (logoImage) {
                logoImage.onerror = replaceWithTextLogo;
                
                // Verifica se a imagem carregou (para casos onde a imagem não existe)
                setTimeout(function() {
                    if (logoImage.naturalWidth === 0) {
                        replaceWithTextLogo();
                    }
                }, 1000);
            }
        });

        // Função para gerar mensagem de pedido
        document.querySelector('.whatsapp-btn').addEventListener('click', function(e) {
            const phoneNumber = "5519982010243";
            const message = "Olá! Gostaria de fazer um pedido do ASSIM ASSADO ESPETOS. Pode me ajudar?";
            
            // Atualiza o link do WhatsApp
            this.href = `https://wa.me/${phoneNumber}?text=${encodeURIComponent(message)}`;
        });
    </script>
</body>
</html>
