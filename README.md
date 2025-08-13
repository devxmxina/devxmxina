<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Ingrid — About & Skills (Cyberpunk)</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500;700;900&family=Share+Tech+Mono&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#05051a;
      --neon:#00ff41;
      --neon-soft:#7fff7f;
      --accent:#39ff14;
    }
    *{box-sizing:border-box;margin:0;padding:0}
    body{
      background: radial-gradient(80% 80% at 50% 10%, rgba(0,255,65,.06), transparent 50%) , linear-gradient(135deg, #05051a, #0a0a2e);
      color: var(--neon);
      font-family: 'Share Tech Mono', monospace;
      line-height: 1.6;
      padding: 24px;
    }
    .wrap{
      max-width: 980px;
      margin: 0 auto;
      border: 2px solid var(--neon);
      border-radius: 14px;
      padding: 28px 28px 22px;
      box-shadow: 0 0 28px rgba(0,255,65,.25), inset 0 0 24px rgba(0,255,65,.08);
      background: linear-gradient(180deg, rgba(0,255,65,.05), rgba(0,255,65,.02));
      position: relative;
      overflow: hidden;
    }
    .wrap:before{
      content:'';
      position:absolute; inset: -2px;
      border-radius: 14px;
      background: conic-gradient(from 0deg, transparent, rgba(0,255,65,.15), transparent);
      filter: blur(24px);
      z-index:-1;
    }
    h2{
      font-family:'Orbitron', sans-serif;
      font-weight:900;
      letter-spacing:.08em;
      color: var(--accent);
      text-shadow: 0 0 14px var(--accent);
      margin-bottom: 12px;
      text-transform: uppercase;
    }
    .about{
      font-size: 1.03rem;
      background: linear-gradient(135deg, rgba(0,255,65,.08), rgba(0,255,65,.02));
      border: 1px solid rgba(0,255,65,.35);
      border-radius: 10px;
      padding: 18px 18px;
      margin-bottom: 22px;
    }
    .skills{
      font-size: 1.02rem;
      background: linear-gradient(135deg, rgba(0,255,65,.05), rgba(0,255,65,.015));
      border: 1px solid rgba(0,255,65,.30);
      border-radius: 10px;
      padding: 16px 18px;
    }
    .mono-line{
      display:block;
      font-family:'Orbitron', sans-serif;
      font-weight:700;
      letter-spacing:.06em;
      color: var(--accent);
      text-shadow: 0 0 10px var(--accent);
      margin-bottom: 10px;
      font-size: 1.05rem;
    }
    .skill-row{
      margin-bottom: 8px;
      word-break: break-word;
    }
    .muted{
      color: var(--neon-soft);
    }
    @media (max-width:600px){
      .wrap{padding:18px}
      .about, .skills{font-size: .98rem}
    }
  </style>
</head>
<body>
  <div class="wrap">
    <h2>About</h2>
    <div class="about">
      <p>I create — new ideas, new systems, new ways to see the unseen.</p>
      <p>For me, <strong>design and beauty</strong> are as important as <strong>function and intelligence</strong>.</p>
      <p>Blending AI, data science, and aesthetics, I build solutions that are <strong>powerful and visually striking</strong> — where technology meets artistry.</p>
    </div>

    <h2>Skills</h2>
    <div class="skills">
      <span class="mono-line">⌁ AI × Code × Design ⌁</span>
      <div class="skill-row">LLMs ⚡ Computer Vision ⚡ NLP ⚡ MLOps</div>
      <div class="skill-row">Python × R × SQL × SAS</div>
      <div class="skill-row">REST APIs × FastAPI × Streamlit × Web Scraping</div>
      <div class="skill-row">Data Pipelines × MongoDB × PostgreSQL</div>
      <div class="skill-row">TensorFlow × PyTorch × scikit-learn</div>
      <div class="skill-row">Docker × GitHub Actions × CI/CD × MLflow</div>
      <div class="skill-row">RAG × LangChain × Azure AI Foundry</div>
      <div class="skill-row">Rust × TypeScript × Web3 × Smart Contracts</div>
      <div class="skill-row">Figma × Brizy × Adobe Suite</div>
      <div class="skill-row">Data Visualization — Plotly × Power BI × Matplotlib</div>
      <div class="skill-row muted">Now building with: LangChain, RAG, Playwright, Azure AI Foundry, Hugging Face</div>
      <div class="skill-row muted">Learning: Rust, TypeScript, WebAssembly, Web3</div>
    </div>
  </div>
</body>
</html>
