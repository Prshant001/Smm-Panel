<!DOCTYPE html>
<html lang="hi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SMMPro Panel</title>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@tabler/icons-webfont@latest/dist/tabler-icons.min.css">
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{font-family:system-ui,sans-serif;background:#f4f4f0;color:#1a1a18;height:100vh;display:flex;flex-direction:column}
:root{--accent:#1a6ef7;--accent-bg:#e6f0fe;--accent-text:#1a5cd4;--success:#15803d;--success-bg:#dcfce7;--warning:#92400e;--warning-bg:#fef3c7;--border:#e0dfd8;--surface:#fff;--surface-1:#f8f8f5;--muted:#888780}
.topbar{background:#fff;border-bottom:1px solid var(--border);padding:0 20px;height:52px;display:flex;align-items:center;justify-content:space-between;flex-shrink:0}
.logo{font-size:16px;font-weight:600;color:var(--accent);display:flex;align-items:center;gap:8px}
.user-info{display:flex;align-items:center;gap:12px;font-size:13px;color:var(--muted)}
.bal{background:var(--accent-bg);color:var(--accent-text);padding:4px 12px;border-radius:20px;font-size:13px;font-weight:500}
.layout{display:flex;flex:1;overflow:hidden}
.sidebar{width:200px;background:#fff;border-right:1px solid var(--border);padding:1rem 0;display:flex;flex-direction:column;gap:2px;overflow-y:auto}
.nav-item{display:flex;align-items:center;gap:10px;padding:10px 16px;font-size:14px;color:var(--muted);cursor:pointer;transition:background 0.15s}
.nav-item:hover{background:var(--surface-1);color:#1a1a18}
.nav-item.active{background:var(--accent-bg);color:var(--accent-text);font-weight:500}
.nav-item i{font-size:17px}
.badge{font-size:11px;background:#ef4444;color:#fff;padding:2px 6px;border-radius:10px;margin-left:auto}
.main{flex:1;padding:20px;overflow-y:auto;background:var(--surface-1)}
.section{display:none}
.section.visible{display:block}
.page-title{font-size:18px;font-weight:600;color:#1a1a18;margin-bottom:16px}
.stat-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(140px,1fr));gap:12px;margin-bottom:20px}
.stat-card{background:#fff;border:1px solid var(--border);border-radius:12px;padding:16px}
.stat-label{font-size:12px;color:var(--muted);margin-bottom:6px}
.stat-val{font-size:22px;font-weight:600;color:#1a1a18}
.stat-sub{font-size:12px;margin-top:4px}
.card{background:#fff;border:1px solid var(--border);border-radius:12px;padding:18px;margin-bottom:16px}
.card-title{font-size:15px;font-weight:600;color:#1a1a18;margin-bottom:14px;display:flex;align-items:center;gap:8px}
table{width:100%;border-collapse:collapse;font-size:13px}
th{text-align:left;padding:8px 10px;color:var(--muted);font-weight:400;border-bottom:1px solid var(--border)}
td{padding:9px 10px;color:#1a1a18;border-bottom:1px solid var(--border)}
tr:last-child td{border-bottom:none}
.status{display:inline-block;font-size:11px;padding:3px 9px;border-radius:10px;font-weight:500}
.s-done{background:var(--success-bg);color:var(--success)}
.s-progress{background:var(--warning-bg);color:var(--warning)}
.s-pending{background:var(--accent-bg);color:var(--accent-text)}
.form-group{margin-bottom:14px}
.form-group label{font-size:13px;color:#444;display:block;margin-bottom:5px;font-weight:500}
select,input[type=text],input[type=number],textarea{width:100%;padding:9px 12px;border:1px solid var(--border);border-radius:8px;background:#fff;color:#1a1a18;font-size:14px;font-family:inherit;outline:none;transition:border 0.15s}
select:focus,input:focus,textarea:focus{border-color:var(--accent);box-shadow:0 0 0 3px var(--accent-bg)}
.submit-btn{background:var(--accent);color:#fff;border:none;padding:10px 24px;border-radius:8px;font-size:14px;font-weight:500;cursor:pointer;width:100%;margin-top:4px;transition:background 0.15s}
.submit-btn:hover{background:#1558d6}
.service-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(160px,1fr));gap:12px}
.svc-card{background:#fff;border:1px solid var(--border);border-radius:12px;padding:14px;cursor:pointer;transition:border-color 0.15s}
.svc-card:hover{border-color:var(--accent)}
.svc-name{font-size:13px;font-weight:600;color:#1a1a18;margin-bottom:4px}
.svc-rate{font-size:13px;color:var(--accent);font-weight:500}
.svc-min{font-size:11px;color:var(--muted);margin-top:2px}
.platform-badge{display:inline-block;font-size:11px;padding:2px 8px;border-radius:10px;margin-bottom:6px;font-weight:500}
.p-ig{background:#fce4ec;color:#880e4f}
.p-yt{background:#ffebee;color:#b71c1c}
.p-fb{background:#e3f2fd;color:#0d47a1}
.p-tw{background:#e0f7fa;color:#006064}
.p-tt{background:#f3e5f5;color:#4a148c}
.price-box{background:var(--surface-1);border-radius:8px;padding:12px;margin-bottom:10px;font-size:13px;display:flex;justify-content:space-between}
.total-box{background:var(--accent-bg);border-radius:8px;padding:12px;margin-bottom:14px;font-size:14px;display:flex;justify-content:space-between}
.order-msg{margin-top:10px;font-size:13px;text-align:center;color:var(--success);display:none;font-weight:500}
</style>
</head>
<body>

<div class="topbar">
  <div class="logo"><i class="ti ti-rocket"></i> SMMPro Panel</div>
  <div class="user-info">
    <span class="bal"><i class="ti ti-coin"></i> ₹847.50</span>
    <span style="display:flex;align-items:center;gap:6px">
      <div style="width:28px;height:28px;border-radius:50%;background:var(--accent-bg);display:flex;align-items:center;justify-content:center;font-size:12px;color:var(--accent-text);font-weight:600">U</div>
      User
    </span>
  </div>
</div>

<div class="layout">
  <div class="sidebar">
    <div class="nav-item active" onclick="show('dashboard',this)"><i class="ti ti-layout-dashboard"></i> Dashboard</div>
    <div class="nav-item" onclick="show('neworder',this)"><i class="ti ti-plus"></i> New Order</div>
    <div class="nav-item" onclick="show('orders',this)"><i class="ti ti-list"></i> My Orders <span class="badge">3</span></div>
    <div class="nav-item" onclick="show('services',this)"><i class="ti ti-sparkles"></i> Services</div>
    <div class="nav-item" onclick="show('funds',this)"><i class="ti ti-wallet"></i> Add Funds</div>
    <div style="flex:1"></div>
    <div class="nav-item" onclick="show('support',this)"><i class="ti ti-headset"></i> Support</div>
  </div>

  <div class="main">

    <!-- DASHBOARD -->
    <div id="dashboard" class="section visible">
      <div class="page-title">Dashboard</div>
      <div class="stat-grid">
        <div class="stat-card"><div class="stat-label">Total Orders</div><div class="stat-val">24</div><div class="stat-sub" style="color:var(--success)">+3 this week</div></div>
        <div class="stat-card"><div class="stat-label">Completed</div><div class="stat-val">19</div><div class="stat-sub" style="color:var(--muted)">79% rate</div></div>
        <div class="stat-card"><div class="stat-label">In Progress</div><div class="stat-val">4</div><div class="stat-sub" style="color:var(--warning)">Running</div></div>
        <div class="stat-card"><div class="stat-label">Balance</div><div class="stat-val">₹847</div><div class="stat-sub" style="color:var(--accent-text)">Add funds</div></div>
      </div>
      <div class="card">
        <div class="card-title"><i class="ti ti-clock-history"></i> Recent orders</div>
        <table>
          <tr><th>ID</th><th>Service</th><th>Link</th><th>Qty</th><th>Status</th></tr>
          <tr><td>#1024</td><td>Instagram Followers</td><td style="color:var(--accent)">@mypage</td><td>500</td><td><span class="status s-done">Completed</span></td></tr>
          <tr><td>#1023</td><td>YouTube Views</td><td style="color:var(--accent)">youtu.be/…</td><td>1000</td><td><span class="status s-progress">In Progress</span></td></tr>
          <tr><td>#1022</td><td>Facebook Likes</td><td style="color:var(--accent)">fb.com/post</td><td>200</td><td><span class="status s-pending">Pending</span></td></tr>
        </table>
      </div>
    </div>

    <!-- NEW ORDER -->
    <div id="neworder" class="section">
      <div class="page-title">New order</div>
      <div class="card">
        <div class="form-group">
          <label>Select category</label>
          <select id="cat" onchange="updateServices()">
            <option value="">-- Select --</option>
            <option value="ig">Instagram</option>
            <option value="yt">YouTube</option>
            <option value="fb">Facebook</option>
            <option value="tw">Twitter / X</option>
            <option value="tt">TikTok</option>
          </select>
        </div>
        <div class="form-group">
          <label>Select service</label>
          <select id="svc" onchange="updatePrice()">
            <option value="">-- Select category first --</option>
          </select>
        </div>
        <div class="form-group">
          <label>Link / URL</label>
          <input type="text" id="link" placeholder="https://...">
        </div>
        <div class="form-group">
          <label>Quantity</label>
          <input type="number" id="qty" value="100" min="10" oninput="updatePrice()">
        </div>
        <div class="price-box">
          <span style="color:var(--muted)">Price per 1000:</span>
          <span id="rate" style="font-weight:500">—</span>
        </div>
        <div class="total-box">
          <span style="color:var(--accent-text)">Total charge:</span>
          <span id="total" style="font-weight:600;color:var(--accent-text)">—</span>
        </div>
        <button class="submit-btn" onclick="placeOrder()">Place order</button>
        <div class="order-msg" id="order-msg">✓ Order placed successfully!</div>
      </div>
    </div>

    <!-- MY ORDERS -->
    <div id="orders" class="section">
      <div class="page-title">My orders</div>
      <div class="card">
        <table>
          <tr><th>ID</th><th>Service</th><th>Qty</th><th>Charge</th><th>Start count</th><th>Status</th></tr>
          <tr><td>#1024</td><td>Instagram Followers</td><td>500</td><td>₹14.50</td><td>0</td><td><span class="status s-done">Completed</span></td></tr>
          <tr><td>#1023</td><td>YouTube Views</td><td>1000</td><td>₹22.00</td><td>400</td><td><span class="status s-progress">In Progress</span></td></tr>
          <tr><td>#1022</td><td>Facebook Likes</td><td>200</td><td>₹8.00</td><td>0</td><td><span class="status s-pending">Pending</span></td></tr>
        </table>
      </div>
    </div>

    <!-- SERVICES -->
    <div id="services" class="section">
      <div class="page-title">All services</div>
      <div class="service-grid">
        <div class="svc-card"><span class="platform-badge p-ig">Instagram</span><div class="svc-name">Followers</div><div class="svc-rate">₹29 / 1000</div><div class="svc-min">Min: 100 | Max: 100K</div></div>
        <div class="svc-card"><span class="platform-badge p-ig">Instagram</span><div class="svc-name">Likes</div><div class="svc-rate">₹15 / 1000</div><div class="svc-min">Min: 50 | Max: 50K</div></div>
        <div class="svc-card"><span class="platform-badge p-ig">Instagram</span><div class="svc-name">Views (Reels)</div><div class="svc-rate">₹8 / 1000</div><div class="svc-min">Min: 100 | Max: 1M</div></div>
        <div class="svc-card"><span class="platform-badge p-yt">YouTube</span><div class="svc-name">Views</div><div class="svc-rate">₹22 / 1000</div><div class="svc-min">Min: 500 | Max: 500K</div></div>
        <div class="svc-card"><span class="platform-badge p-yt">YouTube</span><div class="svc-name">Likes</div><div class="svc-rate">₹35 / 1000</div><div class="svc-min">Min: 100 | Max: 10K</div></div>
        <div class="svc-card"><span class="platform-badge p-yt">YouTube</span><div class="svc-name">Subscribers</div><div class="svc-rate">₹60 / 1000</div><div class="svc-min">Min: 100 | Max: 50K</div></div>
        <div class="svc-card"><span class="platform-badge p-fb">Facebook</span><div class="svc-name">Page Likes</div><div class="svc-rate">₹40 / 1000</div><div class="svc-min">Min: 50 | Max: 10K</div></div>
        <div class="svc-card"><span class="platform-badge p-tw">Twitter / X</span><div class="svc-name">Followers</div><div class="svc-rate">₹55 / 1000</div><div class="svc-min">Min: 100 | Max: 50K</div></div>
        <div class="svc-card"><span class="platform-badge p-tt">TikTok</span><div class="svc-name">Followers</div><div class="svc-rate">₹18 / 1000</div><div class="svc-min">Min: 100 | Max: 100K</div></div>
        <div class="svc-card"><span class="platform-badge p-tt">TikTok</span><div class="svc-name">Likes</div><div class="svc-rate">₹12 / 1000</div><div class="svc-min">Min: 50 | Max: 100K</div></div>
      </div>
    </div>

    <!-- ADD FUNDS -->
    <div id="funds" class="section">
      <div class="page-title">Add funds</div>
      <div class="card" style="background:var(--accent-bg);border-color:#b3d0fc;display:flex;align-items:center;justify-content:space-between">
        <div><p style="font-size:14px;color:var(--accent-text);font-weight:500">Current balance</p><span style="font-size:12px;color:var(--muted)">₹847.50 available</span></div>
        <div style="font-size:24px;font-weight:700;color:var(--accent)">₹847.50</div>
      </div>
      <div class="card">
        <div class="card-title"><i class="ti ti-credit-card"></i> Add funds</div>
        <div class="form-group"><label>Select amount</label>
          <select><option>₹100</option><option>₹250</option><option>₹500</option><option selected>₹1000</option><option>₹2000</option></select>
        </div>
        <div class="form-group"><label>Payment method</label>
          <select><option>UPI</option><option>Net Banking</option><option>Debit / Credit Card</option><option>Paytm</option></select>
        </div>
        <button class="submit-btn">Proceed to payment</button>
      </div>
    </div>

    <!-- SUPPORT -->
    <div id="support" class="section">
      <div class="page-title">Support</div>
      <div class="card">
        <div class="card-title"><i class="ti ti-message-circle"></i> New ticket</div>
        <div class="form-group"><label>Subject</label><input type="text" placeholder="Issue related to order..."></div>
        <div class="form-group"><label>Order ID (optional)</label><input type="text" placeholder="#1024"></div>
        <div class="form-group"><label>Message</label><textarea rows="4" placeholder="Describe your issue..."></textarea></div>
        <button class="submit-btn">Submit ticket</button>
      </div>
    </div>

  </div>
</div>

<script>
const services={
  ig:[{name:'Followers',rate:29},{name:'Likes',rate:15},{name:'Views (Reels)',rate:8},{name:'Story Views',rate:6},{name:'Comments',rate:80}],
  yt:[{name:'Views',rate:22},{name:'Likes',rate:35},{name:'Subscribers',rate:60},{name:'Watch Hours',rate:120}],
  fb:[{name:'Page Likes',rate:40},{name:'Post Likes',rate:18},{name:'Followers',rate:45}],
  tw:[{name:'Followers',rate:55},{name:'Likes',rate:20},{name:'Retweets',rate:30}],
  tt:[{name:'Followers',rate:18},{name:'Likes',rate:12},{name:'Views',rate:5}]
};
function show(id,el){
  document.querySelectorAll('.section').forEach(s=>s.classList.remove('visible'));
  document.getElementById(id).classList.add('visible');
  document.querySelectorAll('.nav-item').forEach(n=>n.classList.remove('active'));
  if(el)el.classList.add('active');
}
function updateServices(){
  const cat=document.getElementById('cat').value;
  const svc=document.getElementById('svc');
  svc.innerHTML='';
  if(!cat){svc.innerHTML='<option>-- Select category first --</option>';return;}
  services[cat].forEach(s=>{
    const o=document.createElement('option');
    o.value=s.rate;
    o.textContent=s.name+' — ₹'+s.rate+'/1000';
    svc.appendChild(o);
  });
  updatePrice();
}
function updatePrice(){
  const rate=parseFloat(document.getElementById('svc').value)||0;
  const qty=parseInt(document.getElementById('qty').value)||0;
  document.getElementById('rate').textContent=rate?'₹'+rate+'/1000':'—';
  const total=rate*qty/1000;
  document.getElementById('total').textContent=total>0?'₹'+total.toFixed(2):'—';
}
function placeOrder(){
  const msg=document.getElementById('order-msg');
  msg.style.display='block';
  setTimeout(()=>msg.style.display='none',3000);
}
</script>
</body>
</html>
