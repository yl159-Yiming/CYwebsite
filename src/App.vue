<template>
  <div class="page">
    <!-- Top header bar -->
    <header class="site-header">
      <div class="site-header__inner">
        <div>
          <h1 class="name">Yiming Li</h1>
          <p class="role">Quant / Energy Markets · Data &amp; Optimization</p>
          <p class="location">Dallas · United States</p>
        </div>

        <div class="header-right">
          <nav class="nav">
            <a href="#about">About</a>
            <a href="#research">Research</a>
            <a href="#projects">Projects</a>
            <a href="#teaching">Teaching</a>
            <a href="#misc">Misc</a>
          </nav>
          <div class="social">
            <a href="mailto:you@example.com">Email</a>
            <span>·</span>
            <a href="https://github.com/yl159-Yiming" target="_blank" rel="noreferrer">GitHub</a>
            <!-- add LinkedIn/Scholar later -->
          </div>
        </div>
      </div>
    </header>

    <!-- Main content, wide -->
    <main class="content">
      <!-- About -->
      <section id="about" class="section section--wide">
        <div class="section-two-col">
          <div>
            <h2>About</h2>
            <p>
              I work on problems at the intersection of power markets, quantitative
              modeling, and data infrastructure. My current focus is on building tools
              for nodal congestion forecasting, unit commitment modeling, and
              trading analytics in PJM and ERCOT.
            </p>
            <p>
              On the engineering side, I design and maintain multi-VM GCP
              environments with shared Python stacks, JupyterHub, MariaDB, and
              BigQuery. I enjoy turning messy data and legacy systems into
              reproducible research pipelines.
            </p>
            <p>
              When I am not debugging solvers or cloud configs, I am probably on a
              tennis court or experimenting with automation scripts for everyday
              tasks.
            </p>
          </div>

          <!-- Sample profile / illustration image -->
          <div class="about-image-wrap">
            <img
                class="about-image"
                src="https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=900&q=80"
                alt="Code and workspace illustration"
            />
          </div>
        </div>
      </section>

      <!-- Research -->
      <section id="research" class="section">
        <h2>Research &amp; Notes</h2>

        <article class="entry entry--with-link">
          <div>
            <h3>Unit Commitment Toy Models in PyPSA</h3>
            <p class="entry-meta">Work in progress</p>
            <p>
              Small but fully specified networks for studying unit commitment,
              reserve constraints, and congestion in a controlled environment.
              Used as a sandbox to understand how different modeling choices
              affect LMPs and flows.
            </p>
          </div>
          <a href="#" class="entry-link">Sample link</a>
        </article>

        <article class="entry entry--with-link">
          <div>
            <h3>Notes on Dual Variables and Congestion</h3>
            <p class="entry-meta">Research notes</p>
            <p>
              Informal write-ups on how dual variables in LP and MIP models
              relate to congestion prices, path-based representations, and
              edge-additive rewards in power systems.
            </p>
          </div>
          <a href="#" class="entry-link">PDF (placeholder)</a>
        </article>

        <article class="entry entry--with-link">
          <div>
            <h3>Data Pipelines for PJM and ERCOT</h3>
            <p class="entry-meta">Technical notes</p>
            <p>
              Sketches for robust pipelines that pull data from PJM Data Miner 2,
              eDART, and ERCOT interfaces, with an emphasis on reproducibility and
              cost-aware cloud storage.
            </p>
          </div>
          <a
              href="https://github.com/yl159-Yiming"
              target="_blank"
              rel="noreferrer"
              class="entry-link"
          >
            View on GitHub
          </a>
        </article>
      </section>

      <!-- Projects with images, full width grid -->
      <section id="projects" class="section section--wide">
        <h2>Selected Projects</h2>

        <div class="projects-grid">
          <article class="project-card">
            <img
                class="project-image"
                src="https://images.unsplash.com/photo-1582719478250-c89cae4dc85b?auto=format&fit=crop&w=900&q=80"
                alt="Power grid illustration"
            />
            <div class="project-body">
              <h3>PJM Congestion Analytics Platform</h3>
              <p class="entry-meta">Ongoing</p>
              <p>
                An internal platform that ingests market, topology, and outage data
                to produce nodal-level analytics and bidding signals, built around
                PyPSA and custom optimization tooling.
              </p>
              <div class="project-links">
                <a href="#" class="pill-link">Demo (placeholder)</a>
                <a href="https://github.com/yl159-Yiming" target="_blank" rel="noreferrer" class="pill-link">
                  Code on GitHub
                </a>
              </div>
            </div>
          </article>

          <article class="project-card">
            <img
                class="project-image"
                src="https://images.unsplash.com/photo-1553877522-43269d4ea984?auto=format&fit=crop&w=900&q=80"
                alt="Cloud infrastructure"
            />
            <div class="project-body">
              <h3>GCP Migration &amp; Shared Python Stack</h3>
              <p class="entry-meta">Infrastructure</p>
              <p>
                Migration of a legacy CentOS / MariaDB environment to Ubuntu with
                uv-managed Python, shared /opt virtualenvs, JupyterHub, and
                automated backups for databases and notebooks.
              </p>
              <div class="project-links">
                <a href="#" class="pill-link">Architecture notes</a>
              </div>
            </div>
          </article>

          <article class="project-card">
            <img
                class="project-image"
                src="https://images.unsplash.com/photo-1587502536502-1643f2f25c88?auto=format&fit=crop&w=900&q=80"
                alt="Tennis court"
            />
            <div class="project-body">
              <h3>Tennis Court Auto-Booking Bot</h3>
              <p class="entry-meta">Side project</p>
              <p>
                A Playwright-based script that logs into a city reservation system,
                searches for specific courts and time slots, and books reservations
                automatically under configurable rules.
              </p>
              <div class="project-links">
                <a href="#" class="pill-link">Read more</a>
              </div>
            </div>
          </article>
        </div>
      </section>

      <!-- Teaching -->
      <section id="teaching" class="section">
        <h2>Teaching &amp; Mentoring</h2>
        <p>
          I informally mentor friends and colleagues on topics like Python tooling,
          version control, and reproducible research environments. From time to
          time I also help people set up cloud-hosted Jupyter environments and
          guide them through performance debugging in PyPSA.
        </p>
      </section>

      <!-- Misc -->
      <section id="misc" class="section">
        <h2>Miscellaneous</h2>
        <p>
          This website is a static single-page app built with Vue 3 and Vite, and
          deployed via GitHub Pages. The source code lives in the
          <a
              href="https://github.com/yl159-Yiming/CYwebsite"
              target="_blank"
              rel="noreferrer"
          >
            repository
          </a>.
        </p>
        <p>
          You can reach me at
          <a href="mailto:you@example.com">you@example.com</a> for questions,
          collaborations, or just to talk about power systems and tennis.
        </p>
      </section>
    </main>
  </div>
