<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SORATABI – Travel Magazine</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,400;0,600;0,700;1,400&family=DM+Sans:wght@300;400;500;600&display=swap" rel="stylesheet">
<style>
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{font-family:'DM Sans',sans-serif;background:#f7f2ec;color:#111}
img{display:block;width:100%;height:100%;object-fit:cover}
button,a{cursor:pointer;font-family:'DM Sans',sans-serif}

/* ── tokens ── */
:root{
  --ink:#111810;--white:#fff;--coral:#d95f3b;--teal:#0a5c4e;
  --sand:#f7f2ec;--mist:#e8e0d5;--gray:#6b6560;
}

/* ── NAV ── */
#nav{
  position:fixed;top:0;left:0;right:0;z-index:300;height:64px;
  display:flex;align-items:center;justify-content:space-between;
  padding:0 clamp(16px,6vw,80px);
  transition:background .35s,border-color .35s,backdrop-filter .35s;
}
#nav.solid{
  background:rgba(252,249,244,.96);
  border-bottom:1px solid rgba(0,0,0,.08);
  backdrop-filter:blur(14px);
}
.logo{text-decoration:none}
.logo-text{font-family:'Cormorant Garamond',serif;font-size:22px;font-weight:700;letter-spacing:3px;color:var(--white);transition:color .35s}
.logo-text span{color:var(--coral)}
.logo-sub{font-size:8px;letter-spacing:4px;color:rgba(255,255,255,.5);text-transform:uppercase;transition:color .35s}
#nav.solid .logo-text{color:var(--ink)}
#nav.solid .logo-sub{color:var(--gray)}
.nav-links{display:flex;gap:6px;align-items:center}
.nav-link{background:none;border:none;font-size:11px;letter-spacing:2px;text-transform:uppercase;color:rgba(255,255,255,.8);border-bottom:1.5px solid transparent;padding:4px 14px 3px;transition:all .2s}
.nav-link.active,.nav-link:hover{color:var(--coral);border-bottom-color:var(--coral)}
#nav.solid .nav-link{color:var(--gray)}
#nav.solid .nav-link.active,#nav.solid .nav-link:hover{color:var(--coral)}
.nav-cta{margin-left:8px;padding:8px 22px;background:var(--coral);border:none;border-radius:40px;color:var(--white);font-size:11px;letter-spacing:1.5px;box-shadow:0 4px 14px rgba(217,95,59,.38)}

/* ── PAGES ── */
.page{display:none}
.page.active{display:block}

/* ── HERO ── */
#hero{position:relative;height:100vh;overflow:hidden}
#hero-img{position:absolute;inset:0;animation:kenburns 13s ease-in-out infinite alternate}
#hero-overlay{position:absolute;inset:0;background:linear-gradient(160deg,rgba(0,0,0,.38) 0%,rgba(0,0,0,.08) 50%,rgba(0,0,0,.62) 100%)}
#hero-content{position:absolute;bottom:13%;left:clamp(20px,8vw,96px);max-width:660px;animation:heroIn .7s ease both}
.hero-tag{display:inline-block;background:var(--coral);color:var(--white);font-size:10px;letter-spacing:4px;padding:4px 14px;border-radius:2px;margin-bottom:18px;text-transform:uppercase}
#hero-title{font-family:'Cormorant Garamond',serif;font-size:clamp(44px,6.5vw,82px);font-weight:700;color:var(--white);line-height:1.08;margin-bottom:20px;text-shadow:0 3px 28px rgba(0,0,0,.35)}
#hero-sub{color:rgba(255,255,255,.8);font-size:clamp(14px,1.4vw,17px);line-height:1.75;margin-bottom:34px;max-width:460px}
.hero-btns{display:flex;gap:14px}
.btn-primary{padding:13px 36px;background:var(--coral);border:none;border-radius:40px;color:var(--white);font-size:14px;letter-spacing:1px;box-shadow:0 8px 28px rgba(217,95,59,.45);transition:transform .2s}
.btn-primary:hover{transform:translateY(-2px)}
.btn-ghost{padding:13px 28px;background:rgba(255,255,255,.14);border:1px solid rgba(255,255,255,.42);border-radius:40px;color:var(--white);font-size:13px;letter-spacing:1px;backdrop-filter:blur(4px);transition:all .2s}
.btn-ghost:hover{background:rgba(255,255,255,.24)}
.hero-dots{position:absolute;bottom:28px;right:clamp(20px,5vw,60px);display:flex;gap:8px}
.dot{width:8px;height:8px;border-radius:4px;background:rgba(255,255,255,.38);cursor:pointer;transition:all .4s;border:none}
.dot.active{width:28px;background:var(--coral)}
.scroll-hint{position:absolute;bottom:28px;left:50%;transform:translateX(-50%);display:flex;flex-direction:column;align-items:center;gap:6px;animation:scrollBounce 2.2s infinite}
.scroll-line{width:1px;height:34px;background:rgba(255,255,255,.32)}
.scroll-text{color:rgba(255,255,255,.38);font-size:8px;letter-spacing:4px;text-transform:uppercase}

