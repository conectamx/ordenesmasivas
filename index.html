<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Conecta MX — Generador de Órdenes Masivas</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=JetBrains+Mono:wght@400;600&display=swap');

  :root {
    --bg: #0f0f14;
    --surface: #1a1a24;
    --surface2: #22222f;
    --border: #2e2e3e;
    --accent: #7c6fff;
    --accent2: #a78bfa;
    --green: #34d399;
    --red: #f87171;
    --text: #e2e2f0;
    --muted: #6b6b8a;
    --fb: #1877f2;
    --ig: #e1306c;
  }

  * { box-sizing: border-box; margin: 0; padding: 0; }

  body {
    background: var(--bg);
    color: var(--text);
    font-family: 'Inter', sans-serif;
    min-height: 100vh;
    padding: 20px 16px 60px;
  }

  header {
    text-align: center;
    margin-bottom: 28px;
  }

  header h1 {
    font-size: 22px;
    font-weight: 700;
    letter-spacing: -0.5px;
    color: #fff;
  }

  header h1 span { color: var(--accent2); }

  header p {
    font-size: 13px;
    color: var(--muted);
    margin-top: 4px;
  }

  .card {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 14px;
    padding: 18px;
    margin-bottom: 14px;
  }

  .card-title {
    font-size: 11px;
    font-weight: 600;
    text-transform: uppercase;
    letter-spacing: 1px;
    color: var(--muted);
    margin-bottom: 14px;
  }

  /* Platform tabs */
  .tabs {
    display: flex;
    gap: 8px;
    margin-bottom: 14px;
  }

  .tab {
    flex: 1;
    padding: 10px;
    border-radius: 10px;
    border: 1.5px solid var(--border);
    background: transparent;
    color: var(--muted);
    font-size: 13px;
    font-weight: 600;
    cursor: pointer;
    transition: all 0.15s;
    font-family: 'Inter', sans-serif;
  }

  .tab.active-fb {
    border-color: var(--fb);
    background: rgba(24,119,242,0.12);
    color: #60a5fa;
  }

  .tab.active-ig {
    border-color: var(--ig);
    background: rgba(225,48,108,0.12);
    color: #f472b6;
  }

  /* Service grid */
  .service-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 8px;
  }

  .svc-btn {
    padding: 10px 8px;
    border-radius: 10px;
    border: 1.5px solid var(--border);
    background: var(--surface2);
    color: var(--text);
    font-size: 12px;
    font-weight: 500;
    cursor: pointer;
    text-align: left;
    transition: all 0.15s;
    font-family: 'Inter', sans-serif;
    line-height: 1.4;
  }

  .svc-btn:hover { border-color: var(--accent); }

  .svc-btn.selected {
    border-color: var(--accent);
    background: rgba(124,111,255,0.15);
    color: var(--accent2);
  }

  .svc-id {
    display: inline-block;
    background: var(--accent);
    color: #fff;
    font-size: 10px;
    font-weight: 700;
    border-radius: 4px;
    padding: 1px 5px;
    margin-bottom: 4px;
    font-family: 'JetBrains Mono', monospace;
  }

  .svc-btn.selected .svc-id { background: var(--accent2); }

  /* Links textarea */
  textarea {
    width: 100%;
    background: var(--surface2);
    border: 1.5px solid var(--border);
    border-radius: 10px;
    color: var(--text);
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    padding: 12px;
    resize: vertical;
    min-height: 100px;
    outline: none;
    transition: border-color 0.15s;
    line-height: 1.6;
  }

  textarea:focus { border-color: var(--accent); }
  textarea::placeholder { color: var(--muted); }

  /* Quantity */
  .qty-row {
    display: flex;
    gap: 8px;
    flex-wrap: wrap;
  }

  .qty-chip {
    padding: 7px 14px;
    border-radius: 20px;
    border: 1.5px solid var(--border);
    background: var(--surface2);
    color: var(--muted);
    font-size: 12px;
    font-weight: 600;
    cursor: pointer;
    transition: all 0.15s;
    font-family: 'Inter', sans-serif;
  }

  .qty-chip:hover, .qty-chip.selected {
    border-color: var(--accent);
    background: rgba(124,111,255,0.15);
    color: var(--accent2);
  }

  .qty-custom {
    flex: 1;
    min-width: 80px;
    padding: 7px 12px;
    border-radius: 20px;
    border: 1.5px solid var(--border);
    background: var(--surface2);
    color: var(--text);
    font-size: 12px;
    font-weight: 600;
    outline: none;
    font-family: 'Inter', sans-serif;
    transition: border-color 0.15s;
  }

  .qty-custom:focus { border-color: var(--accent); }
  .qty-custom::placeholder { color: var(--muted); }

  /* Generate button */
  .btn-generate {
    width: 100%;
    padding: 14px;
    border-radius: 12px;
    border: none;
    background: linear-gradient(135deg, var(--accent), var(--accent2));
    color: #fff;
    font-size: 15px;
    font-weight: 700;
    cursor: pointer;
    font-family: 'Inter', sans-serif;
    transition: opacity 0.15s, transform 0.1s;
    margin-bottom: 14px;
  }

  .btn-generate:active { transform: scale(0.98); }
  .btn-generate:disabled { opacity: 0.4; cursor: not-allowed; }

  /* Output */
  .output-box {
    background: var(--surface2);
    border: 1.5px solid var(--border);
    border-radius: 10px;
    padding: 14px;
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    line-height: 1.8;
    color: var(--green);
    white-space: pre-wrap;
    word-break: break-all;
    min-height: 60px;
    max-height: 280px;
    overflow-y: auto;
  }

  .output-empty {
    color: var(--muted);
    font-style: italic;
    font-family: 'Inter', sans-serif;
  }

  .output-meta {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 10px;
  }

  .output-meta span {
    font-size: 12px;
    color: var(--muted);
  }

  .btn-copy {
    padding: 6px 14px;
    border-radius: 8px;
    border: 1.5px solid var(--accent);
    background: transparent;
    color: var(--accent2);
    font-size: 12px;
    font-weight: 600;
    cursor: pointer;
    font-family: 'Inter', sans-serif;
    transition: all 0.15s;
  }

  .btn-copy:hover { background: rgba(124,111,255,0.15); }
  .btn-copy.copied { border-color: var(--green); color: var(--green); }

  /* Errors */
  .errors {
    background: rgba(248,113,113,0.1);
    border: 1px solid rgba(248,113,113,0.3);
    border-radius: 10px;
    padding: 12px;
    font-size: 12px;
    color: var(--red);
    margin-bottom: 14px;
    line-height: 1.6;
    display: none;
  }

  .svc-btn.preset-btn {
    grid-column: 1 / -1;
    background: rgba(124,111,255,0.08);
    border-color: var(--accent);
    color: var(--accent2);
    font-weight: 600;
  }

  .svc-btn.preset-btn.selected {
    background: rgba(124,111,255,0.25);
    border-color: var(--accent2);
  }

  .svc-btn.preset-btn .svc-id {
    background: linear-gradient(135deg, #7c6fff, #a78bfa);
  }


    font-size: 11px;
    color: var(--muted);
    margin-top: 8px;
    line-height: 1.5;
  }

  .multi-svc-note span { color: var(--accent2); }

  .divider {
    height: 1px;
    background: var(--border);
    margin: 14px 0;
  }

  /* Multi-service toggle */
  .multi-toggle {
    display: flex;
    align-items: center;
    gap: 10px;
    margin-top: 10px;
  }

  .toggle-label {
    font-size: 12px;
    color: var(--muted);
  }

  .toggle {
    position: relative;
    width: 36px;
    height: 20px;
  }

  .toggle input { opacity: 0; width: 0; height: 0; }

  .toggle-slider {
    position: absolute;
    inset: 0;
    background: var(--border);
    border-radius: 20px;
    cursor: pointer;
    transition: 0.2s;
  }

  .toggle-slider:before {
    content: '';
    position: absolute;
    width: 14px;
    height: 14px;
    left: 3px;
    top: 3px;
    background: #fff;
    border-radius: 50%;
    transition: 0.2s;
  }

  input:checked + .toggle-slider { background: var(--accent); }
  input:checked + .toggle-slider:before { transform: translateX(16px); }

