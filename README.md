# Business-analytics-portfolio
Data-Driven Marketing Analytics Portfolio — GA4 • CRO • Power BI • Looker Studio A showcase of real-world dashboards, case studies, and ROI insights designed to help businesses make data-backed marketing decisions.

# 🎯 Business Analytics Portfolio  
**GA4 • CRO • Sales & Marketing Analytics • Power BI • Looker Studio**

A professional portfolio showcasing my data-driven marketing and conversion optimization work.  
It includes real-world style dashboards, client-style case studies, and performance insights focused on **data visualization, ROI modeling, and user behavior analytics**.



## 🌟 Highlights
- **3 Case Studies:**  
  1. *E-commerce GA4 Funnel Optimization* — +21% Checkout Conversion  
  2. *SaaS ROI Model in Power BI* — −14% CAC, +19% ROAS  
  3. *Content CRO for EdTech* — +83% Blog → Signup Rate  
- **2 Client Briefs:** Fully detailed mock briefs showing objectives, data sources, and deliverables.
- **Interactive Dashboards:**  
  - GA4 Engagement Funnel (Looker Studio)  
  - Multi-Touch ROI Model (Power BI)  
  - E-commerce Revenue Analysis (Looker Studio)



## 🧠 Skills & Tools
**Analytics Platforms:** Google Analytics 4 (GA4), Google Tag Manager (GTM)  
**Visualization:** Power BI, Looker Studio, Excel  
**Optimization:** CRO, A/B Testing, Heatmaps (Hotjar, Optimizely)  
**Marketing Metrics:** ROI, CTR, CAC, AOV, CLV, Engagement Rate  
**Other Tools:** HubSpot, BigQuery, SQL, Google Ads, Meta Ads  



## 🧩 Folder Structure

Business-analytics-portfolio/
│
├── index.html → main landing page
├── dashboards.html → dashboard gallery
├── case-studies.html → portfolio writeups
├── assets/
│ ├── dashboard1.jpg
│ ├── dashboard2.jpg
│ ├── dashboard3.jpg
│ ├── favicon.png
│ └── style.css
└── docs/
├── Portfolio_Case_Studies_Fani.pdf
└── Mock_Client_Briefs_Fani.pdf

<!DOCTYPE html>
<html lang="en">
<head>
  <!-- Basic -->
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Fani — Data-Driven Marketing Analyst (GA4 • CRO)</title>
  <meta name="description" content="Data-Driven Marketing & Analytics Portfolio — GA4, CRO, Power BI, Looker Studio. Real dashboards, case studies, and measurable ROI outcomes.">
  <link rel="icon" href="assets/favicon.png">

  <!-- Fonts & Icons -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;800&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="assets/style.css">
  <script>
    // Mobile nav toggle (no external libs)
    document.addEventListener('DOMContentLoaded', () => {
      const btn = document.querySelector('[data-toggle="nav"]');
      const nav = document.querySelector('#site-nav');
      if (btn) btn.addEventListener('click', () => nav.classList.toggle('open'));
    });
  </script>
