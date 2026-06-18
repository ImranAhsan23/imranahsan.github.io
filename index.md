---
layout: default
title: Imran Ahsan
description: Trustworthy AI, Graph Machine Learning, Machine Unlearning, and Explainable AI
permalink: /
---

<style>
:root {
  --navy: #12345b;
  --blue: #1d5f9f;
  --blue-soft: #eaf2fb;
  --ink: #1d2733;
  --muted: #5e6b78;
  --line: #dce4ec;
  --paper: #ffffff;
  --surface: #f7f9fc;
}

* { box-sizing: border-box; }
html { scroll-behavior: smooth; }
body {
  margin: 0;
  color: var(--ink);
  background: var(--surface);
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  line-height: 1.65;
}
a { color: var(--blue); text-decoration: none; }
a:hover { text-decoration: underline; }
.container { max-width: 1080px; margin: 0 auto; padding: 0 24px; }

.topbar {
  position: sticky;
  top: 0;
  z-index: 20;
  background: rgba(255,255,255,.96);
  border-bottom: 1px solid var(--line);
  backdrop-filter: blur(10px);
}
.topbar .container {
  min-height: 62px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 20px;
}
.site-name { font-weight: 800; color: var(--navy); letter-spacing: -.02em; }
.nav { display: flex; flex-wrap: wrap; gap: 17px; }
.nav a { color: #334155; font-size: 14px; font-weight: 650; }

.hero {
  background: var(--paper);
  border-bottom: 1px solid var(--line);
  padding: 58px 0 48px;
}
.hero-grid {
  display: grid;
  grid-template-columns: 210px 1fr;
  gap: 42px;
  align-items: center;
}
.profile-photo {
  width: 210px;
  height: 210px;
  object-fit: cover;
  border-radius: 18px;
  border: 1px solid var(--line);
  box-shadow: 0 14px 34px rgba(18,52,91,.16);
}
.eyebrow {
  margin: 0 0 8px;
  color: var(--blue);
  font-size: 14px;
  font-weight: 750;
  letter-spacing: .08em;
  text-transform: uppercase;
}
.hero h1 {
  margin: 0;
  color: var(--navy);
  font-size: clamp(2.5rem, 6vw, 4.25rem);
  line-height: 1.04;
  letter-spacing: -.045em;
}
.role {
  margin: 12px 0 0;
  color: #314256;
  font-size: 1.25rem;
  font-weight: 650;
}
.summary {
  margin: 15px 0 0;
  max-width: 760px;
  color: var(--muted);
  font-size: 1.04rem;
}
.status-row, .link-row, .keyword-row {
  display: flex;
  flex-wrap: wrap;
  gap: 9px;
}
.status-row { margin-top: 18px; }
.status {
  padding: 6px 11px;
  border-radius: 999px;
  background: var(--blue-soft);
  border: 1px solid #cfe0f2;
  color: var(--navy);
  font-size: 13px;
  font-weight: 650;
}
.link-row { margin-top: 22px; }
.button {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  padding: 9px 14px;
  border-radius: 8px;
  border: 1px solid var(--blue);
  font-weight: 700;
}
.button.primary { background: var(--blue); color: white; }
.button.secondary { background: white; color: var(--blue); }
.button:hover { text-decoration: none; transform: translateY(-1px); }

main { padding: 8px 0 54px; }
section {
  background: var(--paper);
  border: 1px solid var(--line);
  border-radius: 14px;
  padding: 30px;
  margin-top: 20px;
  box-shadow: 0 6px 18px rgba(18,52,91,.035);
}
h2 {
  margin: 0 0 18px;
  color: var(--navy);
  font-size: 1.55rem;
  letter-spacing: -.02em;
}
h3 { margin: 0 0 7px; color: #24364a; font-size: 1.05rem; }
p { margin: 0 0 13px; }
.lead { font-size: 1.04rem; color: #344457; }
.grid-2, .grid-4 {
  display: grid;
  gap: 15px;
}
.grid-2 { grid-template-columns: repeat(2, minmax(0,1fr)); }
.grid-4 { grid-template-columns: repeat(2, minmax(0,1fr)); }
.card {
  border: 1px solid var(--line);
  background: #fbfcfe;
  border-radius: 11px;
  padding: 17px;
}
.card p { color: var(--muted); margin: 0; }
.keyword-row { margin-top: 10px; }
.keyword {
  padding: 4px 9px;
  border-radius: 999px;
  color: var(--blue);
  background: var(--blue-soft);
  font-size: 12px;
  font-weight: 650;
}

.news-item, .timeline-item, .publication {
  padding: 14px 0;
  border-bottom: 1px solid var(--line);
}
.news-item:last-child, .timeline-item:last-child, .publication:last-child { border-bottom: 0; }
.date {
  display: inline-block;
  min-width: 92px;
  color: var(--blue);
  font-weight: 750;
}
.publication-title { color: #15263a; font-weight: 750; }
.publication-meta { margin-top: 4px; color: var(--muted); font-size: 14px; }
.venue {
  display: inline-block;
  margin-left: 5px;
  padding: 2px 7px;
  border-radius: 999px;
  background: var(--blue-soft);
  color: var(--blue);
  font-size: 12px;
  font-weight: 750;
  white-space: nowrap;
}
.paper-links { margin-top: 6px; font-size: 13px; font-weight: 650; }
.timeline-title { font-weight: 750; color: #182b40; }
.timeline-meta { color: var(--muted); font-size: 14px; }

.notice {
  margin-top: 18px;
  border-left: 4px solid var(--blue);
  background: #f5f9fd;
  border-radius: 8px;
  padding: 13px 15px;
  color: #344457;
}
footer {
  padding: 28px 0 42px;
  text-align: center;
  color: var(--muted);
  font-size: 14px;
}

@media (max-width: 760px) {
  .topbar .container { align-items: flex-start; flex-direction: column; padding-top: 13px; padding-bottom: 13px; }
  .hero-grid { grid-template-columns: 1fr; gap: 25px; }
  .profile-photo { width: 170px; height: 170px; }
  .grid-2, .grid-4 { grid-template-columns: 1fr; }
  section { padding: 22px; }
  .date { display: block; min-width: 0; margin-bottom: 3px; }
}
</style>

<div class="topbar">
  <div class="container">
    <a class="site-name" href="#top">Imran Ahsan</a>
    <nav class="nav" aria-label="Main navigation">
      <a href="#about">About</a>
      <a href="#research">Research</a>
      <a href="#publications">Publications</a>
      <a href="#projects">Projects</a>
      <a href="#experience">Experience</a>
      <a href="#teaching">Teaching</a>
      <a href="#contact">Contact</a>
    </nav>
  </div>
</div>

<header class="hero" id="top">
  <div class="container hero-grid">
    <img class="profile-photo" src="{{ '/assets/profile.jpg' | relative_url }}" alt="Portrait of Imran Ahsan">
    <div>
      <p class="eyebrow">Academic Profile</p>
      <h1>Imran Ahsan</h1>
      <p class="role">Ph.D. Candidate · Trustworthy AI and Graph Machine Learning</p>
      <p class="summary">I develop reliable learning systems for relational data, with emphasis on machine unlearning, privacy, explainability, auditability, and reproducible evaluation.</p>
      <div class="status-row">
        <span class="status">Ph.D. defense completed · June 2026</span>
        <span class="status">Chung-Ang University · South Korea</span>
        <span class="status">Open to postdoctoral and faculty opportunities</span>
      </div>
      <div class="link-row">
        <a class="button primary" href="mailto:Imranahsan23@gmail.com">Email</a>
        <a class="button secondary" href="https://scholar.google.com/citations?user=h_P3dAkAAAAJ&hl=en" target="_blank" rel="noopener">Google Scholar</a>
        <a class="button secondary" href="https://github.com/ImranAhsan23" target="_blank" rel="noopener">GitHub</a>
        <a class="button secondary" href="https://www.linkedin.com/in/imran-ahsan-7042365a/" target="_blank" rel="noopener">LinkedIn</a>
      </div>
    </div>
  </div>
</header>

<main class="container">
  <section id="about">
    <h2>About</h2>
    <p class="lead">I am a Ph.D. candidate in Engineering at Chung-Ang University, advised by Prof. Mucheol Kim. My doctoral research studies how trained graph neural networks can respond to deletion requests efficiently and transparently. The work connects natural-language request interpretation, localized model updating, privacy evaluation, and explanation-based verification.</p>
    <p class="lead">My earlier training is in software engineering, including natural-language processing for requirements-derived test generation and more than four years of enterprise software development. This background informs my broader interest in AI systems that are dependable, maintainable, and responsive to user and regulatory requirements.</p>
  </section>

  <section id="research">
    <h2>Research Interests</h2>
    <div class="grid-4">
      <div class="card">
        <h3>Trustworthy Graph Machine Learning</h3>
        <p>Reliable graph representation learning, robust evaluation, fairness, safety, and responsible use of relational models.</p>
      </div>
      <div class="card">
        <h3>Machine Unlearning and Privacy</h3>
        <p>Efficient deletion, retrain fidelity, membership-inference evaluation, privacy-aware model maintenance, and regulatory requirements.</p>
      </div>
      <div class="card">
        <h3>Explainable and Auditable AI</h3>
        <p>Attribution analysis, local structural explanations, human-readable verification, and evidence for model accountability.</p>
      </div>
      <div class="card">
        <h3>AI Software Engineering</h3>
        <p>Requirements-aware AI, benchmark design, reproducible artifacts, model-update workflows, and dependable AI system evolution.</p>
      </div>
    </div>
  </section>

  <section id="news">
    <h2>Recent News</h2>
    <div class="news-item"><span class="date">June 2026</span>Successfully completed my Ph.D. dissertation defense.</div>
    <div class="news-item"><span class="date">2026</span><em>From Random Forget-Sets to Realistic Natural-Language Deletion Requests</em> published at The ACM Web Conference (WWW).</div>
    <div class="news-item"><span class="date">2026</span><em>Forget and Explain: Transparent Verification of GNN Unlearning</em> published at ACM WSDM.</div>
    <div class="news-item"><span class="date">2025</span><em>GNN Unlearning Reality Checklist</em> presented at ICTC.</div>
  </section>

  <section id="publications">
    <h2>Selected Publications</h2>

    <div class="publication">
      <div class="publication-title">Forget and Explain: Transparent Verification of GNN Unlearning <span class="venue">WSDM 2026</span></div>
      <div class="publication-meta"><strong>Imran Ahsan</strong>, Hyunwook Yu, Jinsung Kim, and Mucheol Kim. Proceedings of the Nineteenth ACM International Conference on Web Search and Data Mining, pp. 1063–1067.</div>
      <div class="paper-links"><a href="https://doi.org/10.1145/3773966.3779386" target="_blank" rel="noopener">DOI</a></div>
    </div>

    <div class="publication">
      <div class="publication-title">From Random Forget-Sets to Realistic Natural-Language Deletion Requests <span class="venue">WWW 2026</span></div>
      <div class="publication-meta"><strong>Imran Ahsan</strong>, Jinsung Kim, and Mucheol Kim. Proceedings of The ACM Web Conference 2026, pp. 8741–8744.</div>
      <div class="paper-links"><a href="https://doi.org/10.1145/3774904.3792954" target="_blank" rel="noopener">DOI</a></div>
    </div>

    <div class="publication">
      <div class="publication-title">GNN Unlearning Reality Checklist: A Standard for Robust, Reproducible, and Privacy-Safe Evaluation <span class="venue">ICTC 2025</span></div>
      <div class="publication-meta"><strong>Imran Ahsan</strong>, Hyunwook Yu, and Mucheol Kim. 16th International Conference on Information and Communication Technology Convergence, pp. 874–876.</div>
    </div>

    <div class="publication">
      <div class="publication-title">Unlocking the Power of Graph Neural Networks: A Systematic Literature Review of Application-Oriented GNN Studies <span class="venue">Accepted</span></div>
      <div class="publication-meta"><strong>Imran Ahsan</strong>, Muhammad Waseem Anwar, JungYoon Kim, and Mucheol Kim. Computer Modeling in Engineering &amp; Sciences.</div>
    </div>

    <div class="publication">
      <div class="publication-title">The Semantic Design Space of Retrieval-Augmented Recommender Systems: A Systematic Review of LLM-Based Approaches <span class="venue">Accepted</span></div>
      <div class="publication-meta">Minhyeok Choi, <strong>Imran Ahsan</strong>, Hyunwook Yu, Taeyoung Choe, and Mucheol Kim. Computers, Materials &amp; Continua.</div>
    </div>

    <div class="notice">A complete and current publication list is available on my <a href="https://scholar.google.com/citations?user=h_P3dAkAAAAJ&hl=en" target="_blank" rel="noopener">Google Scholar profile</a>.</div>
  </section>

  <section id="projects">
    <h2>Research Highlights</h2>
    <div class="grid-2">
      <div class="card">
        <h3>Text2Forget</h3>
        <p>A request-driven benchmark that translates natural-language deletion requests into executable graph targets through lexical and semantic resolution.</p>
        <div class="keyword-row"><span class="keyword">WWW 2026</span><span class="keyword">Requirements-aware AI</span><span class="keyword">Benchmark design</span></div>
      </div>
      <div class="card">
        <h3>NodeVanisher</h3>
        <p>A localized graph-unlearning method based on deletion-aware subgraph extraction, capped neighbor sampling, and efficient refinement from a pretrained model.</p>
        <div class="keyword-row"><span class="keyword">Graph unlearning</span><span class="keyword">Efficiency</span><span class="keyword">Scalability</span></div>
      </div>
      <div class="card">
        <h3>Forget and Explain</h3>
        <p>An explainability-driven verification framework that compares pre- and post-unlearning evidence to diagnose residual direct and neighborhood influence.</p>
        <div class="keyword-row"><span class="keyword">WSDM 2026</span><span class="keyword">XAI</span><span class="keyword">Auditability</span></div>
      </div>
      <div class="card">
        <h3>GNN Unlearning Reality Checklist</h3>
        <p>A structured evaluation checklist for realistic threat models, reproducible experiments, privacy diagnostics, and robust graph-unlearning assessment.</p>
        <div class="keyword-row"><span class="keyword">ICTC 2025</span><span class="keyword">Reproducibility</span><span class="keyword">Evaluation</span></div>
      </div>
    </div>
  </section>

  <section id="experience">
    <h2>Education and Experience</h2>
    <div class="grid-2">
      <div>
        <div class="timeline-item">
          <div class="timeline-title">Ph.D. in Engineering</div>
          <div class="timeline-meta">Chung-Ang University, South Korea · 2023–2026</div>
          <div>Defense completed in June 2026; expected graduation August 2026. Advisor: Prof. Mucheol Kim.</div>
        </div>
        <div class="timeline-item">
          <div class="timeline-title">M.S. in Software Engineering</div>
          <div class="timeline-meta">National University of Sciences and Technology, Pakistan · 2014–2017</div>
          <div>Thesis: Automated Test Case Generation from User Specifications using NLP.</div>
        </div>
        <div class="timeline-item">
          <div class="timeline-title">B.S. in Software Engineering</div>
          <div class="timeline-meta">International Islamic University Islamabad, Pakistan · 2009–2013</div>
        </div>
      </div>
      <div>
        <div class="timeline-item">
          <div class="timeline-title">Ph.D. Researcher</div>
          <div class="timeline-meta">Data Intelligence Laboratory, Chung-Ang University · 2023–Present</div>
          <div>Research on trustworthy graph learning, machine unlearning, explainability, privacy, and benchmark design.</div>
        </div>
        <div class="timeline-item">
          <div class="timeline-title">Lecturer in Computer Science</div>
          <div class="timeline-meta">National University of Modern Languages, Pakistan · 2017–2023</div>
          <div>Teaching, curriculum contribution, student mentoring, and final-year project supervision.</div>
        </div>
        <div class="timeline-item">
          <div class="timeline-title">Software Developer</div>
          <div class="timeline-meta">Enterprise software development · 4+ years</div>
          <div>Developed ASP.NET systems for admissions, student services, HR, university portals, and business workflows.</div>
        </div>
      </div>
    </div>
  </section>

  <section id="teaching">
    <h2>Teaching</h2>
    <p class="lead">My teaching experience includes programming fundamentals, object-oriented programming, Java, C#, software engineering, database-backed application development, and project supervision. I use practical assignments and iterative feedback to connect core concepts with complete software systems.</p>
  </section>

  <section id="methods">
    <h2>Methods and Tools</h2>
    <div class="keyword-row">
      <span class="keyword">Python</span><span class="keyword">PyTorch</span><span class="keyword">PyTorch Geometric</span><span class="keyword">Graph Neural Networks</span><span class="keyword">Explainable AI</span><span class="keyword">Machine Unlearning</span><span class="keyword">NLP</span><span class="keyword">Benchmark Design</span><span class="keyword">Membership-Inference Evaluation</span><span class="keyword">C# / ASP.NET</span><span class="keyword">SQL</span><span class="keyword">Git</span><span class="keyword">LaTeX</span>
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:Imranahsan23@gmail.com">Imranahsan23@gmail.com</a></p>
    <p>Google Scholar: <a href="https://scholar.google.com/citations?user=h_P3dAkAAAAJ&hl=en" target="_blank" rel="noopener">scholar.google.com/citations?user=h_P3dAkAAAAJ</a></p>
    <p>GitHub: <a href="https://github.com/ImranAhsan23" target="_blank" rel="noopener">github.com/ImranAhsan23</a></p>
    <p>LinkedIn: <a href="https://www.linkedin.com/in/imran-ahsan-7042365a/" target="_blank" rel="noopener">linkedin.com/in/imran-ahsan-7042365a</a></p>
  </section>
</main>

<footer>
  <div class="container">© 2026 Imran Ahsan · Last updated June 2026</div>
</footer>
