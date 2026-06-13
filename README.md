<!DOCTYPE html>
<html lang="zh">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Canada Jingzhou Chamber of Commerce</title>
<style>
body{font-family:Arial,sans-serif;margin:0;background:#f5f5f5;text-align:center}
.lang-switch{position:absolute;top:20px;left:20px}
.lang-switch button{padding:8px 14px;border:1px solid white;background:transparent;color:white;border-radius:20px;cursor:pointer}
header{background:#003366;color:white;padding:70px 20px}
h1{font-size:48px;margin:0}
h2{color:#003366}
.container{max-width:1000px;margin:auto;padding:40px 20px}
.card{background:white;padding:35px;margin:25px 0;border-radius:10px;box-shadow:0 2px 10px rgba(0,0,0,.1)}
footer{background:#003366;color:white;padding:20px}
.en{display:none}
</style>
</head>

<body>

<header>
  <div class="lang-switch">
    <button onclick="toggleLang()">中文 / EN</button>
  </div>

  <h1 class="zh">加拿大荆州商会</h1>
  <h1 class="en">Canada Jingzhou Chamber of Commerce</h1>

  <p class="zh">连接荆州与加拿大，促进商务、文化与社区交流</p>
  <p class="en">Connecting Jingzhou and Canada through business, culture, and community.</p>
</header>

<div class="container">

  <div class="card">
    <h2 class="zh">关于商会</h2>
    <h2 class="en">About Us</h2>

    <p class="zh">加拿大荆州商会致力于促进荆州与加拿大之间的经贸合作、文化交流与社区发展。</p>
    <p class="en">The Canada Jingzhou Chamber of Commerce promotes business cooperation, cultural exchange, and community development between Jingzhou and Canada.</p>
  </div>

  <div class="card">
    <h2 class="zh">会员</h2>
    <h2 class="en">Membership</h2>

    <p class="zh">欢迎企业家、专业人士和社区成员加入商会。</p>
    <p class="en">Entrepreneurs, professionals, and community members are welcome to join the Chamber.</p>
  </div>

  <div class="card">
    <h2 class="zh">联系我们</h2>
    <h2 class="en">Contact Us</h2>

    <p>Email: info@jingzhoucanada.ca</p>
  </div>

</div>

<footer>
  © 2026 Canada Jingzhou Chamber of Commerce
</footer>

<script>
function toggleLang(){
  const zh = document.querySelectorAll('.zh');
  const en = document.querySelectorAll('.en');
  zh.forEach(x => x.style.display = x.style.display === 'none' ? 'block' : 'none');
  en.forEach(x => x.style.display = x.style.display === 'block' ? 'none' : 'block');
}
</script>

</body>
</html>
