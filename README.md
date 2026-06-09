<!DOCTYPE html>
<html lang="pt-AO">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AluAngola Atacado | Fábrica de Alumínio</title>
    <!-- Ícones e Estilos Modernos -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', Arial, sans-serif; }
        body { background-color: #f4f6f8; color: #333; }
        
        /* Topo e Identidade */
        header { background: #fff; box-shadow: 0 2px 10px rgba(0,0,0,0.05); sticky: top; position: sticky; top: 0; z-index: 100; }
        .top-notice { background: #ff6600; color: white; text-align: center; padding: 6px; font-size: 13px; font-weight: bold; }
        .navbar { display: flex; justify-content: space-between; align-items: center; padding: 15px 5%; }
        .logo h1 { font-size: 24px; color: #222; }
        .logo span { color: #ff6600; }
        .badge-ao { background: #d11515; color: white; padding: 2px 6px; font-size: 11px; border-radius: 3px; margin-left: 5px; vertical-align: middle; }

        /* Banner */
        .hero { background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), url('https://images.unsplash.com/photo-1581091226825-a6a2a5aee158?auto=format&fit=crop&w=1200&q=80') center/cover; color: white; text-align: center; padding: 60px 20px; }
        .hero h2 { font-size: 32px; margin-bottom: 10px; }
        .hero p { color: #ccc; margin-bottom: 20px; }

        /* Content e Grid */
        .container { max-width: 1200px; margin: 40px auto; padding: 0 20px; }
        .section-title { margin-bottom: 30px; border-left: 5px solid #ff6600; padding-left: 15px; }
        .products-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(320px, 1fr)); gap: 30px; }
        
        /* Cartão de Produto Estilo Alibaba */
        .product-card { background: white; border-radius: 8px; border: 1px solid #e0e0e0; overflow: hidden; display: flex; flex-direction: column; transition: 0.3s; }
        .product-card:hover { box-shadow: 0 4px 15px rgba(0,0,0,0.1); }
        .product-img { height: 200px; background: #eaeaea; display: flex; align-items: center; justify-content: center; overflow: hidden; position: relative; }
        .product-img img { width: 100%; height: 100%; object-fit: cover; }
        .moq-tag { position: absolute; top: 10px; left: 10px; background: rgba(0,0,0,0.7); color: white; padding: 4px 8px; font-size: 12px; border-radius: 4px; font-weight: bold; }
        
        .product-detail { padding: 20px; display: flex; flex-direction: column; flex-grow: 1; }
        .product-detail h3 { font-size: 18px; margin-bottom: 10px; color: #222; }
        
        /* Tabela de Preço por Quantidade */
        .wholesale-table { width: 100%; background: #f9f9f9; border-collapse: collapse; margin-bottom: 15px; font-size: 13px; }
        .wholesale-table th, .wholesale-table td { padding: 8px; text-align: left; border: 1px solid #eee; }
        .wholesale-table th { background: #f0f0f0; color: #666; }
        .highlight-price { color: #ff6600; font-weight: bold; }

        /* Inputs e Botão */
        .order-zone { margin-top: auto; background: #fff8f4; padding: 15px; border-radius: 6px; border: 1px dashed #ffb380; }
        .qty-input-group { display: flex; align-items: center; justify-content: space-between; margin-bottom: 12px; }
        .qty-input-group label { font-size: 14px; font-weight: bold; }
        .qty-input-group input { width: 80px; padding: 6px; border: 1px solid #ccc; border-radius: 4px; text-align: center; font-weight: bold; }
        
        .live-total { font-size: 14px; margin-bottom: 12px; color: #555; }
        .live-total span { font-weight: bold; color: #222; }

        .btn-order { display: block; width: 100%; background: #ff6600; color: white; text-align: center; padding: 12px; border: none; border-radius: 4px; font-size: 15px; font-weight: bold; cursor: pointer; text-decoration: none; transition: 0.2s; }
        .btn-order:hover { background: #e65500; }
        .btn-order i { margin-right: 8px; }

        /* Rodapé Informativo */
        footer { background: #222; color: white; padding: 40px 5%; margin-top: 60px; }
        .footer-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 30px; }
        .footer-col h4 { margin-bottom: 15px; color: #ff6600; }
        .footer-col p, .footer-col li { color: #aaa; font-size: 14px; list-style: none; margin-bottom: 8px; }
        .footer-bottom { text-align: center; padding-top: 30px; margin-top: 30px; border-top: 1px solid #333; font-size: 13px; color: #666; }
    </style>
</head>
<body>

    <!-- Topo -->
    <header>
        <div class="top-notice">Portal de Atacado B2B — Distribuição Direta de Luanda para todas as Províncias</div>
        <div class="navbar">
            <div class="logo">
                <h1>Alu<span>Angola</span><span class="badge-ao">AO</span></h1>
            </div>
            <div>
                <span style="font-size: 14px; color: #666;"><i class="fas fa-truck"></i> Logística Facilitada</span>
            </div>
        </div>
    </header>

    <!-- Banner Principal -->
    <section class="hero">
        <h2>Fábrica Nacional de Utensílios de Alumínio</h2>
        <p>Selecione a quantidade desejada abaixo. O sistema calcula o preço de grosso automaticamente.</p>
    </section>

    <!-- Content -->
    <main class="container">
        <div class="section-title">
            <h2>Catálogo de Produtos e Pedido Direto</h2>
            <p>Preços decrescentes conforme o volume de compra</p>
        </div>

        <div class="products-grid">

            <!-- PRODUTO 1: Formas de Bolo -->
            <div class="product-card">
                <div class="product-img">
                    <span class="moq-tag">Mínimo: 10 unids</span>
                    <img src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=400&q=80" alt="Formas de Bolo">
                </div>
                <div class="product-detail">
                    <h3>Forma de Bolo Alumínio Padrão</h3>
                    
                    <table class="wholesale-table">
                        <tr><th>Quantidade</th><th>Preço Unid.</th></tr>
                        <tr><td>10 a 29 unids</td><td class="highlight-price">2.000 Kz</td></tr>
                        <tr><td>30 a 99 unids</td><td class="highlight-price">1.700 Kz</td></tr>
                        <tr><td>100+ unids</td><td class="highlight-price">1.400 Kz</td></tr>
                    </table>

                    <div class="order-zone">
                        <div class="qty-input-group">
                            <label>Quantidade:</label>
                            <input type="number" id="qty-forma" value="10" min="10" oninput="calcularForma()">
                        </div>
                        <div class="live-total">
                            Preço Unitário: <span id="unit-forma">2.000 Kz</span><br>
                            Subtotal: <span id="total-forma" style="color: #ff6600; font-size: 16px;">20.000 Kz</span>
                        </div>
                        <button class="btn-order" onclick="enviarPedido('Forma de Bolo', 'qty-forma')">
                            <i class="fab fa-whatsapp"></i> Pedir no Grosso
                        </button>
                    </div>
                </div>
            </div>

            <!-- PRODUTO 2: Pratos -->
            <div class="product-card">
                <div class="product-img">
                    <span class="moq-tag">Mínimo: 50 unids</span>
                    <img src="https://images.unsplash.com/photo-1610701596007-11502861affa?auto=format&fit=crop&w=400&q=80" alt="Pratos">
                </div>
                <div class="product-detail">
                    <h3>Prato de Alumínio Fundo</h3>
                    
                    <table class="wholesale-table">
                        <tr><th>Quantidade</th><th>Preço Unid.</th></tr>
                        <tr><td>50 a 99 unids</td><td class="highlight-price">800 Kz</td></tr>
                        <tr><td>100 a 499 unids</td><td class="highlight-price">700 Kz</td></tr>
                        <tr><td>500+ unids</td><td class="highlight-price">600 Kz</td></tr>
                    </table>

                    <div class="order-zone">
                        <div class="qty-input-group">
                            <label>Quantidade:</label>
                            <input type="number" id="qty-prato" value="50" min="50" oninput="calcularPrato()">
                        </div>
                        <div class="live-total">
                            Preço Unitário: <span id="unit-prato">800 Kz</span><br>
                            Subtotal: <span id="total-prato" style="color: #ff6600; font-size: 16px;">40.000 Kz</span>
                        </div>
                        <button class="btn-order" onclick="enviarPedido('Prato de Alumínio', 'qty-prato')">
                            <i class="fab fa-whatsapp"></i> Pedir no Grosso
                        </button>
                    </div>
                </div>
            </div>

            <!-- PRODUTO 3: Canecas -->
            <div class="product-card">
                <div class="product-img">
                    <span class="moq-tag">Mínimo: 30 unids</span>
                    <img src="https://images.unsplash.com/photo-1514432324607-a09d9b4aefdd?auto=format&fit=crop&w=400&q=80" alt="Canecas">
                </div>
                <div class="product-detail">
                    <h3>Caneca de Alumínio com Asa</h3>
                    
                    <table class="wholesale-table">
                        <tr><th>Quantidade</th><th>Preço Unid.</th></tr>
                        <tr><td>30 a 99 unids</td><td class="highlight-price">1.100 Kz</td></tr>
                        <tr><td>100 a 299 unids</td><td class="highlight-price">950 Kz</td></tr>
                        <tr><td>300+ unids</td><td class="highlight-price">800 Kz</td></tr>
                    </table>

                    <div class="order-zone">
                        <div class="qty-input-group">
                            <label>Quantidade:</label>
                            <input type="number" id="qty-caneca" value="30" min="30" oninput="calcularCaneca()">
                        </div>
                        <div class="live-total">
                            Preço Unitário: <span id="unit-caneca">1.100 Kz</span><br>
                            Subtotal: <span id="total-caneca" style="color: #ff6600; font-size: 16px;">33.000 Kz</span>
                        </div>
                        <button class="btn-order" onclick="enviarPedido('Caneca de Alumínio', 'qty-caneca')">
                            <i class="fab fa-whatsapp"></i> Pedir no Grosso
                        </button>
                    </div>
                </div>
            </div>

        </div>
    </main>

    <!-- Rodapé -->
    <footer>
        <div class="footer-grid">
            <div class="footer-col">
                <h4>AluAngola Co.</h4>
                <p>O teu parceiro B2B de confiança em Luanda. Fabricação própria e distribuição em grande escala.</p>
            </div>
            <div class="footer-col">
                <h4>Condições Comerciais</h4>
                <ul>
                    <li><i class="fas fa-check-circle"></i> Pagamento por IBAN ou Express</li>
                    <li><i class="fas fa-check-circle"></i> Descontos automáticos por volume</li>
                    <li><i class="fas fa-check-circle"></i> Levantamento no Armazém ou Envio</li>
                </ul>
            </div>
            <div class="footer-col">
                <h4>Contacto de Fábrica</h4>
                <p><i class="fas fa-phone"></i> Terminal Técnico: +244 900 000 000</p>
                <p><i class="fas fa-map-marker-alt"></i> Luanda, Angola</p>
            </div>
        </div>
        <div class="footer-bottom">
            <p>&copy; 2026 AluAngola Marketplace. Pronto a operar.</p>
        </div>
    </footer>

    <!-- Lógica de Cálculo e Envio Automático -->
    <script>
        // O TEU NÚMERO DE WHATSAPP (Coloca o teu número real aqui com o código 244)
        const SEU_WHATSAPP = "244900000000";

        function formatarMoeda(valor) {
            return valor.toLocaleString('pt-PT') + " Kz";
        }

        function calcularForma() {
            let qty = parseInt(document.getElementById('qty-forma').value) || 0;
            let precoUnit = 2000;
            if (qty >= 30 && qty < 100) precoUnit = 1700;
            else if (qty >= 100) precoUnit = 1400;

            let total = qty * precoUnit;
            document.getElementById('unit-forma').innerText = formatarMoeda(precoUnit);
            document.getElementById('total-forma').innerText = formatarMoeda(total);
        }

        function calcularPrato() {
            let qty = parseInt(document.getElementById('qty-prato').value) || 0;
            let precoUnit = 800;
            if (qty >= 100 && qty < 500) precoUnit = 700;
            else if (qty >= 500) precoUnit = 600;

            let total = qty * precoUnit;
            document.getElementById('unit-prato').innerText = formatarMoeda(precoUnit);
            document.getElementById('total-prato').innerText = formatarMoeda(total);
        }

        function calcularCaneca() {
            let qty = parseInt(document.getElementById('qty-caneca').value) || 0;
            let precoUnit = 1100;
            if (qty >= 100 && qty < 300) precoUnit = 950;
            else if (qty >= 300) precoUnit = 800;

            let total = qty * precoUnit;
            document.getElementById('unit-caneca').innerText = formatarMoeda(precoUnit);
            document.getElementById('total-caneca').innerText = formatarMoeda(total);
        }

        function enviarPedido(nomeProduto, inputId) {
            let qty = document.getElementById(inputId).value;
            
            // Obter os valores calculados diretamente da tela
            let sufixo = inputId.split('-')[1];
            let precoUnitario = document.getElementById('unit-' + sufixo).innerText;
            let subtotal = document.getElementById('total-' + sufixo).innerText;

            // Monta o texto no padrão profissional B2B
            let mensagem = `Olá AluAngola!\n\nGostaria de solicitar a seguinte ordem de atacado:\n\n` +
                           `📦 *Produto:* ${nomeProduto}\n` +
                           `🔢 *Quantidade:* ${qty} unidades\n` +
                           `💰 *Preço Unitário Aplicado:* ${precoUnitario}\n` +
                           `📊 *Total Estimado:* ${subtotal}\n\n` +
                           `Por favor, confirmem a disponibilidade de stock e os dados para pagamento via IBAN.`;

            // Abre a API do WhatsApp
            let url = `https://wa.me/${SEU_WHATSAPP}?text=${encodeURIComponent(mensagem)}`;
            window.open(url, '_blank');
        }
    </script>
</body>
</html>