/* ── SECTIONS ── */
.section{padding:72px clamp(16px,6vw,80px)}
.section-label{font-size:10px;letter-spacing:5px;color:var(--coral);text-transform:uppercase;margin-bottom:10px}
.section-title{font-family:'Cormorant Garamond',serif;font-size:clamp(26px,3.5vw,44px);font-weight:700;color:var(--ink)}
.section-head{display:flex;justify-content:space-between;align-items:flex-end;margin-bottom:44px}
.btn-outline{background:none;border:1px solid var(--ink);border-radius:40px;padding:9px 22px;color:var(--ink);font-size:11px;letter-spacing:1px}
.btn-outline:hover{background:var(--ink);color:var(--white)}

/* ── CARDS ── */
.cards-hero-grid{display:grid;grid-template-columns:1.4fr 1fr;grid-template-rows:auto auto;gap:16px}
.cards-hero-grid .card:first-child{grid-row:1/3}
.card{border-radius:10px;overflow:hidden;background:var(--white);box-shadow:0 2px 12px rgba(0,0,0,.07);transition:transform .3s,box-shadow .3s;cursor:pointer}
.card:hover{transform:translateY(-4px);box-shadow:0 16px 48px rgba(0,0,0,.13)}
.card-img{position:relative;overflow:hidden}
.card-img img{transition:transform .65s ease}
.card:hover .card-img img{transform:scale(1.06)}
.card-img-tall{height:500px}
.card-img-normal{height:220px}
.card-overlay{position:absolute;inset:0;background:linear-gradient(to top,rgba(0,0,0,.3),transparent 55%)}
.card-cat{position:absolute;top:14px;left:14px;background:var(--coral);color:var(--white);font-size:10px;letter-spacing:2px;padding:3px 11px;border-radius:2px;text-transform:uppercase}
.card-body{padding:18px 20px 22px}
.card-meta{font-size:11px;color:var(--gray);letter-spacing:1px;margin-bottom:8px}
.card-title{font-family:'Cormorant Garamond',serif;font-weight:700;color:var(--ink);margin-bottom:10px;line-height:1.35}
.card-title-lg{font-size:23px}
.card-title-sm{font-size:18px}
.card-lead{font-size:13px;color:var(--gray);line-height:1.72;margin-bottom:14px;display:-webkit-box;-webkit-line-clamp:2;-webkit-box-orient:vertical;overflow:hidden}
.card-read{font-size:12px;color:var(--coral);letter-spacing:1px;transition:transform .3s;display:inline-block}
.card:hover .card-read{transform:translateX(5px)}

/* ── CATEGORIES ── */
.cats{background:var(--white);padding:52px clamp(16px,6vw,80px)}
.cats-inner{display:flex;justify-content:center;gap:16px;flex-wrap:wrap}
.cat-btn{display:flex;flex-direction:column;align-items:center;gap:10px;background:none;border:none;padding:14px 20px;border-radius:12px;transition:background .2s}
.cat-btn:hover{background:var(--sand)}
.cat-icon{width:60px;height:60px;border-radius:50%;background:var(--sand);display:flex;align-items:center;justify-content:center;font-size:26px}
.cat-label{font-size:11px;letter-spacing:2px;color:var(--gray);text-transform:uppercase}

/* ── MOSAIC ── */
.mosaic{display:grid;grid-template-columns:repeat(4,1fr);grid-template-rows:280px 280px}
.mosaic-cell{position:relative;overflow:hidden;cursor:pointer}
.mosaic-cell img{transition:transform .6s ease}
.mosaic-cell:hover img{transform:scale(1.08)}
.mosaic-cell-overlay{position:absolute;inset:0;background:linear-gradient(to top,rgba(0,0,0,.6),transparent 55%)}
.mosaic-label{position:absolute;bottom:16px;left:16px;color:var(--white);font-size:11px;letter-spacing:3px;text-transform:uppercase;text-shadow:0 1px 4px rgba(0,0,0,.7)}

