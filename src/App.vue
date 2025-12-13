<template>
  <div class="page">
    <!-- Top navigation bar -->
    <header class="top-nav">
      <div class="top-nav__inner">
        <div class="top-nav__brand">
          <a href="#about" class="brand-name">Tapi Tu</a>
        </div>
        <nav class="top-nav__links">
          <a href="#about">Home</a>
          <a href="#cv">CV</a>
          <a href="#working-papers">Working Papers</a>
          <a href="#work-in-progress">Work in Progress</a>
          <a href="#collaborative-research">Collaborative Research</a>
          <a href="#blog">Blog</a>
        </nav>
      </div>
    </header>

    <!-- Main content wrapper -->
    <main class="content">
      <!-- About / Biography section -->
      <section id="about" class="section section--about">
        <div class="about-grid">
          <!-- Left: photo and basic info -->
          <div class="about-left">
            <div class="profile-photo-wrap">
              <!-- TODO: replace src with your own headshot -->
              <img
                  class="profile-photo"
                  src="@/assets/rabbit_profile.png"
                  alt="Profile headshot placeholder"
              />
            </div>
            <div class="about-name-block">
              <h1 class="about-name">Tapi Tu</h1>
              <p class="about-title">Quantitative Researcher in Energy Markets</p>
              <p class="about-affiliation">Your Institution / Company</p>
            </div>
            <div class="about-icons">
              <!-- These can later be replaced with actual icons / svg -->
              <a href="https://google.com" class="about-icon-link">📧</a>
              <a href="https://google.com" class="about-icon-link">G</a>
              <a href="https://google.com" class="about-icon-link">in</a>
            </div>
          </div>

          <!-- Right: biography text -->
          <div class="about-right">
            <h2 class="section-heading">Biography</h2>
            <p>
              I am a researcher working at the intersection of power systems, energy
              markets, and quantitative modeling. My work focuses on nodal
              congestion, unit commitment, and the design of scalable
              optimization-based tools for electricity markets.
            </p>
            <p>
              I am particularly interested in how market design and network
              constraints interact, and how better models and infrastructure can
              improve bidding, hedging, and long-term planning in systems such as
              PJM and ERCOT.
            </p>
            <p>
              I was born and raised in &lt;your city / country&gt;, and outside of
              research I enjoy playing tennis and tinkering with automation
              scripts for everyday life.
            </p>
            <p class="cv-link-row">
              <span class="cv-icon">📄</span>
              <a id="cv" href="https://google.com" class="cv-link">
                Download my curriculum vitae (placeholder link).
              </a>
            </p>
          </div>
        </div>
      </section>

      <!-- Job Market Paper section -->
      <section id="job-market-paper" class="section section--two-col">
        <div class="section-label-col">
          <h2 class="section-heading">Job Market Paper</h2>
        </div>
        <div class="section-main-col">
          <h3 class="paper-title">
            Placeholder Title for Job Market Paper on Power Market Analytics
          </h3>
          <p class="paper-meta">Tapi Tu. (Data analysis in progress.)</p>
          <p>
            This is a placeholder abstract. Here you can describe the key
            question, contribution, and methods of your job market paper or a
            flagship project. For example, you might discuss new approaches for
            modeling long-run congestion patterns, integrating operational data
            with planning models, or identifying structural relationships in
            market outcomes.
          </p>
          <p>
            You can also briefly explain the empirical setting (e.g. PJM / ERCOT)
            and the main tools used (unit commitment models, network flow
            approximations, dual variables, etc.). Replace this text with your
            own abstract when ready.
          </p>
          <p class="last-updated">Last updated on &lt;date&gt;.</p>
        </div>
      </section>

      <!-- Publications section -->
      <section id="publications" class="section">
        <h2 class="section-heading">Publications</h2>

        <article class="paper-entry">
          <h3 class="paper-entry__title">
            <a href="https://google.com">Placeholder Publication on Congestion Measurement</a>
          </h3>
          <p class="paper-entry__meta">
            Tapi Tu. Journal / Conference Name, Volume / Year (forthcoming).
          </p>
          <p class="paper-entry__note">
            Short optional note or one-sentence summary of the paper.
          </p>
        </article>

        <article class="paper-entry">
          <h3 class="paper-entry__title">
            <a href="https://google.com">Another Placeholder Publication Title</a>
          </h3>
          <p class="paper-entry__meta">
            Tapi Tu and Coauthors. Outlet name, year.
          </p>
        </article>
      </section>

      <!-- Working Papers section -->
      <section id="working-papers" class="section">
        <h2 class="section-heading">Working Papers</h2>

        <article class="paper-entry">
          <h3 class="paper-entry__title">
            <a href="https://google.com">Identification in Nodal Power Markets under Network Constraints</a>
          </h3>
          <p class="paper-entry__meta">with Coauthor A and Coauthor B (Submitted).</p>
          <p class="paper-entry__update">Last updated on &lt;date&gt;.</p>
        </article>

        <article class="paper-entry">
          <h3 class="paper-entry__title">
            <a href="https://google.com">Placeholder Working Paper Title 2</a>
          </h3>
          <p class="paper-entry__meta">with Coauthor C (In progress).</p>
          <p class="paper-entry__update">Last updated on &lt;date&gt;.</p>
        </article>
      </section>

      <!-- Work in Progress section -->
      <section id="work-in-progress" class="section">
        <h2 class="section-heading">Work in Progress</h2>

        <article class="paper-entry">
          <h3 class="paper-entry__title">
            <a href="https://google.com">Using Historical Congestion to Design Hedging Strategies</a>
          </h3>
          <p class="paper-entry__meta">Tapi Tu.</p>
          <p class="paper-entry__update">Last updated on &lt;date&gt;.</p>
        </article>
      </section>

      <!-- collaborative projects -->
      <section id="collaborative-research" class="section">
        <h2 class="section-heading">Collaborative / Applied Research</h2>
        <p>
          This section can be used for applied or collaborative projects. You can briefly
          describe the collaboration and then list specific studies.
        </p>

        <article class="paper-entry">
          <h3 class="paper-entry__title">
            <a href="https://google.com">Placeholder Collaborative Project 1</a>
          </h3>
          <p class="paper-entry__meta">First author (Forthcoming in &lt;Journal&gt;).</p>
          <p class="paper-entry__update">Last updated on &lt;date&gt;.</p>
        </article>

        <article class="paper-entry">
          <h3 class="paper-entry__title">
            <a href="https://google.com">Placeholder Collaborative Project 2</a>
          </h3>
          <p class="paper-entry__update">Last updated on &lt;date&gt;.</p>
        </article>
      </section>

      <!-- Simple blog placeholder -->
      <section id="blog" class="section">
        <h2 class="section-heading">Blog</h2>
        <p>
          This is a placeholder for blog posts or informal notes. You can link to
          an external blog, or later render a list of posts generated from a
          Markdown directory or another system.
        </p>
      </section>

      <!-- Rabbit Section -->
      <section id="rabbit" class="section">
        <h2 class="section-heading">My Rabbit</h2>
        <p>
          What is the shape of my rabbit?
        </p>

        <div class="rabbit-gallery">
          <!-- Oval -->
          <div class="rabbit-item">
            <img
                src="@/assets/rabbit_oval.png"
                alt="Rabbit 1"
            />
            <p class="rabbit-caption">Oval</p>
            <button
                class="rabbit-choice-button"
                :class="{ selected: selectedShape === 'oval' }"
                @click="selectShape('oval')"
            >
              Choose this shape
            </button>
          </div>

          <!-- Hexagon -->
          <div class="rabbit-item">
            <img
                src="@/assets/rabbit_hexagon.png"
                alt="Rabbit 2"
            />
            <p class="rabbit-caption">Hexagon</p>
            <button
                class="rabbit-choice-button"
                :class="{ selected: selectedShape === 'hexagon' }"
                @click="selectShape('hexagon')"
            >
              Choose this shape
            </button>
          </div>

          <!-- Rectangle -->
          <div class="rabbit-item">
            <img
                src="@/assets/rabbit_rectangle.png"
                alt="Rabbit 3"
            />
            <p class="rabbit-caption">Rectangle</p>
            <button
                class="rabbit-choice-button"
                :class="{ selected: selectedShape === 'rectangle' }"
                @click="selectShape('rectangle')"
            >
              Choose this shape
            </button>
          </div>
        </div>

        <!-- Submit + message -->
        <div class="rabbit-actions">
          <button
              class="rabbit-submit-button"
              :disabled="!selectedShape"
              @click="submitVote"
          >
            Submit vote
          </button>
          <p v-if="message" class="rabbit-message">
            {{ message }}
          </p>
        </div>

        <!-- Previous / accumulated results -->
        <div class="rabbit-results" v-if="showResults && totalVotes > 0">
          <h3>Previous votes</h3>
          <ul>
            <li>Oval: {{ votes.oval }}</li>
            <li>Hexagon: {{ votes.hexagon }}</li>
            <li>Rectangle: {{ votes.rectangle }}</li>
            <li>Total votes: {{ totalVotes }}</li>
          </ul>
        </div>
      </section>

    </main>
  </div>