</style>
</head>
<body>

<header>
  <h1>Conecta MX <span>— Órdenes Masivas</span></h1>
  <p>Genera el formato para el panel SMM en segundos</p>
</header>

<!-- PLATFORM -->
<div class="card">
  <div class="card-title">1 · Plataforma</div>
  <div class="tabs">
    <button class="tab active-fb" id="tab-fb" onclick="setPlatform('fb')">📘 Facebook</button>
    <button class="tab" id="tab-ig" onclick="setPlatform('ig')">📸 Instagram</button>
  </div>
</div>

<!-- SERVICE -->
<div class="card">
  <div class="card-title">2 · Servicio(s)</div>
  <div class="service-grid" id="service-grid"></div>
  <div class="multi-toggle">
    <label class="toggle">
      <input type="checkbox" id="multi-mode" onchange="renderServices()">
      <span class="toggle-slider"></span>
    </label>
    <span class="toggle-label">Selección múltiple</span>
  </div>
  <div class="multi-svc-note">Los servicios seleccionados se aplicarán a <span>todos los links</span> con la misma cantidad.</div>
</div>

<!-- LINKS -->
<div class="card">
  <div class="card-title">3 · Links (uno por línea)</div>
  <textarea id="links-input" placeholder="https://www.facebook.com/share/p/abc123/&#10;https://www.facebook.com/share/r/xyz789/&#10;..."></textarea>
