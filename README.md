# -NE-Ocekivana-buducnost
<!DOCTYPE html>
<html lang="bs">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>(NE)Očekivana budućnost</title>
  <style>
    body {font-family: system-ui, sans-serif; margin: 0 auto; max-width: 800px; padding: 1rem;}
    nav {margin-bottom: 1rem;}
    button {margin-right: 0.5rem; padding: 0.3rem 0.8rem; border: 1px solid #888; border-radius: 6px; background: #f7f7f7; cursor: pointer;}
    button:hover {background: #eaeaea;}
    article {margin-top: 2rem;}
    h1 {font-size: 2rem; margin-bottom: 0.5rem;}
    footer {margin-top: 4rem; font-size: 0.8rem; color: #555; text-align: center;}
  </style>
</head>
<body>

<nav aria-label="Language switcher">
  <button onclick="setLang('bs')">Bosanski</button>
  <button onclick="setLang('en')">English</button>
</nav>

<!-- Bosnian content -->
<article id="content-bs">
  <h1>Dobrodošli na (NE)Očekivanu budućnost</h1>
  <p>Ovo je moj lični blog na kojem dijelim razmišljanja o tehnologiji, životu i svemu neočekivanom.</p>
</article>

<!-- English content -->
<article id="content-en" style="display:none;">
  <h1>Welcome to the (UN)Expected Future</h1>
  <p>This is my personal blog where I share thoughts on technology, life, and everything unexpected.</p>
</article>

<footer>
  <p>© 2025 (NE)Očekivana budućnost</p>
</footer>

<script>
function setLang(lang) {
  document.documentElement.lang = lang;
  const bs = document.getElementById('content-bs');
  const en = document.getElementById('content-en');
  if (lang === 'bs') {
    bs.style.display = 'block';
    en.style.display = 'none';
  } else {
    bs.style.display = 'none';
    en.style.display = 'block';
  }
}
</script>

</body>
</html>
