<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>About — Steg1118</title>
  <style>
    :root{
      --bg:#0f1724;
      --card:#071226;
      --muted:#9aa6c1;
      --accent:#7aa2f7;
      --glass: rgba(255,255,255,0.03);
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    html,body{height:100%;margin:0;background:linear-gradient(180deg,#071328 0%, #031026 100%);color:#e6eef8;}
    .container{
      max-width:920px;margin:36px auto;padding:28px;background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.015));border-radius:14px;box-shadow:0 6px 30px rgba(2,6,23,0.6);
      display:grid;grid-template-columns: 1fr;gap:18px;
    }
    .header{
      display:flex;gap:16px;align-items:center;
    }
    .avatar{
      width:72px;height:72px;border-radius:12px;background:var(--glass);display:flex;align-items:center;justify-content:center;font-weight:700;color:var(--accent);
      font-size:20px;
    }
    h1{margin:0;font-size:1.45rem;letter-spacing:0.4px;}
    p.lead{margin:6px 0 0;color:var(--muted);font-size:0.98rem;}
    .stats-row{
      display:flex;gap:18px;align-items:flex-start;justify-content:space-between;
    }
    /* use user-provided images but make them responsive and stack on small screens */
    .stats-row img{max-width:100%;height:auto;border-radius:10px;box-shadow:0 6px 18px rgba(0,0,0,0.45);border:1px solid rgba(255,255,255,0.03);}
    .bio{
      background:rgba(255,255,255,0.02);padding:16px;border-radius:10px;color:#dbe9ff;line-height:1.5;
    }
    ul {margin:10px 0 0;padding-left:18px;color:var(--muted);}
    .links{display:flex;gap:12px;flex-wrap:wrap;margin-top:12px;}
    .link-btn{background:transparent;border:1px solid rgba(255,255,255,0.06);padding:8px 12px;border-radius:10px;color:var(--accent);text-decoration:none;font-weight:600;}
    footer{margin-top:12px;color:var(--muted);font-size:0.9rem;}
    @media (min-width:880px){
      .container{grid-template-columns: 1fr;}
      .stats-row{grid-template-columns: 1fr 1fr;}
      .stats-row img.left{width:47%;}
      .stats-row img.right{width:42%;}
      .stats-row{display:flex;}
    }
    @media (max-width:879px){
      .stats-row{flex-direction:column;}
      .stats-row img{width:100%;}
    }
  </style>
</head>
<body>
  <main class="container" role="main">
    <header class="header">
      <div class="avatar">S</div>
      <div>
        <h1>Hi — I'm Steg1118</h1>
        <p class="lead">Junior undergrad who loves building games and learning full-stack web dev.</p>
      </div>
    </header>

    <section class="stats-row" aria-label="GitHub stats">
      <!-- your exact provided image tags (kept same URLs and attributes) -->
      <img class="left" align="left" width="47%" src="https://github-readme-stats.vercel.app/api?username=Steg1118&show_icons=true&include_all_commits=true&theme=tokyonight&hide_border=true" alt="StegStats" />
      <img class="right" align="right" width="42%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Steg1118&layout=compact&theme=tokyonight&hide_border=true" alt="Steg's Languages"/>
    </section>

    <section class="bio" aria-label="About me">
      <p><strong>About me</strong></p>
      <p>I like making games in Unity and have experience programming in:</p>
      <ul>
        <li>C# (Unity)</li>
        <li>C++</li>
        <li>Currently learning React to build my own website</li>
      </ul>

      <p>I've messed around with plenty of projects, and I have an itch.io account with some game builds.</p>

      <div class="links" aria-hidden="false">
        <!-- replace hrefs with your real links -->
        <a class="link-btn" href="https://github.com/Steg1118" target="_blank" rel="noopener">GitHub</a>
        <a class="link-btn" href="https://itch.io/profile/Steg1118="_blank" rel="noopener">itch.io (replace link)</a>
        <a class="link-btn" href="#" onclick="alert('Replace with your portfolio or email link')" >Contact</a>
      </div>

    </section>
  </main>
</body>
</html>