</div>

<!-- QUANTITY -->
<div class="card">
  <div class="card-title">4 · Cantidad por servicio</div>
  <div class="qty-row" id="qty-chips">
    <button class="qty-chip" onclick="setQty(100)">100</button>
    <button class="qty-chip" onclick="setQty(200)">200</button>
    <button class="qty-chip" onclick="setQty(300)">300</button>
    <button class="qty-chip" onclick="setQty(500)">500</button>
    <button class="qty-chip" onclick="setQty(1000)">1K</button>
    <button class="qty-chip" onclick="setQty(2000)">2K</button>
    <input class="qty-custom" type="number" id="qty-custom" placeholder="Otra cantidad" oninput="setQtyCustom(this.value)">
  </div>
</div>

<!-- ERRORS -->
<div class="errors" id="errors"></div>

<!-- GENERATE -->
<button class="btn-generate" id="btn-gen" onclick="generate()">⚡ Generar orden masiva</button>

<!-- OUTPUT -->
<div class="card">
  <div class="output-meta">
    <span id="output-meta-text">—</span>
    <button class="btn-copy" id="btn-copy" onclick="copyOutput()">Copiar</button>
  </div>
  <div class="output-box" id="output"><span class="output-empty">Aquí aparecerá tu orden lista para pegar en el panel...</span></div>
</div>

<script>
// Preset especial: Reacciones Globales Variadas (51+52+57)
const PRESET_GLOBAL_VARIADAS = [51, 52, 57];