/* ── LIST ROWS ── */
.list-row{display:flex;gap:18px;padding:16px 0;border-bottom:1px solid var(--mist);cursor:pointer;transition:all .2s;border-radius:0;padding-left:0;padding-right:0}
.list-row:hover{background:var(--white);border-radius:8px;padding-left:12px;padding-right:12px}
.list-thumb{width:90px;height:90px;border-radius:8px;overflow:hidden;flex-shrink:0}
.list-thumb img{transition:transform .4s}
.list-row:hover .list-thumb img{transform:scale(1.06)}
.list-cat{font-size:10px;color:var(--coral);letter-spacing:2px;margin-bottom:5px;text-transform:uppercase}
.list-title{font-family:'Cormorant Garamond',serif;font-size:18px;font-weight:700;color:var(--ink);margin-bottom:6px;line-height:1.3}
.list-meta{font-size:11px;color:var(--gray)}

/* ── NEWSLETTER ── */
.nl{background:var(--teal);padding:80px clamp(16px,6vw,80px);text-align:center}
.nl-label{font-size:10px;letter-spacing:5px;color:rgba(255,255,255,.4);text-transform:uppercase;margin-bottom:14px}
.nl-title{font-family:'Cormorant Garamond',serif;font-size:clamp(26px,3.5vw,44px);font-weight:700;color:var(--white);margin-bottom:14px}
.nl-sub{color:rgba(255,255,255,.52);font-size:14px;margin-bottom:36px}
.nl-form{display:flex;max-width:440px;margin:0 auto}
.nl-input{flex:1;padding:14px 20px;background:rgba(255,255,255,.12);border:none;border-radius:40px 0 0 40px;color:var(--white);font-size:14px;outline:none;font-family:'DM Sans',sans-serif}
.nl-input::placeholder{color:rgba(255,255,255,.36)}
.nl-btn{padding:14px 28px;background:var(--coral);border:none;border-radius:0 40px 40px 0;color:var(--white);font-size:13px;letter-spacing:1px;white-space:nowrap}

/* ── FOOTER ── */
footer{background:var(--ink);padding:32px clamp(16px,6vw,80px);display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:14px}
.footer-logo{font-family:'Cormorant Garamond',serif;font-size:20px;font-weight:700;letter-spacing:3px;color:var(--white)}
.footer-copy{color:rgba(255,255,255,.22);font-size:11px}

/* ── ARTICLE PAGE ── */
#progress{position:fixed;top:64px;left:0;right:0;height:3px;background:var(--mist);z-index:200}
#progress-bar{width:0%;height:100%;background:var(--coral);transition:width .15s}
.article-hero{position:relative;height:75vh;overflow:hidden}
.article-hero img{animation:kenburns 14s ease-in-out infinite alternate}
.article-hero-overlay{position:absolute;inset:0;background:linear-gradient(to bottom,rgba(0,0,0,.04),rgba(0,0,0,.68))}
.article-hero-content{position:absolute;bottom:0;left:0;right:0;padding:0 clamp(16px,8vw,100px) 56px}
.back-btn{display:inline-block;background:rgba(255,255,255,.14);border:1px solid rgba(255,255,255,.32);border-radius:40px;color:var(--white);padding:6px 18px;font-size:10px;letter-spacing:2px;margin-bottom:16px;backdrop-filter:blur(4px);cursor:pointer}
.article-badges{display:flex;gap:8px;margin-bottom:14px;flex-wrap:wrap}
.badge-coral{background:var(--coral);color:var(--white);font-size:10px;padding:3px 14px;border-radius:2px;letter-spacing:2px}
.badge-glass{background:rgba(255,255,255,.16);color:var(--white);font-size:10px;padding:3px 14px;border-radius:2px;letter-spacing:1px;backdrop-filter:blur(4px)}
.article-title{font-family:'Cormorant Garamond',serif;font-size:clamp(28px,4.5vw,62px);font-weight:700;color:var(--white);margin-bottom:12px;line-height:1.12;max-width:760px;text-shadow:0 2px 22px rgba(0,0,0,.38)}
.article-date{color:rgba(255,255,255,.52);font-size:12px;letter-spacing:1px}
.article-body{max-width:720px;margin:0 auto;padding:60px clamp(16px,5vw,40px)}
.article-lead{font-family:'Cormorant Garamond',serif;font-size:clamp(18px,2vw,23px);line-height:1.85;color:var(--ink);border-left:3px solid var(--coral);padding-left:24px;margin-bottom:44px;font-style:italic}
.tags{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:44px}
.tag{padding:4px 14px;border-radius:40px;background:var(--sand);color:var(--gray);font-size:12px;border:1px solid var(--mist)}
.article-h2{font-family:'Cormorant Garamond',serif;font-size:clamp(20px,2.5vw,28px);font-weight:700;color:var(--ink);margin:44px 0 14px;line-height:1.3}
.article-p{font-size:16px;line-height:1.95;color:#3a3530;margin-bottom:22px}
.article-tip{background:#f0f8f5;border-left:3px solid var(--teal);border-radius:0 8px 8px 0;padding:14px 20px;margin:28px 0;font-size:14px;color:var(--ink);line-height:1.7}
.article-img{margin:48px -40px 0;height:400px;overflow:hidden}

/* ── LIST PAGE ── */
.list-cover{position:relative;height:320px;overflow:hidden}
.list-cover-overlay{position:absolute;inset:0;background:rgba(0,0,0,.44)}
.list-cover-text{position:absolute;inset:0;display:flex;flex-direction:column;justify-content:flex-end;padding:0 clamp(16px,6vw,80px) 44px}
.filter-bar{background:var(--white);border-bottom:1px solid var(--mist);padding:0 clamp(16px,6vw,80px);display:flex;gap:0;overflow-x:auto}
.filter-btn{padding:16px 20px;background:none;border:none;border-bottom:2px solid transparent;color:var(--gray);font-size:12px;letter-spacing:1px;white-space:nowrap;transition:all .2s}
.filter-btn.active,.filter-btn:hover{color:var(--coral);border-bottom-color:var(--coral)}
.cards-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(300px,1fr));gap:24px}

