[adityaroy26_github_profile.html](https://github.com/user-attachments/files/28322982/adityaroy26_github_profile.html)

<style>
  @import url('https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;600&family=Syne:wght@400;600;700&display=swap');

  * { box-sizing: border-box; margin: 0; padding: 0; }

  .profile-wrap {
    background: #0d1117;
    color: #e6edf3;
    font-family: 'Syne', sans-serif;
    min-height: 100vh;
    padding: 0;
  }

  .header-band {
    background: linear-gradient(135deg, #0d1117 0%, #161b22 100%);
    border-bottom: 1px solid #30363d;
    padding: 28px 28px 20px;
    text-align: center;
  }

  .typing-title {
    font-family: 'JetBrains Mono', monospace;
    font-size: 13px;
    color: #58a6ff;
    letter-spacing: 0.04em;
    margin-bottom: 6px;
  }

  .main-title {
    font-size: 22px;
    font-weight: 700;
    color: #e6edf3;
    line-height: 1.3;
  }

  .subtitle {
    font-size: 13px;
    color: #3fb950;
    font-family: 'JetBrains Mono', monospace;
    margin-top: 4px;
    font-weight: 600;
  }

  .content {
    padding: 20px 28px;
    display: flex;
    flex-direction: column;
    gap: 20px;
  }

  .card {
    background: #161b22;
    border: 1px solid #30363d;
    border-radius: 10px;
    padding: 18px 20px;
    position: relative;
  }

  .card-copy-btn {
    position: absolute;
    top: 12px;
    right: 12px;
    background: #21262d;
    border: 1px solid #30363d;
    border-radius: 6px;
    padding: 4px 8px;
    color: #8b949e;
    font-size: 11px;
    cursor: pointer;
    font-family: 'JetBrains Mono', monospace;
  }

  .code-block {
    font-family: 'JetBrains Mono', monospace;
    font-size: 12px;
    line-height: 1.75;
  }

  .kw { color: #ff7b72; }
  .cls { color: #ffa657; }
  .fn { color: #d2a8ff; }
  .str { color: #a5d6ff; }
  .cmt { color: #8b949e; font-style: italic; }
  .self-kw { color: #79c0ff; }
  .attr { color: #e6edf3; }
  .num { color: #79c0ff; }
  .bracket { color: #e6edf3; }
  .indent1 { padding-left: 16px; }
  .indent2 { padding-left: 32px; }
  .indent3 { padding-left: 48px; }

  .section-title {
    font-size: 14px;
    font-weight: 600;
    color: #e6edf3;
    margin-bottom: 14px;
    display: flex;
    align-items: center;
    gap: 8px;
  }

  .section-title span {
    font-size: 16px;
  }

  .tech-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
  }

  .tech-badge {
    display: inline-flex;
    align-items: center;
    gap: 6px;
    padding: 5px 12px;
    border-radius: 20px;
    font-size: 12px;
    font-weight: 600;
    font-family: 'JetBrains Mono', monospace;
    border: 1px solid;
  }

  .badge-python { background: #1c2a1e; border-color: #3fb950; color: #3fb950; }
  .badge-jupyter { background: #2a1c10; border-color: #f97316; color: #f97316; }
  .badge-numpy { background: #1c2433; border-color: #4d9de0; color: #4d9de0; }
  .badge-pandas { background: #1c1f2a; border-color: #a5d6ff; color: #a5d6ff; }
  .badge-matplotlib { background: #261c2a; border-color: #d2a8ff; color: #d2a8ff; }
  .badge-git { background: #2a1c1c; border-color: #ff7b72; color: #ff7b72; }
  .badge-sklearn { background: #1a2424; border-color: #56d364; color: #56d364; }

  .badge-dot {
    width: 6px;
    height: 6px;
    border-radius: 50%;
    background: currentColor;
    flex-shrink: 0;
  }

  .project-card {
    background: #0d1117;
    border: 1px solid #30363d;
    border-radius: 8px;
    padding: 14px 16px;
  }

  .project-name {
    font-size: 14px;
    font-weight: 600;
    color: #58a6ff;
    margin-bottom: 6px;
    display: flex;
    align-items: center;
    gap: 8px;
  }

  .project-badge {
    font-size: 10px;
    color: #e6edf3;
    border: 1px solid #30363d;
    border-radius: 20px;
    padding: 1px 8px;
    font-weight: 400;
  }

  .project-desc {
    font-size: 12px;
    color: #8b949e;
    line-height: 1.6;
    margin-bottom: 10px;
  }

  .project-bullets {
    list-style: none;
    margin-bottom: 10px;
  }

  .project-bullets li {
    font-size: 12px;
    color: #c9d1d9;
    padding: 2px 0;
    padding-left: 14px;
    position: relative;
    line-height: 1.5;
  }

  .project-bullets li::before {
    content: '▸';
    position: absolute;
    left: 0;
    color: #3fb950;
    font-size: 10px;
  }

  .lang-dot {
    display: inline-flex;
    align-items: center;
    gap: 6px;
    font-size: 12px;
    color: #8b949e;
  }

  .dot-jupyter { background: #da5b0b; }

  .view-repo-btn {
    display: inline-block;
    padding: 5px 14px;
    background: transparent;
    border: 1px solid #30363d;
    border-radius: 6px;
    color: #8b949e;
    font-size: 11px;
    font-family: 'JetBrains Mono', monospace;
    cursor: pointer;
    text-decoration: none;
  }

  .view-repo-btn:hover { border-color: #58a6ff; color: #58a6ff; }

  .currently-card {
    background: #0d1117;
    border: 1px solid #21262d;
    border-left: 3px solid #3fb950;
    border-radius: 6px;
    padding: 12px 16px;
  }

  .currently-item {
    font-family: 'JetBrains Mono', monospace;
    font-size: 12px;
    color: #c9d1d9;
    line-height: 2;
  }

  .currently-item::before {
    content: '• ';
    color: #3fb950;
  }

  .stats-row {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 12px;
  }

  .stat-box {
    background: #0d1117;
    border: 1px solid #21262d;
    border-radius: 8px;
    padding: 14px 16px;
    text-align: center;
  }

  .stat-num {
    font-size: 28px;
    font-weight: 700;
    color: #e6edf3;
    font-family: 'JetBrains Mono', monospace;
    line-height: 1;
  }

  .stat-label {
    font-size: 11px;
    color: #8b949e;
    margin-top: 4px;
    font-family: 'JetBrains Mono', monospace;
  }

  .connect-btns {
    display: flex;
    flex-direction: column;
    gap: 8px;
  }

  .connect-btn {
    display: flex;
    align-items: center;
    gap: 10px;
    padding: 10px 16px;
    background: #0d1117;
    border: 1px solid #30363d;
    border-radius: 8px;
    color: #8b949e;
    font-size: 13px;
    font-family: 'JetBrains Mono', monospace;
    cursor: pointer;
    text-decoration: none;
    transition: border-color 0.15s, color 0.15s;
  }

  .connect-btn:hover { border-color: #58a6ff; color: #58a6ff; }

  .connect-btn .icon { font-size: 16px; }

  .contrib-bar {
    display: flex;
    gap: 2px;
    flex-wrap: wrap;
    margin-top: 4px;
  }

  .c-cell {
    width: 10px;
    height: 10px;
    border-radius: 2px;
    background: #21262d;
  }

  .c-cell.l1 { background: #0e4429; }
  .c-cell.l2 { background: #006d32; }
  .c-cell.l3 { background: #26a641; }
  .c-cell.l4 { background: #39d353; }

  .footer-bar {
    background: #161b22;
    border-top: 1px solid #21262d;
    padding: 12px 28px;
    text-align: center;
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    color: #8b949e;
  }

  .section-sep {
    border: none;
    border-top: 1px solid #21262d;
    margin: 0;
  }
</style>

<div class="profile-wrap">
  <div class="header-band">
    <div class="typing-title">&#60;!-- GitHub Profile README --&#62;</div>
    <div class="main-title">Hi, I'm Aditya Roy 👋</div>
    <div class="subtitle">Data Enthusiast • Python Developer • ML Learner</div>
  </div>

  <div class="content">

    <div class="card">
      <button class="card-copy-btn">⎘ copy</button>
      <div class="code-block">
        <div><span class="kw">class</span> <span class="cls">AdityaRoy</span>:</div>
        <div class="indent1"><span class="kw">def</span> <span class="fn">__init__</span>(<span class="self-kw">self</span>):</div>
        <div class="indent2"><span class="self-kw">self</span>.<span class="attr">name</span> = <span class="str">"Aditya Roy"</span></div>
        <div class="indent2"><span class="self-kw">self</span>.<span class="attr">username</span> = <span class="str">"AdityaRoy26"</span></div>
        <div class="indent2"><span class="self-kw">self</span>.<span class="attr">interests</span> = [<span class="str">"Data Science"</span>, <span class="str">"Machine Learning"</span>, <span class="str">"Python"</span>]</div>
        <div class="indent2"><span class="self-kw">self</span>.<span class="attr">tools</span> = [<span class="str">"Jupyter"</span>, <span class="str">"NumPy"</span>, <span class="str">"Pandas"</span>, <span class="str">"Matplotlib"</span>]</div>
        <div class="indent2"><span class="self-kw">self</span>.<span class="attr">current_focus</span> = {</div>
        <div class="indent3"><span class="str">"Learning"</span>: <span class="str">"Data Analysis & ML"</span>,</div>
        <div class="indent3"><span class="str">"Building"</span>: <span class="str">"Mini Projects in Python"</span>,</div>
        <div class="indent3"><span class="str">"Exploring"</span>: <span class="str">"Open Source Contributions"</span></div>
        <div class="indent2">}</div>
        <br>
        <div class="indent1"><span class="kw">def</span> <span class="fn">goal</span>(<span class="self-kw">self</span>):</div>
        <div class="indent2"><span class="kw">return</span> <span class="str">"Build cool things with data and keep learning."</span></div>
      </div>
    </div>

    <div class="card">
      <div class="section-title"><span>🛠</span> Tech Stack</div>
      <div class="tech-grid">
        <span class="tech-badge badge-python"><span class="badge-dot"></span>PYTHON</span>
        <span class="tech-badge badge-jupyter"><span class="badge-dot"></span>JUPYTER</span>
        <span class="tech-badge badge-numpy"><span class="badge-dot"></span>NUMPY</span>
        <span class="tech-badge badge-pandas"><span class="badge-dot"></span>PANDAS</span>
        <span class="tech-badge badge-matplotlib"><span class="badge-dot"></span>MATPLOTLIB</span>
        <span class="tech-badge badge-sklearn"><span class="badge-dot"></span>SKLEARN</span>
        <span class="tech-badge badge-git"><span class="badge-dot"></span>GIT</span>
      </div>
    </div>

    <div class="card">
      <div class="section-title"><span>🚀</span> Featured Project</div>
      <div class="project-card">
        <div class="project-name">
          Mini-projects
          <span class="project-badge">Public</span>
        </div>
        <div class="project-desc">A curated collection of Python mini-projects built using Jupyter Notebooks — exploring data science, automation, and algorithmic problem solving.</div>
        <ul class="project-bullets">
          <li>Built and documented hands-on Python experiments</li>
          <li>Used Jupyter Notebooks for interactive exploration</li>
          <li>Applied data analysis and visualization techniques</li>
          <li>Incrementally committing — 5 commits and growing</li>
        </ul>
        <div style="display: flex; align-items: center; gap: 14px; margin-top: 10px;">
          <span class="lang-dot">
            <span style="width:10px;height:10px;border-radius:50%;background:#da5b0b;display:inline-block;"></span>
            Jupyter Notebook
          </span>
          <button class="view-repo-btn" onclick="openLink('https://github.com/AdityaRoy26/Mini-projects')">⬡ VIEW REPO</button>
        </div>
      </div>
    </div>

    <div class="card">
      <div class="section-title"><span>📊</span> GitHub Stats</div>
      <div class="stats-row">
        <div class="stat-box">
          <div class="stat-num">14</div>
          <div class="stat-label">contributions / year</div>
        </div>
        <div class="stat-box">
          <div class="stat-num">5</div>
          <div class="stat-label">commits this month</div>
        </div>
        <div class="stat-box">
          <div class="stat-num">1</div>
          <div class="stat-label">public repos</div>
        </div>
        <div class="stat-box">
          <div class="stat-num">1</div>
          <div class="stat-label">followers</div>
        </div>
      </div>
      <div style="margin-top: 14px;">
        <div style="font-size:11px;color:#8b949e;margin-bottom:6px;font-family:'JetBrains Mono',monospace;">contribution graph · 2026</div>
        <div class="contrib-bar" id="contrib-grid"></div>
      </div>
    </div>

    <div class="card">
      <div class="section-title"><span>🌱</span> Currently</div>
      <div class="currently-card">
        <div class="currently-item">Learning Python Data Science stack</div>
        <div class="currently-item">Building mini projects with Jupyter</div>
        <div class="currently-item">Exploring ML fundamentals</div>
        <div class="currently-item">Open to collaborations and feedback</div>
      </div>
    </div>

    <div class="card">
      <div class="section-title"><span>🤝</span> Connect With Me</div>
      <div class="connect-btns">
        <a class="connect-btn" href="#" onclick="openLink('https://github.com/AdityaRoy26')">
          <i class="ti ti-brand-github icon" aria-hidden="true"></i>
          GITHUB — AdityaRoy26
        </a>
        <a class="connect-btn" href="#">
          <i class="ti ti-brand-linkedin icon" aria-hidden="true"></i>
          LINKEDIN
        </a>
        <a class="connect-btn" href="#">
          <i class="ti ti-mail icon" aria-hidden="true"></i>
          EMAIL
        </a>
      </div>
    </div>

  </div>

  <div class="footer-bar">
    ✦ profile views: <span style="color:#3fb950">📈 growing</span> &nbsp;|&nbsp; made with ❤️ by AdityaRoy26
  </div>
</div>

<script>
  const grid = document.getElementById('contrib-grid');
  const cells = 140;
  const highWeeks = [128, 129, 130, 131, 132, 133, 134, 135, 136, 137, 138, 139];
  for (let i = 0; i < cells; i++) {
    const c = document.createElement('div');
    c.className = 'c-cell';
    if (highWeeks.includes(i)) {
      const levels = ['l1', 'l2', 'l3', 'l4'];
      c.classList.add(levels[Math.floor(Math.random() * 3) + 1]);
    } else if (Math.random() < 0.05) {
      c.classList.add('l1');
    }
    grid.appendChild(c);
  }

  document.querySelector('.card-copy-btn').addEventListener('click', function() {
    this.textContent = '✓ copied';
    setTimeout(() => this.textContent = '⎘ copy', 1500);
  });
</script>