const SERVICES = {
  fb: [
    // PRESET especial
    { id: 'preset_global', label: '⚡ Globales Variadas\n(Likes + Love + Cares)', group: 'Presets', preset: PRESET_GLOBAL_VARIADAS },
    // Reacciones mundiales individuales
    { id: 51, label: 'Likes 👍', group: 'Global Individual' },
    { id: 52, label: 'Love ❤️', group: 'Global Individual' },
    { id: 53, label: 'Angry 😡', group: 'Global Individual' },
    { id: 54, label: 'Haha 🤣', group: 'Global Individual' },
    { id: 55, label: 'Wow 😮', group: 'Global Individual' },
    { id: 56, label: 'Sad 😢', group: 'Global Individual' },
    { id: 57, label: 'Cares 🥰', group: 'Global Individual' },
    // Reacciones MX
    { id: 4, label: 'Likes MX 👍', group: 'México' },
    { id: 5, label: 'Me encanta MX ❤️', group: 'México' },
    { id: 6, label: 'Me importa MX 🤗', group: 'México' },
    { id: 7, label: 'Me asombra MX 😮', group: 'México' },
    { id: 8, label: 'Me divierte MX 😆', group: 'México' },
    { id: 9, label: 'Me entristece MX 😢', group: 'México' },
    { id: 10, label: 'Me enoja MX 😡', group: 'México' },
    // Mixtas MX
    { id: 15, label: 'Mixtas MX 👍❤️', group: 'Mixtas MX' },
    { id: 16, label: 'Mixtas MX ❤️🤗', group: 'Mixtas MX' },
    { id: 17, label: 'Mixtas MX 👍❤️🤗😊', group: 'Mixtas MX' },
    { id: 18, label: 'Mixtas MX 😆😡', group: 'Mixtas MX' },
    // Vistas
    { id: 65, label: 'Vistas Reel', group: 'Vistas' },
    // Seguidores
    { id: 1, label: 'Seguidores MX', group: 'Seguidores' },
    { id: 71, label: 'Seguidores Globales', group: 'Seguidores' },
  ],
  ig: [
    { id: 38, label: 'Likes MX 🇲🇽', group: 'Likes' },
    { id: 50, label: 'Likes Asiáticos', group: 'Likes' },
    { id: 73, label: 'Likes Auto ⭐', group: 'Likes' },
    { id: 59, label: 'Visualizaciones', group: 'Vistas' },
    { id: 36, label: 'Seguidores MX 🇲🇽', group: 'Seguidores' },
    { id: 70, label: 'Seguidores Asiáticos', group: 'Seguidores' },
    { id: 72, label: 'Seg. Asiáticos Antiguos ⭐', group: 'Seguidores' },
  ]
};

let platform = 'fb';
let selectedServices = new Set();
let quantity = null;

function setPlatform(p) {
  platform = p;
  selectedServices.clear();
  document.getElementById('tab-fb').className = 'tab' + (p === 'fb' ? ' active-fb' : '');
  document.getElementById('tab-ig').className = 'tab' + (p === 'ig' ? ' active-ig' : '');
  renderServices();
  clearOutput();
}

function renderServices() {
  const multi = document.getElementById('multi-mode').checked;
  const grid = document.getElementById('service-grid');
  const svcs = SERVICES[platform];

  // Group by category
  const groups = {};
  svcs.forEach(s => {
    if (!groups[s.group]) groups[s.group] = [];
    groups[s.group].push(s);
  });

  let html = '';
  Object.entries(groups).forEach(([group, items]) => {
    html += `<div style="grid-column:1/-1;font-size:10px;font-weight:600;color:var(--muted);text-transform:uppercase;letter-spacing:1px;margin-top:8px;margin-bottom:2px;">${group}</div>`;
    items.forEach(s => {
      const sel = selectedServices.has(s.id) ? 'selected' : '';
      const isPreset = s.preset ? 'preset-btn' : '';
      const idLabel = s.preset ? s.preset.join('+') : s.id;
      const labelText = s.label.replace('\n', '<br>');
      html += `<button class="svc-btn ${sel} ${isPreset}" onclick="toggleService('${s.id}', ${multi})">
        <span class="svc-id">${idLabel}</span><br>${labelText}
      </button>`;
    });
  });

  grid.innerHTML = html;
}