</template>

<script setup>
// no logic needed yet
</script>

<style scoped>
.page {
  min-height: 100vh;
  padding: 0;
  margin: 0;
  font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI",
  sans-serif;
  background: #f3f4f6;
  color: #111827;
}

/* Header: full-width band */

.site-header {
  background: #ffffff;
  border-bottom: 1px solid #e5e7eb;
  box-shadow: 0 1px 3px rgba(15, 23, 42, 0.06);
}

.site-header__inner {
  /* 🔴 removed max-width: 1200px */
  width: 100%;
  margin: 0;
  padding: 1.5rem 3rem;
  display: flex;
  justify-content: space-between;
  gap: 2rem;
  align-items: center;
}

.name {
  font-size: 2.3rem;
  font-weight: 700;
  margin: 0;
}

.role {
  margin: 0.2rem 0 0.1rem;
  font-size: 1rem;
  color: #4b5563;
}

.location {
  margin: 0.1rem 0 0;
  font-size: 0.9rem;
  color: #6b7280;
}

.header-right {
  display: flex;
  flex-direction: column;
  align-items: flex-end;
  gap: 0.4rem;
}

.nav {
  display: flex;
  flex-wrap: wrap;
  gap: 1.2rem;
  font-size: 0.95rem;
}

.nav a {
  text-decoration: none;
  color: #4b5563;
}