</template>

<script setup>
import { ref, computed, onMounted, watch } from 'vue'

const STORAGE_KEY = 'rabbit-votes-v1'

const selectedShape = ref(null) // 'oval' | 'hexagon' | 'rectangle' | null

// vote counts are kept and persisted in localStorage
const votes = ref({
  oval: 0,
  hexagon: 0,
  rectangle: 0,
})

const message = ref('')
// controls whether the results block is visible in the current session
const showResults = ref(false)

// Load previous votes from localStorage on mount
onMounted(() => {
  try {
    const raw = localStorage.getItem(STORAGE_KEY)
    if (raw) {
      const parsed = JSON.parse(raw)
      if (
          parsed &&
          typeof parsed === 'object' &&
          ['oval', 'hexagon', 'rectangle'].every(k => typeof parsed[k] === 'number')
      ) {
        votes.value = parsed
      }
    }
  } catch (e) {
    console.error('Failed to load rabbit votes from localStorage', e)
  }
})

// Persist votes whenever they change
watch(
    votes,
    (newVal) => {
      try {
        localStorage.setItem(STORAGE_KEY, JSON.stringify(newVal))
      } catch (e) {
        console.error('Failed to save rabbit votes to localStorage', e)
      }
    },
    { deep: true }
)

const totalVotes = computed(() =>
    votes.value.oval + votes.value.hexagon + votes.value.rectangle
)