/* ── RELATED ── */
.related{background:var(--sand);padding:60px clamp(16px,6vw,80px)}
.related-label{font-size:10px;letter-spacing:5px;color:var(--coral);text-transform:uppercase;margin-bottom:8px}
.related-title{font-family:'Cormorant Garamond',serif;font-size:28px;font-weight:700;color:var(--ink);margin-bottom:28px}
.related-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(260px,1fr));gap:20px}

/* ── ANIMATIONS ── */
@keyframes kenburns{from{transform:scale(1) translate(0,0)}to{transform:scale(1.07) translate(-1.5%,-1%)}}
@keyframes heroIn{from{opacity:0;transform:translateY(32px)}to{opacity:1;transform:translateY(0)}}
@keyframes scrollBounce{0%,100%{transform:translateX(-50%) translateY(0)}50%{transform:translateX(-50%) translateY(9px)}}
@keyframes fadeUp{from{opacity:0;transform:translateY(20px)}to{opacity:1;transform:translateY(0)}}
.fade-up{animation:fadeUp .5s ease both}

/* responsive */
@media(max-width:640px){
  .cards-hero-grid{grid-template-columns:1fr}
  .cards-hero-grid .card:first-child{grid-row:auto}
  .mosaic{grid-template-columns:repeat(2,1fr);grid-template-rows:repeat(4,200px)}
  .hero-btns{flex-direction:column}
}
</style>
</head>
<body>

<!-- NAV -->
<nav id="nav">
  <a href="#" class="logo" onclick="showPage('top');return false">
    <div class="logo-text">SORA<span>TABI</span></div>
    <div class="logo-sub">TRAVEL MAGAZINE</div>
  </a>
  <div class="nav-links">
    <button class="nav-link active" id="nav-top" onclick="showPage('top')">TOP</button>
    <button class="nav-link" id="nav-list" onclick="showPage('list')">記事一覧</button>
    <button class="nav-cta">旅に出る ✈</button>
  </div>
</nav>

<div id="progress"><div id="progress-bar"></div></div>