.nav a:hover {
  color: #111827;
}

.social {
  font-size: 0.9rem;
  color: #4b5563;
}

.social a {
  color: #2563eb;
  text-decoration: none;
}

.social a:hover {
  text-decoration: underline;
}

/* Content */

.content {
  /* 🔴 removed max-width: 1200px */
  width: 100%;
  margin: 1.75rem 0 2.5rem;
  padding: 0 3rem; /* just some side padding so it’s not glued to the edge */
  display: flex;
  flex-direction: column;
  gap: 1.75rem;
}

.section {
  background: #ffffff;
  border-radius: 0.9rem;
  padding: 1.6rem 1.7rem;
  border: 1px solid #e5e7eb;
  box-shadow: 0 1px 2px rgba(15, 23, 42, 0.04);
}

.section--wide {
  padding: 1.8rem 2rem;
}

.section h2 {
  margin: 0 0 0.9rem;
  font-size: 1.5rem;
}

.section p {
  margin: 0.5rem 0;
  color: #4b5563;
  line-height: 1.6;
}

/* About two-column layout */

.section-two-col {
  display: grid;
  grid-template-columns: minmax(0, 2fr) minmax(260px, 1.3fr);
  gap: 1.75rem;
  align-items: center;
}

.about-image-wrap {
  display: flex;
  justify-content: flex-end;
}

.about-image {
  width: 100%;
  max-width: 360px;
  border-radius: 1.2rem;
  object-fit: cover;
  box-shadow: 0 12px 30px rgba(15, 23, 42, 0.25);
}

/* Entries */

.entry {
  margin-top: 0.9rem;
}

.entry--with-link {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  gap: 1.5rem;
}

.entry h3 {
  margin: 0;
  font-size: 1.05rem;
}

.entry-meta {
  margin: 0.2rem 0 0.35rem;
  font-size: 0.85rem;
  color: #9ca3af;
}

.entry-link {
  font-size: 0.85rem;
  color: #2563eb;
  text-decoration: none;
  white-space: nowrap;
}

.entry-link:hover {
  text-decoration: underline;
}

/* Projects grid */

.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 1.2rem;
}

.project-card {
  background: #f9fafb;
  border-radius: 0.9rem;
  border: 1px solid #e5e7eb;
  overflow: hidden;
  display: flex;
  flex-direction: column;
  height: 100%;
}

.project-image {
  width: 100%;
  height: 160px;
  object-fit: cover;
}

.project-body {
  padding: 1rem 1.1rem 1.1rem;
}

.project-body h3 {
  margin: 0;
  font-size: 1.05rem;
}

.project-body p {
  margin: 0.4rem 0;
}

.project-links {
  margin-top: 0.5rem;
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
}

.pill-link {
  display: inline-block;
  padding: 0.25rem 0.7rem;
  border-radius: 999px;
  border: 1px solid #d1d5db;
  font-size: 0.8rem;
  text-decoration: none;
  color: #2563eb;
  background: #ffffff;
}

.pill-link:hover {
  background: #eff6ff;
}

/* Responsive */

@media (max-width: 900px) {
  .site-header__inner {
    flex-direction: column;
    align-items: flex-start;
    padding: 1.2rem 1.5rem;
  }

  .header-right {
    align-items: flex-start;
  }

  .content {
    padding: 0 1.5rem;
  }

  .section-two-col {
    grid-template-columns: minmax(0, 1fr);
  }

  .about-image-wrap {
    justify-content: flex-start;
  }
}

@media (max-width: 640px) {
  .content {
    margin-top: 1.3rem;
    padding: 0 1.2rem;
  }

  .section {
    padding: 1.3rem 1.25rem;
  }

  .name {
    font-size: 2rem;
  }
}
</style>


