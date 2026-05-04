<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Neuro Suplementos</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }

    body {
      font-family: Arial, sans-serif;
      background: #f4f4f4;
      color: #222;
    }

    /* ===== HEADER ===== */
    .header {
      background: #1a1a2e;
      padding: 1rem 2rem;
      display: flex;
      align-items: center;
      justify-content: space-between;
      border-bottom: 2px solid #1a24e2;
    }
    .logo { font-size: 22px; font-weight: bold; color: #fff; letter-spacing: 1px; }
    .logo span { color: #1a24e2; }

    nav a {
      color: #ccc;
      text-decoration: none;
      margin-left: 1.5rem;
      font-size: 14px;
      transition: color 0.2s;
    }
    nav a:hover { color: #1a24e2; }

    .cart-btn {
      background: #1a24e2;
      color: #fff;
      border: none;
      padding: 8px 16px;
      border-radius: 6px;
      font-size: 14px;
      cursor: pointer;
    }
    .cart-count {
      background: #fff;
      color: #1a24e2;
      border-radius: 50%;
      width: 18px; height: 18px;
      font-size: 11px;
      font-weight: bold;
      display: inline-flex;
      align-items: center;
      justify-content: center;
      margin-left: 6px;
    }

    /* ===== HERO ===== */
    .hero {
      background: linear-gradient(135deg, #1a1a2e 0%, #16213e 60%, #0f3460 100%);
      padding: 4rem 2rem;
      text-align: center;
      color: #fff;
    }
    .hero h1 { font-size: 36px; margin-bottom: 1rem; }
    .hero h1 span { color: #1a24e2; }
    .hero p { font-size: 16px; color: #aaa; max-width: 480px; margin: 0 auto 1.5rem; }
    .hero-btn {
      background: #1a24e2;
      color: #fff;
      border: none;
      padding: 12px 30px;
      border-radius: 6px;
      font-size: 15px;
      cursor: pointer;
    }
    .hero-btn:hover { background: #1a24e2; }

    /* ===== SEÇÃO PRODUTOS ===== */
    .section { padding: 2rem; max-width: 1100px; margin: 0 auto; }
    .section-title { font-size: 22px; font-weight: bold; margin-bottom: 1.25rem; }
    .section-title span { color: #1a24e2; }

    /* ===== FILTROS ===== */
    .filters { display: flex; gap: 8px; flex-wrap: wrap; margin-bottom: 1.5rem; }
    .filter-btn {
      background: #fff;
      border: 1px solid #ddd;
      color: #555;
      padding: 6px 16px;
      border-radius: 20px;
      font-size: 13px;
      cursor: pointer;
      transition: all 0.2s;
    }
    .filter-btn.active, .filter-btn:hover {
      background: #1a24e2;
      color: #fff;
      border-color: #1a24e2;
    }

    /* ===== GRID DE PRODUTOS ===== */
    .products-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
      gap: 1rem;
    }

    .product-card {
      background: #fff;
      border: 1px solid #e5e5e5;
      border-radius: 12px;
      overflow: hidden;
      transition: transform 0.2s, box-shadow 0.2s;
    }
    .product-card:hover {
      transform: translateY(-4px);
      box-shadow: 0 8px 24px rgba(0,0,0,0.1);
    }

    .product-img {
      height: 140px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 52px;
    }

    .product-info { padding: 12px; }
    .product-cat {
      font-size: 11px;
      color: #1a24e2;
      font-weight: bold;
      text-transform: uppercase;
      letter-spacing: 0.5px;
      margin-bottom: 4px;
    }
    .badge {
      background: #22c55e;
      color: #fff;
      font-size: 10px;
      padding: 2px 7px;
      border-radius: 10px;
      margin-left: 6px;
      vertical-align: middle;
    }
    .product-name { font-size: 14px; font-weight: bold; margin-bottom: 6px; color: #222; }
    .product-desc { font-size: 12px; color: #777; margin-bottom: 10px; line-height: 1.5; }

    .product-footer { display: flex; align-items: center; justify-content: space-between; }
    .product-price { font-size: 16px; font-weight: bold; color: #1a24e2; }
    .add-btn {
      background: #1a24e2;
      color: #fff;
      border: none;
      padding: 6px 12px;
      border-radius: 6px;
      font-size: 12px;
      cursor: pointer;
      transition: background 0.2s;
    }
    .add-btn:hover { background: #1a24e2; }

    /* ===== CARRINHO LATERAL ===== */
    .cart-panel {
      display: none;
      position: fixed;
      top: 0; right: 0;
      width: 320px; height: 100%;
      background: #fff;
      border-left: 1px solid #e5e5e5;
      padding: 1.5rem;
      overflow-y: auto;
      z-index: 100;
      box-shadow: -4px 0 20px rgba(0,0,0,0.15);
    }
    .cart-panel.open { display: block; }
    .cart-panel h3 { font-size: 18px; font-weight: bold; margin-bottom: 1rem; }
    .close-cart { float: right; cursor: pointer; font-size: 20px; color: #999; }
    .close-cart:hover { color: #1a24e2; }

    .cart-item {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 8px 0;
      border-bottom: 1px solid #eee;
      font-size: 13px;
    }
    .cart-item-name { flex: 1; color: #222; }
    .cart-item-price { color: #1a24e2; font-weight: bold; margin: 0 10px; white-space: nowrap; }
    .remove-btn { color: #aaa; cursor: pointer; font-size: 16px; }
    .remove-btn:hover { color: #1a24e2; }

    .cart-total {
      margin-top: 1rem;
      font-size: 18px;
      font-weight: bold;
      color: #222;
      text-align: right;
    }

    /* ===== BOTÃO WHATSAPP ===== */
    .whatsapp-btn {
      width: 100%;
      background: #25d366;
      color: #fff;
      border: none;
      padding: 14px;
      border-radius: 8px;
      font-size: 15px;
      font-weight: bold;
      cursor: pointer;
      margin-top: 1rem;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 8px;
      transition: background 0.2s;
    }
    .whatsapp-btn:hover { background: #1ebe5d; }

    .whatsapp-info {
      margin-top: 10px;
      font-size: 12px;
      color: #888;
      text-align: center;
      line-height: 1.5;
    }

    .empty-cart { color: #aaa; font-size: 14px; text-align: center; padding: 2rem 0; }

    /* ===== TOAST (NOTIFICAÇÃO) ===== */
    .toast {
      position: fixed;
      bottom: 2rem; left: 50%;
      transform: translateX(-50%) translateY(20px);
      background: #22c55e;
      color: #fff;
      padding: 10px 20px;
      border-radius: 6px;
      font-size: 14px;
      opacity: 0;
      pointer-events: none;
      transition: all 0.3s;
      z-index: 200;
    }
    .toast.show { opacity: 1; transform: translateX(-50%) translateY(0); }

    /* ===== SOBRE ===== */
    .sobre-section {
      background: #fff;
      padding: 3rem 2rem;
      text-align: center;
    }
    .sobre-grid {
      display: flex;
      justify-content: center;
      gap: 2rem;
      flex-wrap: wrap;
      margin-top: 1.5rem;
    }
    .sobre-item { max-width: 180px; text-align: center; }
    .sobre-item .icone { font-size: 36px; margin-bottom: 8px; }
    .sobre-item strong { display: block; margin-bottom: 4px; }
    .sobre-item p { font-size: 13px; color: #777; }

    /* ===== RODAPÉ ===== */
    footer {
      background: #1a1a2e;
      color: #aaa;
      text-align: center;
      padding: 1.5rem;
      font-size: 13px;
      margin-top: 3rem;
    }
    footer span { color: #1a24e2; }
  </style>
</head>
<body>

  <!-- CABEÇALHO -->
  <header class="header">
    <div class="logo">NEURO<span>BYTE</span></div>
    <nav>
      <a href="#produtos">Produtos</a>
      <a href="#sobre">Sobre</a>
      <a href="#contato">Contato</a>
    </nav>
    <button class="cart-btn" onclick="toggleCart()">
      🛒 Carrinho <span class="cart-count" id="cartCount">0</span>
    </button>
  </header>

  <!-- BANNER PRINCIPAL -->
  <section class="hero">
    <h1>Suplementos para <span>resultados reais</span></h1>
    <p>Qualidade premium para quem leva o treino a sério. Entrega rápida para todo o Brasil.</p>
    <button class="hero-btn" onclick="document.getElementById('produtos').scrollIntoView({behavior:'smooth'})">
      Ver produtos
    </button>
  </section>

  <!-- PRODUTOS -->
  <section class="section" id="produtos">
    <div class="section-title">Nossos <span>Produtos</span></div>

    <div class="filters">
      <button class="filter-btn active" onclick="filterProducts('todos', this)">Todos</button>
      <button class="filter-btn" onclick="filterProducts('proteína', this)">Proteína</button>
      <button class="filter-btn" onclick="filterProducts('pré-treino', this)">Pré-treino</button>
      <button class="filter-btn" onclick="filterProducts('vitamina', this)">Vitaminas</button>
      <button class="filter-btn" onclick="filterProducts('creatina', this)">Creatina</button>
    </div>

    <div class="products-grid" id="productsGrid"></div>
  </section>

  <!-- SOBRE -->
  <section class="sobre-section" id="sobre">
    <h2 style="font-size:24px; margin-bottom:0.5rem;">
      Por que escolher a <span style="color:#1a24e2;">NeuroByte</span>?
    </h2>
    <div class="sobre-grid">
      <div class="sobre-item">
        <div class="icone">🏆</div>
        <strong>Qualidade premium</strong>
        <p>Produtos testados e certificados</p>
      </div>
      <div class="sobre-item">
        <div class="icone">🚚</div>
        <strong>Entrega rápida</strong>
        <p>Para todo o Brasil em até 5 dias</p>
      </div>
      <div class="sobre-item">
        <div class="icone">💬</div>
        <strong>Suporte via WhatsApp</strong>
        <p>Atendimento rápido e humanizado</p>
      </div>
    </div>
  </section>

  <!-- CONTATO -->
  <section class="section" id="contato" style="text-align:center; padding-top: 2rem;">
    <div class="section-title">Entre em <span>contato</span></div>
    <p style="color:#777; margin-bottom:1rem;">Dúvidas? Fale com a gente!</p>
    <p>📧 contato@neurobyte.com.br</p>
    <p style="margin-top:6px;">📱 (11) 4002-0922</p>
  </section>

  <!-- CARRINHO LATERAL -->
  <div class="cart-panel" id="cartPanel">
    <span class="close-cart" onclick="toggleCart()">✕</span>
    <h3>🛒 Meu carrinho</h3>
    <div id="cartItems"></div>
    <div id="cartSummary"></div>
  </div>

  <!-- NOTIFICAÇÃO -->
  <div class="toast" id="toast"></div>

  <!-- RODAPÉ -->
  <footer>
    <p>© 2025 <span>ForceMax</span> Suplementos — Todos os direitos reservados.</p>
  </footer>

  <script>
    // ============================================================
    // ⚠️ COLOQUE O SEU NÚMERO DE WHATSAPP AQUI (só números)
    // Formato: 55 + DDD + número
    // Exemplo: "5511999990000"  →  55 (Brasil) + 11 (DDD) + número
    // ============================================================
    const WHATSAPP_NUMERO = "5511991414943";

    // ============================================================
    // LISTA DE PRODUTOS
    // ============================================================
    const products = [
      { id: 1, name: 'Whey Protein 900g',   cat: 'proteína',   price: 189.90, desc: 'Concentrado 80% proteína. Sabor chocolate.', emoji: '🥛', bg: '#e8f4fd', hot: true  },
      { id: 2, name: 'Whey Isolado 1kg',    cat: 'proteína',   price: 259.90, desc: 'Isolado 90%+ proteína. Zero lactose.',        emoji: '🏋️', bg: '#f0e8fd', hot: false },
      { id: 3, name: 'Creatina Mono 300g',  cat: 'creatina',   price:  89.90, desc: 'Monohidratada pura. Força e recuperação.',    emoji: '⚡', bg: '#fff3e0', hot: true  },
      { id: 4, name: 'Pré-Treino Extreme',  cat: 'pré-treino', price: 129.90, desc: 'Energia e foco máximo. 40 doses.',            emoji: '🔥', bg: '#fce8e8', hot: false },
      { id: 5, name: 'Vitamina C 1000mg',   cat: 'vitamina',   price:  49.90, desc: 'Imunidade reforçada. 60 cápsulas.',           emoji: '🍊', bg: '#fff9e6', hot: false },
      { id: 6, name: 'Multivitamínico',     cat: 'vitamina',   price:  69.90, desc: '19 vitaminas e minerais. 60 comprimidos.',    emoji: '💊', bg: '#e8fdf0', hot: false },
      { id: 7, name: 'BCAA 4:1:1 200g',    cat: 'proteína',   price:  79.90, desc: 'Aminoácidos essenciais. Recuperação.',        emoji: '💪', bg: '#fdf0e8', hot: false },
      { id: 8, name: 'Pré-Treino Pump',     cat: 'pré-treino', price: 109.90, desc: 'Vasodilatação intensa. Sabor frutas.',        emoji: '🎯', bg: '#f5e8fd', hot: false },
    ];

    let cart = [];

    // ============================================================
    // RENDERIZAR PRODUTOS
    // ============================================================
    function renderProducts(filter) {
      const grid = document.getElementById('productsGrid');
      const lista = (filter === 'todos') ? products : products.filter(p => p.cat === filter);

      grid.innerHTML = lista.map(p => `
        <div class="product-card">
          <div class="product-img" style="background:${p.bg}">${p.emoji}</div>
          <div class="product-info">
            <div class="product-cat">
              ${p.cat}
              ${p.hot ? '<span class="badge">popular</span>' : ''}
            </div>
            <div class="product-name">${p.name}</div>
            <div class="product-desc">${p.desc}</div>
            <div class="product-footer">
              <div class="product-price">R$ ${p.price.toFixed(2).replace('.', ',')}</div>
              <button class="add-btn" onclick="addToCart(${p.id})">+ Adicionar</button>
            </div>
          </div>
        </div>
      `).join('');
    }

    // ============================================================
    // FILTRAR POR CATEGORIA
    // ============================================================
    function filterProducts(cat, btn) {
      document.querySelectorAll('.filter-btn').forEach(b => b.classList.remove('active'));
      btn.classList.add('active');
      renderProducts(cat);
    }

    // ============================================================
    // ADICIONAR AO CARRINHO
    // ============================================================
    function addToCart(id) {
      const produto = products.find(p => p.id === id);
      cart.push(produto);
      document.getElementById('cartCount').textContent = cart.length;
      showToast('✅ ' + produto.name + ' adicionado!');
      renderCart();
    }

    // ============================================================
    // REMOVER DO CARRINHO
    // ============================================================
    function removeFromCart(index) {
      cart.splice(index, 1);
      document.getElementById('cartCount').textContent = cart.length;
      renderCart();
    }

    // ============================================================
    // RENDERIZAR CARRINHO
    // ============================================================
    function renderCart() {
      const container = document.getElementById('cartItems');
      const summary   = document.getElementById('cartSummary');

      if (cart.length === 0) {
        container.innerHTML = '<div class="empty-cart">Seu carrinho está vazio.</div>';
        summary.innerHTML = '';
        return;
      }

      container.innerHTML = cart.map((item, i) => `
        <div class="cart-item">
          <span class="cart-item-name">${item.emoji} ${item.name}</span>
          <span class="cart-item-price">R$ ${item.price.toFixed(2).replace('.', ',')}</span>
          <span class="remove-btn" onclick="removeFromCart(${i})">✕</span>
        </div>
      `).join('');

      const total = cart.reduce((soma, item) => soma + item.price, 0);

      summary.innerHTML = `
        <div class="cart-total">Total: R$ ${total.toFixed(2).replace('.', ',')}</div>

        <button class="whatsapp-btn" onclick="finalizarPedido()">
          <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="white">
            <path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"/>
          </svg>
          Finalizar pelo WhatsApp
        </button>

        <p class="whatsapp-info">
          Você será redirecionado para o WhatsApp com o seu pedido já preenchido.
          Nossa equipe confirmará o pagamento e o envio.
        </p>
      `;
    }

    // ============================================================
    // FINALIZAR PEDIDO VIA WHATSAPP
    // ============================================================
    function finalizarPedido() {
      if (cart.length === 0) return;

      // Monta a lista de itens
      const itens = cart.map((item, i) =>
        `${i + 1}. ${item.name} — R$ ${item.price.toFixed(2).replace('.', ',')}`
      ).join('\n');

      const total = cart.reduce((soma, item) => soma + item.price, 0);

      // Monta a mensagem completa
      const mensagem =
        `Olá! Gostaria de fazer um pedido na NeuroByte 💪\n\n` +
        `*Meu pedido:*\n${itens}\n\n` +
        `*Total: R$ ${total.toFixed(2).replace('.', ',')}*\n\n` +
        `Por favor, me informe sobre formas de pagamento e prazo de entrega. Obrigado!`;

      // Codifica a mensagem para URL e abre o WhatsApp
      const url = `https://wa.me/${WHATSAPP_NUMERO}?text=${encodeURIComponent(mensagem)}`;
      window.open(url, '_blank');
    }

    // ============================================================
    // ABRIR / FECHAR CARRINHO
    // ============================================================
    function toggleCart() {
      document.getElementById('cartPanel').classList.toggle('open');
      renderCart();
    }

    // ============================================================
    // NOTIFICAÇÃO (TOAST)
    // ============================================================
    function showToast(msg) {
      const t = document.getElementById('toast');
      t.textContent = msg;
      t.classList.add('show');
      setTimeout(() => t.classList.remove('show'), 2200);
    }

    // Carrega os produtos ao abrir a página
    renderProducts('todos');
  </script>

</body>
</html>