<!-- ═══════════ TOP PAGE ═══════════ -->
<div id="page-top" class="page active">

  <!-- HERO -->
  <div id="hero">
    <div id="hero-img">
      <img id="hero-photo" src="https://images.unsplash.com/photo-1506929562872-bb421503ef21?w=1920&q=90&auto=format&fit=crop" alt="hero">
    </div>
    <div id="hero-overlay"></div>
    <div id="hero-content">
      <div class="hero-tag" id="hero-tag">特集</div>
      <h1 id="hero-title">旅は、<br>自分を変える。</h1>
      <p id="hero-sub">SORATABIが厳選した絶景と出会いの旅へ。<br>20〜30代の旅好きが本当に行きたい場所だけを届けます。</p>
      <div class="hero-btns">
        <button class="btn-primary" onclick="showArticle(0)">記事を読む</button>
        <button class="btn-ghost" onclick="showPage('list')">すべて見る →</button>
      </div>
    </div>
    <div class="hero-dots" id="hero-dots"></div>
    <div class="scroll-hint">
      <div class="scroll-line"></div>
      <div class="scroll-text">scroll</div>
    </div>
  </div>

  <!-- FEATURED -->
  <div class="section" style="background:var(--sand)">
    <div class="section-head">
      <div>
        <div class="section-label">Featured</div>
        <h2 class="section-title">今週のおすすめ旅先</h2>
      </div>
      <button class="btn-outline" onclick="showPage('list')">すべて見る →</button>
    </div>
    <div class="cards-hero-grid" id="featured-cards"></div>
  </div>

  <!-- CATEGORIES -->
  <div class="cats">
    <div style="text-align:center;margin-bottom:36px">
      <div class="section-label">Explore</div>
      <h2 class="section-title" style="font-size:clamp(24px,3vw,38px)">テーマから探す</h2>
    </div>
    <div class="cats-inner">
      <button class="cat-btn" onclick="showPage('list')"><div class="cat-icon">🏝</div><div class="cat-label">ビーチ</div></button>
      <button class="cat-btn" onclick="showPage('list')"><div class="cat-icon">🏛</div><div class="cat-label">文化</div></button>
      <button class="cat-btn" onclick="showPage('list')"><div class="cat-icon">🍜</div><div class="cat-label">グルメ</div></button>
      <button class="cat-btn" onclick="showPage('list')"><div class="cat-icon">🗻</div><div class="cat-label">自然</div></button>
      <button class="cat-btn" onclick="showPage('list')"><div class="cat-icon">🏨</div><div class="cat-label">ホテル</div></button>
      <button class="cat-btn" onclick="showPage('list')"><div class="cat-icon">🎒</div><div class="cat-label">冒険</div></button>
    </div>
  </div>

  <!-- MOSAIC -->
  <div class="mosaic" id="mosaic"></div>

  <!-- LATEST -->
  <div class="section" style="background:var(--sand)">
    <div class="section-label">Latest</div>
    <h2 class="section-title" style="margin-bottom:36px">最新の旅の物語</h2>
    <div id="list-rows-home"></div>
  </div>

  <!-- NEWSLETTER -->
  <div class="nl">
    <div class="nl-label">Newsletter</div>
    <h2 class="nl-title">旅のインスピレーションを毎週お届け</h2>
    <p class="nl-sub">週1回、厳選した旅先情報・お得なセールをお届けします</p>
    <div class="nl-form">
      <input class="nl-input" placeholder="your@email.com">
      <button class="nl-btn">登録する</button>
    </div>
  </div>

  <footer>
    <div class="footer-logo">SORA<span style="color:var(--coral)">TABI</span></div>
    <div class="footer-copy">© 2026 SORATABI · Photos: Unsplash (CC0)</div>
  </footer>
</div>

<!-- ═══════════ LIST PAGE ═══════════ -->
<div id="page-list" class="page">
  <div class="list-cover">
    <img src="https://images.unsplash.com/photo-1476514525535-07fb3b4ae5f1?w=1920&q=85&auto=format&fit=crop" alt="">
    <div class="list-cover-overlay"></div>
    <div class="list-cover-text">
      <div class="section-label">All Stories</div>
      <h1 style="font-family:'Cormorant Garamond',serif;font-size:clamp(30px,5vw,56px);font-weight:700;color:var(--white)">旅の記事一覧</h1>
    </div>
  </div>
  <div class="filter-bar" id="filter-bar"></div>
  <div class="section" style="background:var(--sand);padding-top:52px">
    <div class="cards-grid" id="list-cards"></div>
  </div>
</div>

<!-- ═══════════ ARTICLE PAGE ═══════════ -->
<div id="page-article" class="page">
  <div class="article-hero">
    <img id="art-photo" src="" alt="">
    <div class="article-hero-overlay"></div>
    <div class="article-hero-content">
      <button class="back-btn" onclick="showPage('list')">← 記事一覧</button>
      <div class="article-badges">
        <span class="badge-coral" id="art-cat"></span>
        <span class="badge-glass" id="art-dest"></span>
      </div>
      <h1 class="article-title" id="art-title"></h1>
      <div class="article-date" id="art-date"></div>
    </div>
  </div>
  <div class="article-body">
    <p class="article-lead" id="art-lead"></p>
    <div class="tags" id="art-tags"></div>
    <div id="art-body"></div>
    <div class="article-img"><img id="art-img2" src="" alt=""></div>
  </div>
  <div class="related">
    <div class="related-label">Related</div>
    <h3 class="related-title">あわせて読みたい</h3>
    <div class="related-grid" id="related-cards"></div>
  </div>
</div>