function toggleService(id, multi) {
  // Convert numeric strings to numbers for real IDs
  const key = isNaN(id) ? id : Number(id);
  if (!multi) {
    selectedServices.clear();
    selectedServices.add(key);
  } else {
    if (selectedServices.has(key)) selectedServices.delete(key);
    else selectedServices.add(key);
  }
  renderServices();
  clearOutput();
}

function expandSelectedServices() {
  const allSvcs = SERVICES[platform];
  const expanded = [];
  selectedServices.forEach(id => {
    const svc = allSvcs.find(s => s.id === id);
    if (svc && svc.preset) {
      svc.preset.forEach(pid => { if (!expanded.includes(pid)) expanded.push(pid); });
    } else {
      if (!expanded.includes(id)) expanded.push(id);
    }
  });
  return expanded;
}

function setQty(val) {
  quantity = val;
  document.getElementById('qty-custom').value = '';
  document.querySelectorAll('.qty-chip').forEach(c => {
    c.classList.toggle('selected', parseInt(c.textContent.replace('K','000')) === val || c.textContent === val+'');
  });
  // fix 1K/2K
  document.querySelectorAll('.qty-chip').forEach(c => {
    const v = c.textContent === '1K' ? 1000 : c.textContent === '2K' ? 2000 : parseInt(c.textContent);
    c.classList.toggle('selected', v === val);
  });
}

function setQtyCustom(val) {
  quantity = val ? parseInt(val) : null;
  document.querySelectorAll('.qty-chip').forEach(c => c.classList.remove('selected'));
}

function clearOutput() {
  document.getElementById('output').innerHTML = '<span class="output-empty">Aquí aparecerá tu orden lista para pegar en el panel...</span>';
  document.getElementById('output-meta-text').textContent = '—';
  document.getElementById('btn-copy').classList.remove('copied');
  document.getElementById('btn-copy').textContent = 'Copiar';
  document.getElementById('errors').style.display = 'none';
}

function generate() {
  const errBox = document.getElementById('errors');
  errBox.style.display = 'none';
  const errors = [];

  if (selectedServices.size === 0) errors.push('• Selecciona al menos un servicio.');
  if (!quantity || quantity < 1) errors.push('• Ingresa una cantidad válida.');

  const rawLinks = document.getElementById('links-input').value;
  const links = rawLinks.split('\n')
    .map(l => l.trim().replace(/\s+/g, ''))
    .filter(l => l.length > 0);

  if (links.length === 0) errors.push('• Pega al menos un link.');

  // Detect invalid links
  const invalidLinks = links.filter(l => !l.startsWith('http'));
  if (invalidLinks.length > 0) {
    errors.push(`• Links con formato incorrecto (${invalidLinks.length}):\n  ${invalidLinks.join('\n  ')}`);
  }

  if (errors.length > 0) {
    errBox.textContent = errors.join('\n');
    errBox.style.display = 'block';
    return;
  }

  const validLinks = links.filter(l => l.startsWith('http'));
  const svcIds = expandSelectedServices();
  const lines = [];

  validLinks.forEach(link => {
    svcIds.forEach(id => {
      lines.push(`${id}|${link}|${quantity}`);
    });
  });

  const total = lines.length;
  const totalReactions = total * quantity;

  document.getElementById('output').textContent = lines.join('\n');
  document.getElementById('output-meta-text').textContent =
    `${total} líneas · ${validLinks.length} links · ${svcIds.length} servicio(s) · ${totalReactions.toLocaleString()} total`;
}

function copyOutput() {
  const text = document.getElementById('output').textContent;
  if (!text || text.includes('Aquí aparecerá')) return;
  navigator.clipboard.writeText(text).then(() => {
    const btn = document.getElementById('btn-copy');
    btn.textContent = '✓ Copiado';
    btn.classList.add('copied');
    setTimeout(() => {
      btn.textContent = 'Copiar';
      btn.classList.remove('copied');
    }, 2000);
  });
}

// Init
renderServices();
</script>
</body>
</html>
