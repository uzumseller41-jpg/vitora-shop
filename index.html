<!DOCTYPE html>
<html lang="uz">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
  <title>Vitora | Smart Pharm</title>
  <script src="https://telegram.org/js/telegram-web-app.js"></script>
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif; }
    body { background: #0b1120; color: #f8fafc; padding-bottom: 84px; }
    .container { max-width: 520px; margin: 0 auto; padding: 16px; }
    .greeting { font-size: 13px; color: #94a3b8; }
    .username { font-size: 22px; font-weight: 800; text-transform: uppercase; margin: 2px 0 14px; }
    .bonus-card {
      background: linear-gradient(135deg, #1d4ed8, #2563eb 60%, #3b82f6);
      border-radius: 18px; padding: 18px 20px; margin-bottom: 18px;
      box-shadow: 0 10px 25px rgba(37, 99, 235, 0.35);
    }
    .bonus-label { font-size: 11px; letter-spacing: 1px; opacity: 0.85; font-weight: 700; }
    .bonus-val { font-size: 32px; font-weight: 800; margin: 4px 0 2px; }
    .bonus-sub { font-size: 13px; opacity: 0.9; display: flex; justify-content: space-between; }
    .search-box {
      width: 100%; background: #1e293b; border: 1px solid #334155; color: #fff;
      padding: 12px 14px; border-radius: 12px; font-size: 14px; margin-bottom: 12px; outline: none;
    }
    .cats { display: flex; gap: 8px; overflow-x: auto; padding-bottom: 10px; margin-bottom: 12px; scrollbar-width: none; }
    .cats::-webkit-scrollbar { display: none; }
    .cat-btn {
      background: #1e293b; color: #cbd5e1; border: 1px solid #334155;
      padding: 7px 13px; border-radius: 20px; font-size: 12px; white-space: nowrap; cursor: pointer;
    }
    .cat-btn.active { background: #2563eb; color: #fff; border-color: #2563eb; font-weight: 600; }
    .section-title { font-size: 17px; font-weight: 700; margin-bottom: 12px; }
    .grid { display: grid; grid-template-columns: repeat(2, 1fr); gap: 12px; }
    .card {
      background: #111827; border: 1px solid #1e293b; border-radius: 16px;
      padding: 12px; display: flex; flex-direction: column; justify-content: space-between;
    }
    .img-wrap {
      background: #fff; border-radius: 12px; height: 110px; display: flex;
      align-items: center; justify-content: center; position: relative; margin-bottom: 10px; overflow: hidden;
    }
    .img-wrap img { max-height: 95%; max-width: 95%; object-fit: contain; }
    .badge-id {
      position: absolute; top: 6px; left: 6px; background: #0f172a; color: #fff;
      font-size: 10px; font-weight: 700; padding: 2px 7px; border-radius: 8px; z-index: 2;
    }
    .p-name { font-size: 12px; font-weight: 700; line-height: 1.35; margin-bottom: 4px; color: #f1f5f9; }
    .p-cat { font-size: 11px; color: #60a5fa; margin-bottom: 4px; }
    .p-desc { font-size: 10px; color: #94a3b8; line-height: 1.3; margin-bottom: 6px; }
    .p-stock { font-size: 11px; color: #34d399; margin-bottom: 8px; font-weight: 600; }
    .p-stock.out { color: #f87171; }
    .card-bottom { display: flex; align-items: center; justify-content: space-between; margin-top: auto; }
    .p-price { font-size: 13px; font-weight: 800; color: #fff; }
    .add-btn {
      background: #2563eb; color: #fff; border: none; width: 30px; height: 30px;
      border-radius: 10px; font-size: 18px; font-weight: 700; cursor: pointer;
    }
    .add-btn:disabled { background: #334155; cursor: not-allowed; }
    .qty-ctrl { display: flex; align-items: center; gap: 6px; background: #1e293b; border-radius: 10px; padding: 3px 6px; }
    .qty-ctrl button { background: none; border: none; color: #fff; font-size: 16px; font-weight: 700; width: 20px; cursor: pointer; }
    .cart-item {
      background: #111827; border: 1px solid #1e293b; border-radius: 14px;
      padding: 12px; margin-bottom: 10px; display: flex; justify-content: space-between; align-items: center; gap: 10px;
    }
    .total-row {
      display: flex; justify-content: space-between; font-size: 18px; font-weight: 800;
      padding: 14px 0; border-top: 1px solid #1e293b; margin-top: 8px;
    }
    .form-box { background: #111827; border: 1px solid #1e293b; border-radius: 16px; padding: 14px; margin-top: 10px; }
    .form-title { font-size: 15px; font-weight: 700; margin-bottom: 12px; }
    label { display: block; font-size: 12px; color: #94a3b8; margin: 10px 0 5px; }
    input, select {
      width: 100%; background: #0f172a; border: 1px solid #334155; color: #fff;
      padding: 11px 12px; border-radius: 10px; font-size: 14px; outline: none;
    }
    .card-pay-box {
      display: none; background: #172554; border: 1px solid #2563eb;
      border-radius: 12px; padding: 12px; margin-top: 10px;
    }
    .card-num-row { display: flex; justify-content: space-between; align-items: center; margin-top: 6px; }
    .card-digits { font-size: 15px; font-weight: 800; letter-spacing: 0.5px; color: #93c5fd; }
    .copy-btn {
      background: #2563eb; color: #fff; border: none; padding: 6px 12px;
      border-radius: 8px; font-size: 12px; font-weight: 600; cursor: pointer;
    }
    .submit-btn {
      width: 100%; background: #2563eb; color: #fff; border: none; padding: 14px;
      border-radius: 12px; font-size: 15px; font-weight: 700; margin-top: 16px; cursor: pointer;
    }
    .submit-btn:disabled { opacity: 0.6; }
    .bottom-nav {
      position: fixed; bottom: 0; left: 0; right: 0; background: #0f172a;
      border-top: 1px solid #1e293b; display: flex; justify-content: space-around; padding: 8px 0 12px; z-index: 50;
    }
    .nav-item {
      background: none; border: none; color: #64748b; font-size: 11px;
      display: flex; flex-direction: column; align-items: center; gap: 3px; cursor: pointer; position: relative;
    }
    .nav-item.active { color: #3b82f6; font-weight: 700; }
    .nav-icon { font-size: 20px; }
    .cart-badge {
      position: absolute; top: -2px; right: -8px; background: #ef4444; color: #fff;
      font-size: 10px; font-weight: 700; padding: 1px 5px; border-radius: 10px;
    }
    .tab-page { display: none; }
    .tab-page.active { display: block; }
    .info-card { background: #111827; border: 1px solid #1e293b; border-radius: 14px; padding: 14px; margin-bottom: 10px; }
  </style>
</head>
<body>
  <div class="container">
    <!-- TAB 1: ASOSIY -->
    <div id="tab-home" class="tab-page active">
      <div class="greeting" id="greetingText">Хайрли кун</div>
      <div class="username" id="userName">МИЖОЗ</div>
      <div class="bonus-card">
        <div class="bonus-label">БОНУС</div>
        <div class="bonus-val">5 000 <span style="font-size:16px;font-weight:500;">сўм</span></div>
        <div class="bonus-sub">
          <span id="userCardId">ID: VTR-00000001</span>
          <span>Даража: Бронза</span>
        </div>
      </div>
      <input type="text" id="searchHome" class="search-box" placeholder="🔍 Дори ёки БАД номини излаш..." oninput="renderProducts()" />
      <div class="section-title">Оммабоп маҳсулотлар</div>
      <div id="homeGrid" class="grid">Юкланмоқда...</div>
    </div>

    <!-- TAB 2: KATALOG -->
    <div id="tab-catalog" class="tab-page">
      <div class="section-title">Категориялар ва Каталог</div>
      <input type="text" id="searchCat" class="search-box" placeholder="🔍 Каталогдан излаш..." oninput="renderProducts()" />
      <div id="catBar" class="cats"></div>
      <div id="catGrid" class="grid"></div>
    </div>

    <!-- TAB 3: BUYURTMALAR / SAVATCHA -->
    <div id="tab-cart" class="tab-page">
      <div class="section-title">Саватча ва Буюртма</div>
      <div id="cartList"></div>
      <div id="checkoutSection" style="display:none;">
        <div class="total-row">
          <span>Жами:</span>
          <span id="cartTotal">0 сўм</span>
        </div>
        <div class="form-box">
          <div class="form-title">Буюртма маълумотлари</div>

          <label>Телефон рақами *</label>
          <input type="tel" id="phoneInput" placeholder="+998 90 123 45 67" />

          <label>Қабул қилиш усули</label>
          <select id="deliveryType" onchange="toggleAddress()">
            <option value="Етказиб бериш (Доставка)">Етказиб бериш (Доставка)</option>
            <option value="Дорихонадан олиб кетиш (Самовывоз)">Дорихонадан олиб кетиш (Самовывоз)</option>
          </select>

          <div id="addressWrap">
            <label>Манзил</label>
            <input type="text" id="addressInput" placeholder="Самарқанд, кўча, уй/мўлжал" />
          </div>

          <label>Тўлов усули *</label>
          <select id="paymentMethod" onchange="toggleCardBox()">
            <option value="Нақд пул">💵 Нақд пул</option>
            <option value="Click">💳 Click (картага ўтказма)</option>
            <option value="Payme">💳 Payme (картага ўтказма)</option>
          </select>

          <div id="cardPayBox" class="card-pay-box">
            <div style="font-size:12px; color:#cbd5e1;">Тўлов учун Humo карта рақами:</div>
            <div class="card-num-row">
              <span class="card-digits" id="cardNumberText">9860 1501 1189 2918</span>
              <button type="button" class="copy-btn" onclick="copyCard()">Нусхалаш</button>
            </div>
            <div style="font-size:11px; color:#94a3b8; margin-top:6px;">Тўлов чекини ботга юборинг.</div>
          </div>

          <button type="button" class="submit-btn" id="submitBtn" onclick="submitOrder()">Буюртмани расмийлаштириш</button>
        </div>
      </div>
    </div>

    <!-- TAB 4: YANA -->
    <div id="tab-more" class="tab-page">
      <div class="section-title">Vitora | Smart Pharm</div>
      <div class="info-card">
        <b>📍 Филиалимиз:</b><br/>
        <span style="color:#94a3b8;font-size:13px;">Самарқанд шаҳри, асосий филиал.<br/>Иш вақти: 08:00 – 22:00</span>
      </div>
      <div class="info-card">
        <b>💳 Тўлов картаси (Click / Payme):</b><br/>
        <span style="color:#60a5fa;font-size:14px;font-weight:700;">9860 1501 1189 2918</span>
      </div>
    </div>
  </div>

  <!-- PASTKI MENYU -->
  <div class="bottom-nav">
    <button class="nav-item active" onclick="switchTab('home', this)">
      <span class="nav-icon">🏠</span><span>Асосий</span>
    </button>
    <button class="nav-item" onclick="switchTab('catalog', this)">
      <span class="nav-icon">📦</span><span>Каталог</span>
    </button>
    <button class="nav-item" onclick="switchTab('cart', this)">
      <span class="nav-icon">🛍</span><span>Буюртмалар</span>
      <span class="cart-badge" id="cartBadge" style="display:none;">0</span>
    </button>
    <button class="nav-item" onclick="switchTab('more', this)">
      <span class="nav-icon">•••</span><span>Яна</span>
    </button>
  </div>

  <script>
    const API_BASE = "https://vitora-bot.onrender.com";
    const tg = window.Telegram && window.Telegram.WebApp ? window.Telegram.WebApp : null;
    if (tg) { tg.expand(); tg.ready(); }

    // Soatga qarab salomlashish
    const hour = new Date().getHours();
    let greet = "Хайрли кеч";
    if (hour >= 5 && hour < 12) greet = "Хайрли тонг";
    else if (hour >= 12 && hour < 18) greet = "Хайрли кун";
    document.getElementById("greetingText").textContent = greet;

    const tgUser = tg && tg.initDataUnsafe && tg.initDataUnsafe.user ? tg.initDataUnsafe.user : {};
    const userId = tgUser.id || 0;
    const fullName = [tgUser.first_name, tgUser.last_name].filter(Boolean).join(" ") || "Мижоз";
    const username = tgUser.username || "yoq";
    const cardId = "VTR-" + Math.abs(userId || 1).toString(16).toUpperCase().padStart(8, "0").slice(0, 8);

    document.getElementById("userName").textContent = fullName;
    document.getElementById("userCardId").textContent = "ID: " + cardId;

    let products = [];
    let cart = {};
    let selectedCategory = "Барчаси";

    function switchTab(tabName, btn) {
      document.querySelectorAll(".tab-page").forEach(p => p.classList.remove("active"));
      document.querySelectorAll(".nav-item").forEach(b => b.classList.remove("active"));
      document.getElementById("tab-" + tabName).classList.add("active");
      btn.classList.add("active");
      if (tabName === "cart") renderCart();
    }

    function toggleAddress() {
      const val = document.getElementById("deliveryType").value;
      document.getElementById("addressWrap").style.display = val.includes("Самовывоз") ? "none" : "block";
    }

    function toggleCardBox() {
      const pm = document.getElementById("paymentMethod").value;
      document.getElementById("cardPayBox").style.display = (pm === "Click" || pm === "Payme") ? "block" : "none";
    }

    function copyCard() {
      navigator.clipboard.writeText("9860150111892918");
      alert("Карта рақами нусхаланди: 9860 1501 1189 2918");
    }

    async function loadProducts() {
      try {
        const res = await fetch(API_BASE + "/api/products?t=" + Date.now());
        const data = await res.json();
        products = data.products || [];
        buildCategories();
        renderProducts();
      } catch (e) {
        document.getElementById("homeGrid").textContent = "Сервер билан алоқа узилди. Қайта урининг.";
      }
    }

    function buildCategories() {
      const cats = ["Барчаси", ...new Set(products.map(p => p.category).filter(Boolean))];
      const bar = document.getElementById("catBar");
      bar.innerHTML = cats.map(c =>
        `<button class="cat-btn ${c === selectedCategory ? 'active' : ''}" onclick="selectCat('${c.replace(/'/g, "\\'")}')">${c}</button>`
      ).join("");
    }

    function selectCat(cat) {
      selectedCategory = cat;
      buildCategories();
      renderProducts();
    }

    function getCategoryVisual(cat, name) {
      const text = ((cat || "") + " " + (name || "")).toLowerCase();
      if (text.includes("омега") || text.includes("рыб")) return { icon: "🐟", bg: "linear-gradient(135deg,#fef3c7,#fde68a)", label: "OMEGA-3" };
      if (text.includes("дет") || text.includes("кидс") || text.includes("бэби")) return { icon: "🧸", bg: "linear-gradient(135deg,#fce7f3,#fbcfe8)", label: "KIDS" };
      if (text.includes("сироп") || text.includes("масло") || text.includes("экстракт") || text.includes("фито") || text.includes("трав") || text.includes("чай")) return { icon: "🌿", bg: "linear-gradient(135deg,#dcfce7,#bbf7d0)", label: "PHYTO" };
      if (text.includes("сустав") || text.includes("кост") || text.includes("кальц") || text.includes("коллаген")) return { icon: "🦴", bg: "linear-gradient(135deg,#e0e7ff,#c7d2fe)", label: "OSTEO" };
      if (text.includes("магн") || text.includes("цинк") || text.includes("желез") || text.includes("минерал") || text.includes("селен")) return { icon: "💎", bg: "linear-gradient(135deg,#cffafe,#a5f3fc)", label: "MINERAL" };
      if (text.includes("иммун") || text.includes("вит с") || text.includes("витамин с") || text.includes("вит d") || text.includes("витамин d")) return { icon: "🛡️", bg: "linear-gradient(135deg,#ffedd5,#fed7aa)", label: "IMMUNO" };
      if (text.includes("желуд") || text.includes("пищевар") || text.includes("пробио") || text.includes("лакто") || text.includes("бифидо")) return { icon: "🧬", bg: "linear-gradient(135deg,#f3e8ff,#e9d5ff)", label: "BIO" };
      return { icon: "💊", bg: "linear-gradient(135deg,#dbeafe,#bfdbfe)", label: "VITAMIN" };
    }

    function cardHTML(p) {
      const qty = cart[p.id] || 0;
      const inStock = (p.stock || 0) > 0;
      const vis = getCategoryVisual(p.category, p.name);
      const imgBlock = p.image
        ? `<img src="${p.image}" alt="${p.name}" />`
        : `<div style="width:100%;height:100%;background:${vis.bg};display:flex;flex-direction:column;align-items:center;justify-content:center;">
             <div style="font-size:40px;line-height:1;">${vis.icon}</div>
             <div style="font-size:10px;font-weight:800;color:#1e293b;margin-top:4px;letter-spacing:0.8px;">${vis.label}</div>
           </div>`;
      const actionBlock = qty > 0
        ? `<div class="qty-ctrl">
             <button onclick="changeQty(${p.id}, -1)">−</button>
             <span>${qty}</span>
             <button onclick="changeQty(${p.id}, 1)">+</button>
           </div>`
        : `<button class="add-btn" ${inStock ? "" : "disabled"} onclick="changeQty(${p.id}, 1)">+</button>`;

      return `
        <div class="card">
          <div>
            <div class="img-wrap">
              <span class="badge-id">${p.id}</span>
              ${imgBlock}
            </div>
            <div class="p-name">${p.name}</div>
            <div class="p-cat">${p.category || ""}</div>
            <div class="p-desc">${p.description || ""}</div>
          </div>
          <div>
            <div class="p-stock ${inStock ? "" : "out"}">${inStock ? "Қолдиқ: " + p.stock + " дона" : "Тугаган"}</div>
            <div class="card-bottom">
              <div class="p-price">${Number(p.price).toLocaleString()} сўм</div>
              ${actionBlock}
            </div>
          </div>
        </div>
      `;
    }

    function renderProducts() {
      const qHome = (document.getElementById("searchHome").value || "").toLowerCase();
      const qCat = (document.getElementById("searchCat").value || "").toLowerCase();

      const homeFiltered = products.filter(p => p.name.toLowerCase().includes(qHome)).slice(0, 40);
      document.getElementById("homeGrid").innerHTML = homeFiltered.length
        ? homeFiltered.map(cardHTML).join("")
        : "<div style='color:#94a3b8;'>Маҳсулот топилмади</div>";

      const catFiltered = products.filter(p => {
        const matchCat = selectedCategory === "Барчаси" || p.category === selectedCategory;
        const matchQ = p.name.toLowerCase().includes(qCat);
        return matchCat && matchQ;
      });
      document.getElementById("catGrid").innerHTML = catFiltered.length
        ? catFiltered.map(cardHTML).join("")
        : "<div style='color:#94a3b8;'>Маҳсулот топилмади</div>";
    }

    function changeQty(pid, delta) {
      const prod = products.find(x => x.id === pid);
      if (!prod) return;
      const next = (cart[pid] || 0) + delta;
      if (next <= 0) delete cart[pid];
      else if (next <= prod.stock) cart[pid] = next;
      else alert("Омборда фақат " + prod.stock + " дона бор!");

      updateBadge();
      renderProducts();
      renderCart();
    }

    function updateBadge() {
      const totalCount = Object.values(cart).reduce((a, b) => a + b, 0);
      const badge = document.getElementById("cartBadge");
      badge.style.display = totalCount > 0 ? "inline-block" : "none";
      badge.textContent = totalCount;
    }

    function renderCart() {
      const ids = Object.keys(cart).map(Number);
      const list = document.getElementById("cartList");
      const sec = document.getElementById("checkoutSection");

      if (!ids.length) {
        list.innerHTML = "<div class='info-card' style='color:#94a3b8;text-align:center;'>Саватчангиз ҳозирча бўш.</div>";
        sec.style.display = "none";
        return;
      }

      let total = 0;
      list.innerHTML = ids.map(id => {
        const p = products.find(x => x.id === id);
        if (!p) return "";
        const qty = cart[id];
        total += p.price * qty;
        return `
          <div class="cart-item">
            <div style="flex:1;">
              <div style="font-size:13px;font-weight:700;">${p.name}</div>
              <div style="font-size:12px;color:#60a5fa;margin-top:3px;">${Number(p.price).toLocaleString()} сўм</div>
            </div>
            <div class="qty-ctrl">
              <button onclick="changeQty(${p.id}, -1)">−</button>
              <span>${qty}</span>
              <button onclick="changeQty(${p.id}, 1)">+</button>
            </div>
          </div>
        `;
      }).join("");

      document.getElementById("cartTotal").textContent = total.toLocaleString() + " сўм";
      sec.style.display = "block";
    }

    async function submitOrder() {
      const phone = document.getElementById("phoneInput").value.trim();
      if (!phone) {
        alert("Илтимос, телефон рақамингизни киритинг!");
        return;
      }
      const delivery_type = document.getElementById("deliveryType").value;
      const address = document.getElementById("addressInput").value.trim();
      const payment_method = document.getElementById("paymentMethod").value;

      const ids = Object.keys(cart).map(Number);
      let total = 0;
      const cartArr = [];
      const lines = [];

      ids.forEach((id, idx) => {
        const p = products.find(x => x.id === id);
        if (!p) return;
        const qty = cart[id];
        const sub = p.price * qty;
        total += sub;
        cartArr.push({ id: p.id, qty });
        lines.push(`${idx + 1}. ${p.name} — ${qty} дона × ${p.price.toLocaleString()} = ${sub.toLocaleString()} сўм`);
      });

      const btn = document.getElementById("submitBtn");
      btn.disabled = true;
      btn.textContent = "Юборилмоқда...";

      try {
        const res = await fetch(API_BASE + "/api/order", {
          method: "POST",
          headers: { "Content-Type": "application/json" },
          body: JSON.stringify({
            user_id: userId,
            name: fullName,
            username: username,
            card: cardId,
            phone,
            delivery_type,
            address,
            payment_method,
            cart: cartArr,
            items: lines.join("\n"),
            total
          })
        });
        const data = await res.json();
        if (data.ok) {
          alert("✅ Буюртмангиз қабул қилинди! Тез орада оператор боғланади.");
          cart = {};
          updateBadge();
          await loadProducts();
          renderCart();
        } else {
          alert("Хатолик юз берди: " + (data.error || ""));
        }
      } catch (e) {
        alert("Серверга уланиб бўлмади.");
      } finally {
        btn.disabled = false;
        btn.textContent = "Буюртмани расмийлаштириш";
      }
    }

    loadProducts();
  </script>
</body>
</html>