<script>
/* ── DATA ── */
const ARTICLES = [
  {
    id:0, cat:"リゾート",
    photo:"https://images.unsplash.com/photo-1514282401047-d79a71a590e8?w=1200&q=85&auto=format&fit=crop",
    title:"モルディブ、水上ヴィラで過ごす夢のような5日間",
    dest:"🇲🇻 モルディブ", time:"5分で読める", date:"2026.02.18",
    lead:"エメラルドグリーンの海に浮かぶ水上コテージ。波の音だけが響く朝。世界中の旅人が憧れる楽園への完全ガイド。",
    tags:["ラグジュアリー","ビーチ","ハネムーン"],
    body:[
      {t:"h2",c:"なぜモルディブは特別なのか"},
      {t:"p", c:"モルディブは1,200以上の小島からなる島嶼国家。その透明度を誇るラグーンと純白のビーチは世界屈指の美しさ。水上ヴィラからの夕日は一生に一度は見るべき絶景として多くの旅行者を魅了し続けています。"},
      {t:"h2",c:"ベストシーズンと過ごし方"},
      {t:"p", c:"11月〜4月が乾季のベストシーズン。青い空と静かな海が続くこの時期は、シュノーケリングやダイビングに最適。早朝のサンライズウォッチングから始まり、夕刻のサンセットクルーズで締めくくる贅沢な一日を。"},
      {t:"tip",c:"💡 予算ヒント：ハネムーナーピークを避けた平日予約で30〜40%オフになるリゾートも。早期予約割引を狙おう。"},
      {t:"h2",c:"絶対泊まりたいリゾート3選"},
      {t:"p", c:"① ソネバジャニ：プライベートプールが全棟に付属する超高級ヴィラ。② パーク ハイアット モルディブ：大人専用の秘境リゾート。③ ビラ ノプル：コスパ最高のセルフケータリング型ヴィラ。"},
    ],
  },
  {
    id:1, cat:"文化",
    photo:"https://images.unsplash.com/photo-1537996194471-e657df975ab4?w=1200&q=85&auto=format&fit=crop",
    title:"バリ島、神々の島で見つけた本当の自分",
    dest:"🇮🇩 バリ島", time:"7分で読める", date:"2026.02.12",
    lead:"芸術と信仰が溶け合う「神々の島」。ウブドの棚田、ヒンドゥー寺院の祭祀、朝日のヨガリトリートが心に語りかける。",
    tags:["文化","スピリチュアル","自然"],
    body:[
      {t:"h2",c:"ウブドで感じる時間のゆらぎ"},
      {t:"p", c:"バリ島の中心部に位置するウブドは芸術と文化の中心地。石畳の細道を歩けば、伝統舞踊の音楽が漏れ聞こえ、供物を頭に乗せた女性たちが寺院へと向かう光景に出会えます。"},
      {t:"tip",c:"✨ 体験：サンライズ前の朝4時発、チャトゥール・サンカラ火山トレッキングは忘れられない体験。"},
    ],
  },
  {
    id:2, cat:"ヨーロッパ",
    photo:"https://images.unsplash.com/photo-1570077188670-e3a8d69ac5ff?w=1200&q=85&auto=format&fit=crop",
    title:"サントリーニ島、青と白の世界で恋に落ちる",
    dest:"🇬🇷 ギリシャ", time:"4分で読める", date:"2026.01.28",
    lead:"白い壁と青いドーム、夕暮れに染まるカルデラ。絵葉書から飛び出したような風景が現実として目の前に広がる。",
    tags:["ヨーロッパ","カップル","絶景"],
    body:[{t:"p",c:"近日公開予定です。ニュースレターに登録してお待ちください。"}],
  },
  {
    id:3, cat:"国内",
    photo:"https://images.unsplash.com/photo-1493976040374-85c8e12f0c0e?w=1200&q=85&auto=format&fit=crop",
    title:"京都の秋、紅葉と寺社仏閣が作り出す幻想",
    dest:"🇯🇵 京都", time:"6分で読める", date:"2026.01.20",
    lead:"海外の旅行者が最も訪れたい日本の街、京都。紅葉の季節に見せる表情は、何度来ても飽きることのない深みがある。",
    tags:["国内","歴史","紅葉"],
    body:[{t:"p",c:"近日公開予定です。"}],
  },
  {
    id:4, cat:"リゾート",
    photo:"https://images.unsplash.com/photo-1507525428034-b723cf961d3e?w=1200&q=85&auto=format&fit=crop",
    title:"ハワイ、ローカルが教えてくれた本当のアロハスピリット",
    dest:"🇺🇸 ハワイ", time:"5分で読める", date:"2026.01.08",
    lead:"ワイキキビーチだけじゃない。地元のプレートランチ、隠れビーチ、早朝のサーフィン──ハワイの本当の顔を探して。",
    tags:["リゾート","グルメ","サーフィン"],
    body:[{t:"p",c:"近日公開予定です。"}],
  },
  {
    id:5, cat:"中東・アフリカ",
    photo:"https://images.unsplash.com/photo-1539020140153-e479b8c22e70?w=1200&q=85&auto=format&fit=crop",
    title:"モロッコ、迷宮の街マラケシュで時間を忘れる",
    dest:"🇲🇦 モロッコ", time:"8分で読める", date:"2025.12.30",
    lead:"スパイスと染料が入り混じるスーク、夜明けのアザーン、サハラ砂漠の星空。五感すべてが揺さぶられる体験がここにある。",
    tags:["アフリカ","文化","砂漠"],
    body:[{t:"p",c:"近日公開予定です。"}],
  },
];