</head>
<body>
  <!-- ============ Header / Nav ============ -->
  <header class="header">
    <a class="brand" href="#top" aria-label="Go to top">
      <img src="assets/logo.svg" alt="" class="logo" />
      <span>Fani Analytics</span>
    </a>

    <button class="nav-toggle" data-toggle="nav" aria-label="Toggle navigation" aria-expanded="false">
      ☰
    </button>

    <nav id="site-nav" class="nav" aria-label="Primary">
      <a href="#skills">Skills</a>
      <a href="#dashboards">Dashboards</a>
      <a href="#case-studies">Case Studies</a>
      <a href="#services">Services</a>
      <a href="#about">About</a>
      <a href="#contact" class="btn btn-accent">Contact</a>
    </nav>
  </header>

  <!-- ============ Hero ============ -->
  <main id="top" class="container">
    <section class="hero">
      <div class="hero-text">
        <h1>Data-Driven Marketing Analyst</h1>
        <p class="tagline">I turn GA4, CRO, and Marketing data into <strong>measurable growth</strong> with dashboards & experiments.</p>
        <div class="hero-ctas">
          <!-- Replace with your Calendly/WhatsApp -->
          <a href="#contact" class="btn btn-accent">Book a 20-min GA4 Review</a>
          <a href="#dashboards" class="btn btn-ghost">View Dashboards</a>
        </div>
        <ul class="kpis" role="list" aria-label="Key results">
          <li><span class="kpi">+21%</span><span class="kpi-label">Checkout Conversion</span></li>
          <li><span class="kpi">−14%</span><span class="kpi-label">Blended CAC</span></li>
          <li><span class="kpi">+83%</span><span class="kpi-label">Blog → Signup</span></li>
        </ul>
        <p class="muted sm">Event integrity validated against source systems (±3%).</p>
      </div>
      <figure class="hero-visual">
        <img src="assets/hero-dashboard.jpg" alt="Portfolio dashboards preview" loading="eager">
        <figcaption class="sr-only">A collage of analytics dashboards showing funnels, ROI and KPIs.</figcaption>
      </figure>
    </section>

    <!-- ============ Skills ============ -->
    <section id="skills" class="section">
      <h2 class="section-title">Skills & Tools</h2>
      <div class="grid skills">
        <div class="card">
          <h3>Analytics</h3>
          <p>Google Analytics 4 (events, funnels, conversions), Google Tag Manager</p>
        </div>
        <div class="card">
          <h3>Visualization</h3>
          <p>Power BI, Looker Studio, Excel (charts, DAX/measures, blended data)</p>
        </div>
        <div class="card">
          <h3>CRO & Research</h3>
          <p>A/B testing, heatmaps, scroll tracking, experiment design</p>
        </div>
        <div class="card">
          <h3>Marketing Analytics</h3>
          <p>ROI/ROAS, CAC, AOV, CLV, Attribution (position-based, assisted)</p>
        </div>
        <div class="card">
          <h3>Data & Ops</h3>
          <p>BigQuery/SQL basics, UTM governance, CRM alignment, HubSpot</p>
        </div>
      </div>
    </section>

    <!-- ============ Dashboards ============ -->
    <section id="dashboards" class="section">
      <h2 class="section-title">Featured Dashboards</h2>
      <div class="grid cards">
        <!-- Card 1 -->
        <article class="card card-hover">
          <img src="assets/dashboard1.jpg" alt="E-commerce Revenue & ROI dashboard" class="card-img">
          <div class="card-body">
            <h3>E-commerce Revenue & ROI</h3>
            <p class="muted">Looker Studio • Reveals channel-level revenue leaks and ROI.</p>
            <!-- Replace # with your published dashboard link -->
            <a href="#" class="btn btn-small" target="_blank" rel="noopener">Open Live Dashboard</a>
          </div>
        </article>
        <!-- Card 2 -->
        <article class="card card-hover">
          <img src="assets/dashboard2.jpg" alt="GA4 Funnel analysis dashboard" class="card-img">
          <div class="card-body">
            <h3>GA4 Funnel Analysis</h3>
            <p class="muted">Power BI • Checkout conversion uplift +21% after fixes.</p>
            <a href="#" class="btn btn-small" target="_blank" rel="noopener">Open Live Dashboard</a>
          </div>
        </article>
        <!-- Card 3 -->
        <article class="card card-hover">
          <img src="assets/dashboard3.jpg" alt="SaaS Multi-Touch ROI dashboard" class="card-img">
          <div class="card-body">
            <h3>SaaS Multi-Touch ROI</h3>
            <p class="muted">Power BI • CAC −14% after spend re-allocation.</p>
            <a href="#" class="btn btn-small" target="_blank" rel="noopener">Open Live Dashboard</a>
          </div>
        </article>
      </div>
      <p class="sm muted mt-8">*Screenshots are illustrative. Live dashboards may require view access.</p>
    </section>

    <!-- ============ Case Studies ============ -->
    <section id="case-studies" class="section">
      <h2 class="section-title">Case Studies</h2>

      <details class="case">
        <summary>E-commerce GA4 Funnel Optimization — <span class="pill">+21% CVR</span></summary>
        <div class="case-body">
          <p><strong>Challenge:</strong> Checkout completion 1.9% with unclear drop-offs post-GA4 migration.</p>
          <p><strong>Action:</strong> Enhanced e-commerce events via GTM, segmented traffic, funnel dashboard, A/B tests.</p>
          <p><strong>Result:</strong> CVR 1.9% → 2.3% (+21%), RPS +12%, payment step abandonment −18%.</p>
          <div class="buttons">
            <a class="btn btn-small" href="docs/Portfolio_Case_Studies_Fani.pdf" target="_blank" rel="noopener">Download PDF</a>
          </div>
        </div>
      </details>

      <details class="case">
        <summary>SaaS Marketing Performance & ROI — <span class="pill">−14% CAC</span></summary>
        <div class="case-body">
          <p><strong>Challenge:</strong> Rising CAC & weak attribution beyond last-click.</p>
          <p><strong>Action:</strong> GA4 + UTM governance, assisted conversions, Power BI ROI model from CRM + ad spend.</p>
          <p><strong>Result:</strong> Blended CAC −14%, Trial→Paid +9%, ROAS +19%.</p>
          <div class="buttons">
            <a class="btn btn-small" href="docs/Portfolio_Case_Studies_Fani.pdf" target="_blank" rel="noopener">Download PDF</a>
          </div>
        </div>
      </details>

      <details class="case">
        <summary>Content to Conversion CRO — <span class="pill">+83% Signup</span></summary>
        <div class="case-body">
          <p><strong>Challenge:</strong> High traffic but poor blog→signup rate (0.6%).</p>
          <p><strong>Action:</strong> Topic×CTA mapping via GA4+GSC, engagement events, layout A/B tests.</p>
          <p><strong>Result:</strong> Signup 0.6% → 1.1% (+83%), top articles contribute ~38% signups.</p>
          <div class="buttons">
            <a class="btn btn-small" href="docs/Portfolio_Case_Studies_Fani.pdf" target="_blank" rel="noopener">Download PDF</a>
          </div>
        </div>
      </details>

      <div class="cta-row">
        <a class="btn btn-ghost" href="docs/Mock_Client_Briefs_Fani.pdf" target="_blank" rel="noopener">View Client Briefs Pack (PDF)</a>
      </div>
    </section>

    <!-- ============ Services ============ -->
    <section id="services" class="section">
      <h2 class="section-title">Services</h2>
      <div class="grid services">
        <div class="card">
          <h3>GA4 Audit & Implementation</h3>
          <p>Event schema, GTM setup, validation & governance.</p>
        </div>
        <div class="card">
          <h3>ROI & Channel Modeling</h3>
          <p>Power BI / Looker Studio models with assisted conversions.</p>
        </div>
        <div class="card">
          <h3>CRO Experiments</h3>
          <p>A/B test design, heatmaps, funnel fixes & reporting.</p>
        </div>
        <div class="card">
          <h3>Executive Reporting</h3>
          <p>Weekly insights, KPI decks & enablement sessions.</p>
        </div>
      </div>
      <p class="muted sm mt-8">Packages: Starter (1 week) • Growth (4 weeks) • Retainer (Monthly)</p>
    </section>

    <!-- ============ About ============ -->
    <section id="about" class="section">
      <h2 class="section-title">About</h2>
      <div class="about">
        <p>I help teams make data-backed decisions using GA4, CRO and performance analytics. My dashboards highlight where revenue leaks, and my experiments fix them.</p>
        <ul class="badges" role="list">
          <li>GA4</li><li>GTM</li><li>Power BI</li><li>Looker Studio</li><li>BigQuery</li><li>SQL</li><li>Hotjar</li><li>Optimizely</li>
        </ul>
      </div>
    </section>

    <!-- ============ Contact ============ -->
    <section id="contact" class="section">
      <h2 class="section-title">Contact</h2>
      <div class="contact">
        <p class="muted">Open for remote analytics projects. Timezone: Asia/Dhaka (GMT+6)</p>
        <div class="grid contact-grid">
          <a class="btn btn-accent" href="mailto:yourname@example.com">Email Me</a>
          <a class="btn btn-ghost" href="https://linkedin.com/in/yourprofile" target="_blank" rel="noopener">LinkedIn</a>
          <!-- Replace with Calendly/WhatsApp if you prefer -->
          <a class="btn btn-ghost" href="#" target="_blank" rel="noopener">Book a Call</a>
        </div>
      </div>
    </section>
  </main>

  <!-- ============ Footer ============ -->
  <footer class="footer">
    <p class="sm muted">© <span id="y"></span> Fani Analytics — Turning analytics into growth.</p>
  </footer>

  <script>document.getElementById('y').textContent = new Date().getFullYear();</script>
</body>
</html>





