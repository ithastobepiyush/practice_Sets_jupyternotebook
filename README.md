<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Practice Sets — Jupyter Notebook</title>
  <style>
    :root{
      --bg:#0f1724; --card:#0b1220; --muted:#98a0b3; --accent:#3b82f6; --glass: rgba(255,255,255,0.03);
      --radius:12px; --pad:20px;
      color-scheme: dark;
    }
    *{box-sizing:border-box}
    body{font-family:Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial; margin:0; background:linear-gradient(180deg,#071228 0%,#081427 100%); color:#e6eef8; -webkit-font-smoothing:antialiased; -moz-osx-font-smoothing:grayscale}
    .wrap{max-width:900px;margin:48px auto;padding:24px}
    .card{background:linear-gradient(180deg,var(--card),var(--glass));border:1px solid rgba(255,255,255,0.03);padding:var(--pad);border-radius:var(--radius);box-shadow:0 8px 30px rgba(2,6,23,0.6)}
    header{display:flex;align-items:center;justify-content:space-between;gap:16px}
    h1{font-size:20px;margin:0}
    p.lead{margin:8px 0 18px;color:var(--muted);font-size:14px}
    .meta{display:flex;gap:12px;align-items:center}
    .badge{background:rgba(255,255,255,0.04);padding:8px 12px;border-radius:999px;font-size:13px;color:var(--muted)}
    hr{border:0;border-top:1px solid rgba(255,255,255,0.03);margin:20px 0}
    ul{margin:8px 0 18px 20px;color:var(--muted)}
    code{background:rgba(255,255,255,0.02);padding:4px 6px;border-radius:6px;font-family:ui-monospace, SFMono-Regular, Monaco, "Roboto Mono", monospace;font-size:13px}
    .grid{display:grid;grid-template-columns:1fr 260px;gap:18px}
    .side .box{background:rgba(255,255,255,0.02);padding:12px;border-radius:10px;color:var(--muted);font-size:14px}
    a.button{display:inline-block;padding:10px 14px;border-radius:10px;background:linear-gradient(90deg,var(--accent),#60a5fa);color:white;text-decoration:none;font-weight:600}
    footer{margin-top:18px;color:var(--muted);font-size:13px}
    @media (max-width:800px){.grid{grid-template-columns:1fr} .side{order:2}}
  </style>
</head>
<body>
  <div class="wrap">
    <div class="card">
      <header>
        <div>
          <h1>Practice Sets — Jupyter Notebook</h1>
          <p class="lead">A curated collection of Jupyter Notebook practice sets and solutions documenting a learning journey in Python and data/problem-solving.</p>
        </div>
        <div class="meta">
          <span class="badge">Jupyter Notebooks</span>
          <span class="badge">Python</span>
        </div>
      </header>

      <hr />

      <div class="grid">
        <main>
          <section>
            <h3>Contents</h3>
            <ul>
              <li>Jupyter Notebook files (.ipynb) containing solved practice problems.</li>
              <li>Step-by-step explanations and code comments where applicable.</li>
              <li>Notebooks span topics like data manipulation, algorithms, and visualization.</li>
            </ul>
          </section>

          <section>
            <h3>Tools &amp; Libraries</h3>
            <p class="muted">Typical environment used to create these notebooks:</p>
            <ul>
              <li>Python 3.8+</li>
              <li>Jupyter Notebook / JupyterLab</li>
              <li>Common libraries: <code>numpy</code>, <code>pandas</code>, <code>matplotlib</code>, <code>scikit-learn</code> (as needed)</li>
            </ul>
          </section>

          <section>
            <h3>Objectives</h3>
            <ul>
              <li>Strengthen problem-solving and algorithmic thinking.</li>
              <li>Practice data handling, analysis, and visualization.</li>
              <li>Track progress with clean, well-documented notebooks.</li>
            </ul>
          </section>

          <section>
            <h3>Contributing</h3>
            <p class="muted">This repository is primarily a personal learning log, but constructive feedback is welcome.</p>
            <ul>
              <li>Open an issue to suggest improvements or report typos.</li>
              <li>Pull requests are welcome for formatting, README improvements, or small fixes.</li>
            </ul>
          </section>

          <section>
            <h3>License</h3>
            <p class="muted">No license is specified for this project. Please contact the author for reuse permission.</p>
          </section>
        </main>

        <aside class="side">
          <div class="box">
            <strong>Quick actions</strong>
            <p style="margin:10px 0 8px;color:var(--muted)">Clone the repository and open notebooks with Jupyter:</p>
            <pre style="background:transparent;margin:0;padding:0;color:var(--muted)"><code>git clone https://github.com/ithastobepiyush/practice_Sets_jupyternotebook.git
cd practice_Sets_jupyternotebook
jupyter notebook</code></pre>
            <div style="margin-top:12px"><a class="button" href="https://github.com/ithastobepiyush" target="_blank" rel="noreferrer">View author on GitHub</a></div>
          </div>

          <div style="height:12px"></div>

          <div class="box">
            <strong>Author</strong>
            <p style="margin:8px 0 0;color:var(--muted)"><strong>Piyush Tiwari</strong><br/>GitHub: <a href="https://github.com/ithastobepiyush" target="_blank" rel="noreferrer">ithastobepiyush</a></p>
          </div>
        </aside>
      </div>

      <footer>
        Last updated: <span id="updated">—</span>
      </footer>
    </div>
  </div>
  <script>
    // optionally show current date
    document.getElementById('updated').textContent = new Date().toLocaleDateString();
  </script>
</body>
</html>