function selectShape(shape) {
  selectedShape.value = shape
  message.value = '' // clear any old message
}

function submitVote() {
  if (!selectedShape.value) {
    message.value = 'Please choose a rabbit shape first.'
    return
  }

  votes.value[selectedShape.value] += 1

  const labelMap = {
    oval: 'Oval',
    hexagon: 'Hexagon',
    rectangle: 'Rectangle',
  }

  message.value = `You voted for ${labelMap[selectedShape.value]}!`
  showResults.value = true
}
</script>

<style scoped>
.page {
  min-height: 100vh;
  margin: 0;
  padding: 0;
  font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI",
  sans-serif;
  background: #f5f5f5;
  color: #1f2933;
}

/* Top navigation bar, similar spirit to the reference site */

.top-nav {
  background: #1f4f7b; /* deep blue */
  color: #ffffff;
  padding: 0.75rem 0;
}

.top-nav__inner {
  max-width: 1100px;
  margin: 0 auto;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0 1.5rem;
}

.brand-name {
  font-size: 1.3rem;
  font-weight: 600;
  color: #ffffff;
  text-decoration: none;
}

.top-nav__links {
  display: flex;
  flex-wrap: wrap;
  gap: 1.25rem;
  font-size: 0.95rem;
}

.top-nav__links a {
  color: #e5e7eb;
  text-decoration: none;
}

.top-nav__links a:hover {
  color: #ffffff;
  text-decoration: underline;
}

/* Main content wrapper */

.content {
  max-width: 1100px;
  margin: 2.5rem auto 3rem;
  padding: 0 1.5rem 3rem;
}

.section {
  background: #ffffff;
  border-radius: 0.4rem;
  padding: 1.75rem 2rem;
  box-shadow: 0 1px 3px rgba(15, 23, 42, 0.08);
}

.section + .section {
  margin-top: 2.25rem;
}

.section-heading {
  margin: 0 0 1.1rem;
  font-size: 1.5rem;
  font-weight: 600;
}

/* About / biography layout */

.section--about {
  padding-top: 2.25rem;
}

.about-grid {
  display: grid;
  grid-template-columns: minmax(0, 1.1fr) minmax(0, 1.4fr);
  gap: 2.5rem;
  align-items: flex-start;
}

.about-left {
  text-align: center;
}

.profile-photo-wrap {
  display: flex;
  justify-content: center;
  margin-bottom: 1.2rem;
}

.profile-photo {
  width: 220px;
  height: 220px;
  border-radius: 999px;
  object-fit: cover;
}

.about-name-block {
  margin-bottom: 0.75rem;
}

.about-name {
  margin: 0;
  font-size: 1.6rem;
  font-weight: 600;
}

.about-title {
  margin: 0.35rem 0 0.15rem;
  font-size: 0.95rem;
  color: #4b5563;
}

.about-affiliation {
  margin: 0;
  font-size: 0.95rem;
  color: #1f4f7b;
}

.about-icons {
  margin-top: 0.8rem;
  display: flex;
  justify-content: center;
  gap: 0.7rem;
}

.about-icon-link {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 34px;
  height: 34px;
  border-radius: 999px;
  border: 1px solid #d1d5db;
  text-decoration: none;
  font-size: 0.9rem;
  color: #1f4f7b;
}

.about-icon-link:hover {
  background: #edf2ff;
}

.about-right p {
  margin: 0 0 0.75rem;
  line-height: 1.7;
  color: #374151;
}

.cv-link-row {
  margin-top: 0.8rem;
  display: flex;
  align-items: center;
  gap: 0.4rem;
}

