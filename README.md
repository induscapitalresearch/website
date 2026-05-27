<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>INDUS Capital Research LLC</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta name="description" content="INDUS Capital Research LLC is a multiple member-managed LLC with over 10 years of quantitative research, AI-driven trade risk management, and data analytics experience." />
  <style>
    :root {
      --primary: #0b1f33;
      --accent: #1aa3a3;
      --light: #f5f7fb;
      --text: #1f2933;
    }
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
      color: var(--text);
      background: white;
      line-height: 1.6;
    }
    header {
      background: radial-gradient(circle at top left, #1a3555, #050b14);
      color: white;
      padding: 18px 7%;
      display: flex;
      align-items: center;
      justify-content: space-between;
      position: sticky;
      top: 0;
      z-index: 20;
    }
    header .logo-text {
      font-size: 1.1rem;
      font-weight: 700;
      letter-spacing: 0.08em;
      text-transform: uppercase;
    }
    header nav a {
      color: #d7e2ff;
      margin-left: 20px;
      text-decoration: none;
      font-size: 0.95rem;
    }
    header nav a:hover {
      color: var(--accent);
    }
    main {
      min-height: 70vh;
    }

    .hero {
      background: linear-gradient(135deg, #050b14 0%, #061526 45%, #071a2e 100%);
      color: white;
      padding: 80px 7% 70px;
      display: grid;
      grid-template-columns: minmax(0, 3fr) minmax(0, 2fr);
      gap: 40px;
      align-items: center;
    }
    .hero h1 {
      font-size: 2.4rem;
      margin-bottom: 10px;
    }
    .hero h2 {
      font-size: 1.05rem;
      font-weight: 500;
      color: #9fb4ff;
      text-transform: uppercase;
      letter-spacing: 0.16em;
      margin-bottom: 18px;
    }
    .hero p {
      max-width: 640px;
      color: #d2ddff;
      margin-bottom: 20px;
    }
    .hero .tags {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
      margin-bottom: 22px;
    }
    .hero .tag {
      border-radius: 999px;
      border: 1px solid rgba(255,255,255,0.16);
      padding: 6px 12px;
      font-size: 0.8rem;
      text-transform: uppercase;
      letter-spacing: 0.12em;
      color: #e6f6ff;
    }
    .btn-primary {
      background: var(--accent);
      color: #04101d;
      border-radius: 999px;
      padding: 10px 22px;
      font-size: 0.95rem;
      border: none;
      cursor: pointer;
      text-decoration: none;
      font-weight: 600;
      display: inline-block;
    }
    .btn-primary:hover {
      opacity: 0.9;
    }
    .hero-card {
      background: rgba(4, 10, 22, 0.9);
      border-radius: 16px;
      border: 1px solid rgba(88, 154, 255, 0.28);
      padding: 20px 22px;
      color: #d7e2ff;
      box-shadow: 0 18px 45px rgba(0,0,0,0.7);
    }
    .hero-card h3 {
      font-size: 0.9rem;
      text-transform: uppercase;
      letter-spacing: 0.16em;
      color: #9fb4ff;
      margin-bottom: 10px;
    }
    .hero-card .metric-row {
      display: flex;
      justify-content: space-between;
      margin-bottom: 8px;
      font-size: 0.9rem;
    }
    .hero-card .metric-label {
      color: #9fb4ff;
    }
    .hero-card .metric-value {
      font-weight: 600;
    }
    .hero-card .pill {
      display: inline-block;
      margin-top: 8px;
      margin-right: 6px;
      padding: 4px 10px;
      font-size: 0.75rem;
      border-radius: 999px;
      border: 1px solid rgba(159,180,255,0.6);
      color: #e3ecff;
    }

    section {
      padding: 60px 7%;
    }
    section.alt {
      background: var(--light);
    }
    h2.section-title {
      font-size: 1.8rem;
      margin-bottom: 10px;
    }
    .section-subtitle {
      color: #64748b;
      margin-bottom: 28px;
    }

    .grid-2 {
      display: grid;
      grid-template-columns: repeat(2, minmax(0,1fr));
      gap: 32px;
    }
    .services-grid {
      display: grid;
      grid-template-columns: repeat(3, minmax(0,1fr));
      gap: 24px;
      margin-top: 10px;
    }

    .card {
      background: white;
      border-radius: 14px;
      padding: 20px 22px;
      box-shadow: 0 10px 24px rgba(15, 23, 42, 0.08);
      border: 1px solid rgba(148, 163, 184, 0.25);
    }
    .card h3 {
      font-size: 1.05rem;
      margin-bottom: 6px;
    }
    .card p {
      font-size: 0.92rem;
      color: #4b5563;
    }

    .service-badge {
      display: inline-block;
      font-size: 0.75rem;
      text-transform: uppercase;
      letter-spacing: 0.16em;
      color: #0b1f33;
      margin-bottom: 6px;
    }
    .service-tech {
      font-size: 0.8rem;
      color: #64748b;
      margin-top: 8px;
    }
    ul {
      margin: 8px 0 0 18px;
      font-size: 0.92rem;
      color: #4b5563;
    }

    .pill-row {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      margin-bottom: 16px;
    }
    .pill-small {
      font-size: 0.75rem;
      padding: 4px 10px;
      border-radius: 999px;
      background: rgba(10, 132, 255, 0.08);
      color: #0b1f33;
      border: 1px solid rgba(15, 23, 42, 0.08);
    }
    .info-row {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      font-size: 0.9rem;
      color: #4b5563;
    }
    .info-item span.label {
      font-weight: 600;
      color: #111827;
    }

    footer {
      background: #020617;
      color: #94a3b8;
      padding: 18px 7% 22px;
      font-size: 0.85rem;
      margin-top: 30px;
    }
    footer a {
      color: #e5e7eb;
      text-decoration: none;
    }
    footer a:hover {
      color: var(--accent);
    }

    @media (max-width: 960px) {
      .hero {
        grid-template-columns: 1fr;
      }
      .grid-2 {
        grid-template-columns: 1fr;
      }
      .services-grid {
        grid-template-columns: repeat(2, minmax(0,1fr));
      }
    }
    @media (max-width: 640px) {
      header {
        flex-direction: column;
        align-items: flex-start;
        gap: 10px;
      }
      header nav {
        display: flex;
        flex-wrap: wrap;
      }
      .services-grid {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>
<body>
<header>
  <div class="logo-text">INDUS Capital Research LLC</div>
  <nav>
    <a href="#home">Home</a>
    <a href="#services">Services</a>
    <a href="#research">Research</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<main>
  <!-- HOME / HERO -->
  <section id="home" class="hero">
    <div>
      <h2>Established Quantitative Research & Risk</h2>
      <h1>AI‑Driven Capital & Risk Intelligence</h1>
      <p>
        INDUS Capital Research LLC is a Wyoming‑formed, multiple member‑managed limited liability company with more than a decade of experience in quantitative research, program and risk management, and data analytics for trade risk management.
      </p>
      <div class="tags">
        <span class="tag">Program &amp; Risk Management</span>
        <span class="tag">AI Expert Advisors</span>
        <span class="tag">Python &amp; Quant Models</span>
        <span class="tag">Data Discovery &amp; Visualization</span>
      </div>
      <a class="btn-primary" href="#services">Explore Services</a>
    </div>
    <div class="hero-card">
      <h3>Core Focus Areas</h3>
      <div class="metric-row">
        <span class="metric-label">Experience</span>
        <span class="metric-value">10+ Years</span>
      </div>
      <div class="metric-row">
        <span class="metric-label">Programs &amp; Risk</span>
        <span class="metric-value">Quantitative &amp; AI‑Driven</span>
      </div>
      <div class="metric-row">
        <span class="metric-label">Analytics</span>
        <span class="metric-value">Signals from Complex Data</span>
      </div>
      <div class="metric-row">
        <span class="metric-label">Automation</span>
        <span class="metric-value">Monitoring &amp; Backtesting</span>
      </div>
      <div class="metric-row">
        <span class="metric-label">Structure</span>
        <span class="metric-value">Multi‑Member Managed LLC</span>
      </div>
      <div class="metric-row">
        <span class="metric-label">Principal Office</span>
        <span class="metric-value">Sheridan, WY</span>
      </div>
      <span class="pill">SciPy</span>
      <span class="pill">scikit‑learn</span>
      <span class="pill">Python / Perl</span>
      <span class="pill">Supervised Learning</span>
    </div>
  </section>

  <!-- SERVICES -->
  <section id="services">
    <h2 class="section-title">Services & Capabilities</h2>
    <p class="section-subtitle">
      INDUS designs and implements analytical programs, AI Expert Advisors, and data analytics frameworks tuned for real‑world trade and risk environments. 
    </p>

    <div class="services-grid">
      <div class="card">
        <div class="service-badge">Program & Risk Management</div>
        <h3>Analytical Modeling & Automation</h3>
        <p>
          Design and management of quantitative programs that integrate analytical modeling, automated decision logic, and risk controls across the full trade lifecycle.
        </p>
        <ul>
          <li>Program design for risk‑aware execution</li>
          <li>Software components for trading workflows</li>
          <li>Governance and monitoring frameworks</li>
        </ul>
        <div class="service-tech">
          Tech: Python, automation frameworks, event‑driven architectures. 
        </div>
      </div>

      <div class="card">
        <div class="service-badge">AI Expert Advisors</div>
        <h3>Supervised Learning for Markets</h3>
        <p>
          Automated “AI Expert Advisors” using supervised learning models for clustering, classification, and regression tailored to market and risk signals.
        </p>
        <ul>
          <li>Feature engineering for trade and risk data</li>
          <li>Model development & calibration using SciPy and scikit‑learn</li>
          <li>Signal validation and robustness checks</li>
        </ul>
        <div class="service-tech">
          Tech: Python ML stack (SciPy, scikit‑learn, related libraries). 
        </div>
      </div>

      <div class="card">
        <div class="service-badge">Valuation & Backtesting</div>
        <h3>Python/Perl Risk Models</h3>
        <p>
          Python‑ and Perl‑based valuation and risk models with systematic backtesting pipelines to assess performance, drawdowns, and scenario behavior over time.
        </p>
        <ul>
          <li>Strategy backtesting and benchmarking</li>
          <li>Scenario and sensitivity analyses</li>
          <li>Custom valuation model development</li>
        </ul>
        <div class="service-tech">
          Tech: Python, Perl, historical and synthetic data engines. 
        </div>
      </div>
    </div>

    <div style="margin-top:40px;" class="grid-2">
      <div class="card">
        <div class="service-badge">Automation & Monitoring</div>
        <h3>Unusual Activity Detection</h3>
        <p>
          An automation framework for monitoring unusual activity, surfacing anomalies in positions, flows, or risk metrics before they become material issues.
        </p>
        <ul>
          <li>Real‑time rules and anomaly detection</li>
          <li>Alerting and escalation workflows</li>
          <li>Dashboards for risk oversight</li>
        </ul>
      </div>

      <div class="card">
        <div class="service-badge">Data Analytics</div>
        <h3>Data Discovery & Visualization</h3>
        <p>
          Data analytics, discovery, and visualization in Python to uncover patterns and trends that may not be immediately evident through conventional reporting.
        </p>
        <ul>
          <li>Exploratory data analysis for complex datasets</li>
          <li>Visual narratives that connect metrics to decisions</li>
          <li>Dashboards that highlight key drivers and anomalies</li>
        </ul>
        <div class="service-tech">
          Tech: Python visualization libraries and analytics tooling. 
        </div>
      </div>
    </div>
  </section>

  <!-- RESEARCH -->
  <section id="research" class="alt">
    <h2 class="section-title">Research Heritage</h2>
    <p class="section-subtitle">
      INDUS builds on more than 10 years of work in quantitative modeling, supervised learning, and risk‑focused data analytics. 
    </p>

    <div class="grid-2">
      <div>
        <p>
          Research begins with clear questions about decisions, risk, and signals. Data is organized, cleaned, and structured for supervised learning or analytical modeling workflows, ensuring that experiments rest on stable foundations. 
        </p>
        <p style="margin-top:10px;">
          Models are evaluated not only on raw performance metrics but also on robustness, interpretability, and behavior under stress scenarios, so research outputs can be responsibly embedded into real systems. 
        </p>
      </div>
      <div class="card">
        <h3>Research Pillars</h3>
        <ul>
          <li>Supervised learning for clustering, classification, and regression</li>
          <li>Python‑based analysis using SciPy, scikit‑learn, and related libraries</li>
          <li>Backtesting frameworks for strategy and model evaluation</li>
          <li>Data visualization to make complex behaviors legible</li>
          <li>Continuous refinement as new data and conditions emerge</li>
        </ul>
      </div>
    </div>

    <div style="margin-top:32px;" class="grid-2">
      <div class="card">
        <h3>From Experiments to Programs</h3>
        <p>
          Results are translated into documented rules, monitoring thresholds, and change‑management processes so that research artifacts become durable components within program and risk frameworks. 
        </p>
      </div>
      <div class="card">
        <h3>Documentation & Governance</h3>
        <p>
          Clear records of data sources, assumptions, model choices, and limitations support governance and auditability for stakeholders who rely on the outputs.
        </p>
      </div>
    </div>
  </section>

  <!-- ABOUT -->
  <section id="about">
    <h2 class="section-title">The Firm</h2>
    <p class="section-subtitle">
      INDUS is structured as a multiple member‑managed limited liability company, combining technical, analytical, and operational perspectives in shared decision‑making. 
    </p>

    <div class="grid-2">
      <div>
        <div class="pill-row">
          <span class="pill-small">Multiple Member‑Managed LLC</span>
          <span class="pill-small">Quant &amp; AI‑Native</span>
          <span class="pill-small">Program‑First Approach</span>
        </div>
        <p>
          As a multi‑member LLC, INDUS brings together engineering, analytics, business, and operational experience within a single governance framework, rather than separating decision‑making from day‑to‑day work. 
        </p>
        <p style="margin-top:10px;">
          This structure supports continuity over time: programs, models, and analytics platforms are developed with long‑term stewardship in mind, not short‑term experiments. 
        </p>
      </div>
      <div class="card">
        <h3>Firm Snapshot</h3>
        <div class="info-row">
          <div class="info-item">
            <span class="label">Entity Type:&nbsp;</span>Multiple member‑managed limited liability company (LLC)
          </div>
          <div class="info-item">
            <span class="label">Experience:&nbsp;</span>10+ years in research‑driven quantitative and data analytics work
          </div>
          <div class="info-item">
            <span class="label">Focus:&nbsp;</span>Program & risk management, AI Expert Advisors, valuation, and analytics
          </div>
        </div>
      </div>
    </div>

    <div style="margin-top:32px;" class="grid-2">
      <div class="card">
        <h3>Research‑Led</h3>
        <p>
          INDUS treats research, backtesting, and stress testing as core activities, ensuring that any deployed system is backed by a clear path from hypothesis to implementation.
        </p>
      </div>
      <div class="card">
        <h3>Program‑First</h3>
        <p>
          Rather than focusing on individual models alone, the firm emphasizes programs and frameworks that integrate models, data, and human judgment into a coherent whole.
        </p>
      </div>
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact" class="alt">
    <h2 class="section-title">Contact & Principal Office</h2>
    <p class="section-subtitle">
      For collaboration, inquiries, or to learn more about how INDUS can support your risk and analytics vision, please reach out.
    </p>

    <div class="grid-2">
      <div class="card">
        <h3>Principal Office</h3>
        <p>
          INDUS Capital Research LLC<br />
          30 N Gould St, Ste R<br />
          Sheridan, WY 82801<br />
          United States
        </p>
        <p style="margin-top:12px;">
          For initial conversations, please contact us by email with a brief overview of your objectives and any relevant timelines or constraints.
        </p>
      </div>
      <div class="card">
        <h3>Contact Details</h3>
        <p>
          Email: <em>investor.indus@gmail.com</em> <br />
          Web: <em>https://induscapitalresearch.github.io/website/</em> 
        </p>
        <p style="margin-top:10px; font-size:0.86rem; color:#6b7280;">
          INDUS Capital Research LLC provides research and risk analytics services and does not represent investment, legal, or tax advice. Any strategies or models discussed should be evaluated in the context of your own risk policies and regulatory obligations.
        </p>
      </div>
    </div>
  </section>
</main>

<footer>
  <div>© <span id="year"></span> INDUS Capital Research LLC. All rights reserved.</div>
</footer>

<script>
  document.getElementById('year').textContent = new Date().getFullYear();
</script>
</body>
</html>
