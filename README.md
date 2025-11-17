# hairstudio
Black Gold Hair Studio Demo
<!DOCTYPE html>
<html lang="zh-CN">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Black Gold Hair Studio</title>

<style>
    body { margin:0; background:#0a0a0a; color:#f1f1f1; font-family:-apple-system, BlinkMacSystemFont, "PingFang SC"; }

    .banner {
        background:url('https://images.unsplash.com/photo-1522335789203-aabd1fc54bc9') center/cover;
        height:52vh;
        display:flex;
        align-items:flex-end;
        padding:30px;
        font-size:32px;
        color:#f9d48b;
        font-weight:700;
        text-shadow:0 4px 18px rgba(0,0,0,0.6);
    }

    .nav {
        display:flex;
        justify-content:space-around;
        margin:25px 0;
    }
    .nav a {
        color:#f9d48b;
        text-decoration:none;
        font-size:15px;
        padding:8px 14px;
        border:1px solid rgba(249,212,139,0.3);
        border-radius:10px;
    }

    .section-title {
        font-size:20px;
        margin:20px 20px 10px;
        color:#f9d48b;
    }

    .card {
        background:#111;
        border-radius:16px;
        padding:16px;
        margin:15px 20px;
        border:1px solid rgba(249,212,139,0.15);
        box-shadow:0 4px 18px rgba(0,0,0,0.3);
    }
    .card img { width:100%; border-radius:12px; margin-bottom:10px; }
    .card h3 { margin:0; color:#f9d48b; font-size:18px; }
    .card p { font-size:14px; color:#bbb; margin:6px 0 0; }

</style>
</head>
<body>

<div class="banner">Black Gold Hair Studio</div>

<div class="nav">
    <a href="styles.html">发型库</a>
    <a href="ai-hair.html">AI 试发</a>
    <a href="booking.html">预约</a>
    <a href="merchant.html">商户端</a>
</div>

<div class="section-title">明星发型推荐</div>

<div class="card">
    <img src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d">
    <h3>质感黑金层次剪</h3>
    <p>线条利落、氛围冷感，高级感拉满。</p>
</div>

<div class="card">
    <img src="https://images.unsplash.com/photo-1524504388940-b1c1722653e1">
    <h3>烟金雾调染发</h3>
    <p>低饱和雾金色，显白耐看。</p>
</div>

</body>
</html>