const MOSAICS = [
  {src:"https://images.unsplash.com/photo-1514282401047-d79a71a590e8?w=600&q=80&auto=format&fit=crop",label:"モルディブ"},
  {src:"https://images.unsplash.com/photo-1537996194471-e657df975ab4?w=600&q=80&auto=format&fit=crop",label:"バリ"},
  {src:"https://images.unsplash.com/photo-1570077188670-e3a8d69ac5ff?w=600&q=80&auto=format&fit=crop",label:"サントリーニ"},
  {src:"https://images.unsplash.com/photo-1493976040374-85c8e12f0c0e?w=600&q=80&auto=format&fit=crop",label:"京都"},
  {src:"https://images.unsplash.com/photo-1507525428034-b723cf961d3e?w=600&q=80&auto=format&fit=crop",label:"ハワイ"},
  {src:"https://images.unsplash.com/photo-1539020140153-e479b8c22e70?w=600&q=80&auto=format&fit=crop",label:"モロッコ"},
  {src:"https://images.unsplash.com/photo-1476610182048-b716b8518aae?w=600&q=80&auto=format&fit=crop",label:"アイスランド"},
  {src:"https://images.unsplash.com/photo-1528127269322-539801943592?w=600&q=80&auto=format&fit=crop",label:"ベトナム"},
];

const HEROES = [
  {src:"https://images.unsplash.com/photo-1506929562872-bb421503ef21?w=1920&q=90&auto=format&fit=crop", tag:"特集", title:"旅は、<br>自分を変える。", sub:"SORATABIが厳選した絶景と出会いの旅へ。<br>20〜30代の旅好きが本当に行きたい場所だけを届けます。"},
  {src:"https://images.unsplash.com/photo-1476514525535-07fb3b4ae5f1?w=1920&q=90&auto=format&fit=crop", tag:"新着", title:"その先に、<br>未知の美しさがある。", sub:"本物の旅ガイドを、SORATABIが厳選してお届けします。"},
  {src:"https://images.unsplash.com/photo-1500835556837-99ac94a94552?w=1920&q=90&auto=format&fit=crop", tag:"特集", title:"今すぐ行きたい<br>旅先7選", sub:"2026年、絶対に訪れるべき場所を厳選しました。"},
];

const CATS = ["すべて","リゾート","文化","ヨーロッパ","国内","中東・アフリカ"];

/* ── STATE ── */
let currentCat = "すべて";
let heroIdx = 0;
let heroTimer;

/* ── CARD HTML ── */
function cardHTML(a, tall) {
  return `
    <div class="card" onclick="showArticle(${a.id})">
      <div class="card-img ${tall ? 'card-img-tall' : 'card-img-normal'}">
        <img src="${a.photo}" alt="${a.title}" loading="lazy">
        <div class="card-overlay"></div>
        <div class="card-cat">${a.cat}</div>
      </div>
      <div class="card-body">
        <div class="card-meta">${a.dest} · ${a.date}</div>
        <h3 class="card-title ${tall ? 'card-title-lg' : 'card-title-sm'}">${a.title}</h3>
        <p class="card-lead">${a.lead}</p>
        <span class="card-read">読む →</span>
      </div>
    </div>`;
}

/* ── BUILD HOME ── */
function buildHome() {
  // Featured grid
  const fc = document.getElementById('featured-cards');
  fc.innerHTML = cardHTML(ARTICLES[0], true) + ARTICLES.slice(1,3).map(a => cardHTML(a, false)).join('');

  // Mosaic
  const mosaic = document.getElementById('mosaic');
  mosaic.innerHTML = MOSAICS.map(m => `
    <div class="mosaic-cell" onclick="showPage('list')">
      <img src="${m.src}" alt="${m.label}" loading="lazy">
      <div class="mosaic-cell-overlay"></div>
      <div class="mosaic-label">${m.label}</div>
    </div>`).join('');

  // List rows
  const lr = document.getElementById('list-rows-home');
  lr.innerHTML = ARTICLES.map(a => `
    <div class="list-row" onclick="showArticle(${a.id})">
      <div class="list-thumb"><img src="${a.photo}" alt="${a.title}" loading="lazy"></div>
      <div>
        <div class="list-cat">${a.cat}</div>
        <div class="list-title">${a.title}</div>
        <div class="list-meta">${a.dest} · ${a.time} · ${a.date}</div>
      </div>
    </div>`).join('');

  // Hero dots
  const dots = document.getElementById('hero-dots');
  dots.innerHTML = HEROES.map((_,i) => `<button class="dot ${i===0?'active':''}" onclick="goHero(${i})"></button>`).join('');
}