.cv-icon {
  font-size: 1rem;
}

.cv-link {
  color: #1f4f7b;
  text-decoration: none;
}

.cv-link:hover {
  text-decoration: underline;
}

/* Two-column sections (Job Market Paper) */

.section--two-col {
  display: grid;
  grid-template-columns: minmax(0, 0.9fr) minmax(0, 1.6fr);
  gap: 2.5rem;
}

.section-label-col {
  border-right: 1px solid #e5e7eb;
}

.section-label-col .section-heading {
  margin-top: 0.25rem;
}

.section-main-col {
  font-size: 0.98rem;
  color: #374151;
}

.section-main-col p {
  margin: 0 0 0.8rem;
  line-height: 1.7;
}

.paper-title {
  margin: 0 0 0.4rem;
  font-size: 1.2rem;
  font-weight: 600;
}

.paper-meta {
  margin: 0 0 0.75rem;
  font-size: 0.9rem;
  color: #6b7280;
}

.last-updated {
  margin-top: 0.4rem;
  font-size: 0.85rem;
  color: #9ca3af;
}

/* Paper / project entry styling used for many sections */

.paper-entry + .paper-entry {
  margin-top: 1.5rem;
}

.paper-entry__title {
  margin: 0 0 0.3rem;
  font-size: 1.05rem;
}

.paper-entry__title a {
  color: #1f4f7b;
  text-decoration: none;
}

.paper-entry__title a:hover {
  text-decoration: underline;
}

.paper-entry__meta {
  margin: 0 0 0.35rem;
  font-size: 0.9rem;
  color: #6b7280;
}

.paper-entry__note {
  margin: 0;
  font-size: 0.95rem;
  color: #374151;
}

.paper-entry__update {
  margin: 0;
  font-size: 0.85rem;
  color: #9ca3af;
}

/* Responsive tweaks */

@media (max-width: 900px) {
  .top-nav__inner {
    flex-direction: column;
    align-items: flex-start;
    gap: 0.6rem;
  }

  .about-grid,
  .section--two-col {
    grid-template-columns: minmax(0, 1fr);
  }

  .section-label-col {
    border-right: none;
    border-bottom: 1px solid #e5e7eb;
    margin-bottom: 1.3rem;
    padding-bottom: 0.8rem;
  }
}

@media (max-width: 640px) {
  .content {
    padding: 0 1rem 2.5rem;
  }

  .section {
    padding: 1.4rem 1.25rem;
  }

  .profile-photo {
    width: 190px;
    height: 190px;
  }
}

.rabbit-photo-wrap {
  margin-top: 1.2rem;
  display: flex;
  justify-content: center;
}

.rabbit-photo {
  width: 260px;
  height: 260px;
  object-fit: cover;
  border-radius: 1rem;
  box-shadow: 0 6px 18px rgba(0, 0, 0, 0.15);
}

.rabbit-gallery {
  margin-top: 1.5rem;
  display: grid;
  grid-template-columns: repeat(3, 1fr); /* widened cards */
  gap: 1.6rem; /* slightly larger spacing */
  justify-content: center; /* center the grid if total width is smaller */
}

.rabbit-item img {
  width: 100%;
  height: 250px;
  border-radius: 0.6rem;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.12);
}

.rabbit-caption {
  margin-top: 0.4rem;
  text-align: center;
  font-size: 0.9rem;
  color: #374151;
}

@media (max-width: 700px) {
  .rabbit-gallery {
    grid-template-columns: 1fr;
  }
}

.rabbit-choice-button {
  display: block;
  margin: 0.6rem auto 0;
  padding: 0.4rem 0.8rem;
  border-radius: 999px;
  border: 1px solid #d1d5db;
  background: #f9fafb;
  font-size: 0.85rem;
  cursor: pointer;
}

.rabbit-choice-button.selected {
  border-color: #1f4f7b;
  background: #e0ecff;
  font-weight: 600;
}

.rabbit-choice-button:hover {
  background: #edf2ff;
}

.rabbit-actions {
  margin-top: 1.5rem;
  display: flex;
  align-items: center;
  gap: 0.75rem;
}

.rabbit-submit-button {
  padding: 0.45rem 1.1rem;
  border-radius: 999px;
  border: none;
  background: #1f4f7b;
  color: #ffffff;
  font-size: 0.9rem;
  cursor: pointer;
}

.rabbit-submit-button:disabled {
  opacity: 0.5;
  cursor: not-allowed;
}

.rabbit-message {
  font-size: 0.9rem;
  color: #374151;
}

.rabbit-results {
  margin-top: 1.2rem;
  font-size: 0.9rem;
}

.rabbit-results ul {
  margin: 0.4rem 0 0;
  padding-left: 1.2rem;
}

</style>