/* ── BUILD LIST ── */
function buildList() {
  // Filter bar
  const fb = document.getElementById('filter-bar');
  fb.innerHTML = CATS.map(c => `<button class="filter-btn ${c===currentCat?'active':''}" onclick="setCat('${c}')">${c}</button>`).join('');

  // Cards
  const filtered = currentCat === "すべて" ? ARTICLES : ARTICLES.filter(a => a.cat === currentCat);
  const gc = document.getElementById('list-cards');
  gc.innerHTML = filtered.map((a,i) => `<div style="animation:fadeUp .4s ${i*.07}s both">${cardHTML(a, false)}</div>`).join('');
}

function setCat(c) {
  currentCat = c;
  buildList();
}

/* ── HERO CAROUSEL ── */
function goHero(i) {
  clearInterval(heroTimer);
  heroIdx = i;
  const h = HEROES[i];
  const photo = document.getElementById('hero-photo');
  const title = document.getElementById('hero-title');
  const sub   = document.getElementById('hero-sub');
  const tag   = document.getElementById('hero-tag');
  const content = document.getElementById('hero-content');

  content.style.opacity = '0';
  content.style.transform = 'translateY(16px)';
  photo.style.opacity = '0';

  setTimeout(() => {
    photo.src = h.src;
    title.innerHTML = h.title;
    sub.innerHTML = h.sub;
    tag.textContent = h.tag;
    photo.style.opacity = '1';
    content.style.opacity = '1';
    content.style.transform = 'translateY(0)';
  }, 400);

  document.querySelectorAll('.dot').forEach((d,di) => d.classList.toggle('active', di===i));
  startHeroTimer();
}

function startHeroTimer() {
  heroTimer = setInterval(() => goHero((heroIdx + 1) % HEROES.length), 5500);
}

/* ── SHOW ARTICLE ── */
function showArticle(id) {
  const a = ARTICLES[id];
  document.getElementById('art-photo').src = a.photo;
  document.getElementById('art-cat').textContent = a.cat;
  document.getElementById('art-dest').textContent = a.dest;
  document.getElementById('art-title').textContent = a.title;
  document.getElementById('art-date').textContent = a.date + ' · ' + a.time;
  document.getElementById('art-lead').textContent = a.lead;
  document.getElementById('art-img2').src = a.photo;

  document.getElementById('art-tags').innerHTML = a.tags.map(t => `<span class="tag">#${t}</span>`).join('');

  document.getElementById('art-body').innerHTML = a.body.map(b => {
    if (b.t==='h2')  return `<h2 class="article-h2">${b.c}</h2>`;
    if (b.t==='p')   return `<p class="article-p">${b.c}</p>`;
    if (b.t==='tip') return `<div class="article-tip">${b.c}</div>`;
    return '';
  }).join('');

  // Related
  const related = ARTICLES.filter(x => x.id !== id).slice(0,3);
  document.getElementById('related-cards').innerHTML = related.map(r => cardHTML(r, false)).join('');

  showPage('article');
}

/* ── NAVIGATION ── */
function showPage(p) {
  document.querySelectorAll('.page').forEach(el => el.classList.remove('active'));
  document.getElementById('page-' + p).classList.add('active');
  document.querySelectorAll('.nav-link').forEach(el => el.classList.remove('active'));
  const nl = document.getElementById('nav-' + p);
  if (nl) nl.classList.add('active');
  window.scrollTo(0, 0);
  if (p === 'list') buildList();
  // progress bar only for article
  document.getElementById('progress').style.display = p === 'article' ? 'block' : 'none';
}

/* ── SCROLL HANDLER ── */
window.addEventListener('scroll', () => {
  const nav = document.getElementById('nav');
  if (window.scrollY > 70) nav.classList.add('solid');
  else nav.classList.remove('solid');

  // progress
  const el = document.documentElement;
  const pct = Math.min(100, (el.scrollTop / (el.scrollHeight - el.clientHeight)) * 100);
  document.getElementById('progress-bar').style.width = pct + '%';
});

/* ── NAV transparent/solid on page change ── */
const _showPage = showPage;

/* ── INIT ── */
buildHome();
startHeroTimer();
document.getElementById('progress').style.display = 'none';
document.getElementById('hero-content').style.transition = 'opacity .5s ease, transform .5s ease';
document.getElementById('hero-photo').style.transition = 'opacity .5s ease';
</script>
</body>
</html>
