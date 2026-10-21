---
layout: default
title: "Resources"
---

<h1>Resources</h1>

<h2>Ongoing Writing groups at the WiCS+ Network</h2>
<p>
The Fall 2026 writing groups will begin on September 15, 2026. These drop-in sessions are open to everyone, with no prior commitment required. You are welcome to join as frequently or infrequently as your schedule allows.
</p>

<p>
Sessions provide an encouraging environment to share your writing goals, followed by quiet, camera-off writing time with accountability.
</p>

<ul>
  <li>Mondays 10 am–12 noon ET / 16:00–18:00 CEST</li>
  <li>Wednesdays 1–3 pm ET / 19:00–21:00 CEST</li>
  <li>Fridays 10 am–12 noon ET / 16:00–18:00 CEST</li>
  <li>Fridays 1–3 pm ET / 19:00–21:00 CEST</li>
</ul>

<p>
You can sign up <a href="https://docs.google.com/forms/d/e/1FAIpQLScnotepQuc8T7RP6wCXWU9ixTHRF1AiJkM5lPCNa2Yq_fUJvw/viewform">here</a>.
</p>

<p>
This is a regular activity in the network. Stay tuned for future editions.
</p>

<h2>Events' Resources </h2>
<p>
  Here you can find the resources shared during WiCS+E events
</p>
<div class="event-card featured">
  <a class="event-link"
     href="{{ '/resources/2026_march_computational_skills' | relative_url }}">

    <img src="{{ '/events-images/february_2026.png' | relative_url }}"
         alt="Building Inclusive Computational Skills flyer"
         class="event-photo">

    <h2 class="event-title">Building Inclusive Computational Skills</h2>

    <p class="event-subtitle">
      Online panel · International Women’s Month
    </p>

    <p class="event-meta">
    Check Resources
    </p>

  </a>
</div>

<div class="event-card featured">
  <a class="event-link"
     href="{{ '/resources/2026_psychopyforwics' | relative_url }}">

    <img src="{{ '/events-images/psychopy_2026.png' | relative_url }}"
         alt="Building Inclusive Computational Skills flyer"
         class="event-photo">

    <h2 class="event-title">PsychoPy for Women in Cognitive Science (WiCS) – Resources</h2>

    <p class="event-subtitle">
     Collaborative Workshop Series
    </p>

    <p class="event-meta">
    Check Resources
    </p>

  </a>
</div>

<style>
/* GRID */
.events-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1.5rem;
  margin-top: 1.5rem;
}

/* Tablet */
@media (max-width: 900px) {
  .events-grid {
    grid-template-columns: repeat(2, 1fr);
  }
}

/* Mobile */
@media (max-width: 560px) {
  .events-grid {
    grid-template-columns: 1fr;
  }
}

/* CARD */
.event-card {
  border-radius: 14px;
  background: #ffffff;
  padding: 1.2rem 1rem;
  text-align: center;

  box-shadow:
    0 4px 12px rgba(0, 102, 204, 0.15),
    0 0 0 1px rgba(0, 102, 204, 0.08);

  transition: transform 0.15s ease, box-shadow 0.15s ease;
}

.event-card:hover {
  transform: translateY(-2px);
  box-shadow:
    0 8px 18px rgba(0, 102, 204, 0.25),
    0 0 0 1px rgba(0, 102, 204, 0.15);
}

.event-link,
.event-card-inner {
  text-decoration: none;
  color: inherit;
  display: block;
}

/* OPTIONAL IMAGE (for later) */
.event-photo {
  width: 100%;
  height: 140px;
  object-fit: cover;
  border-radius: 10px;
  margin-bottom: 0.6rem;
  background: #f2f6fb;
}

/* TEXT */
.event-title {
  margin: 0.2rem 0 0.4rem;
  font-size: 1.05rem;
}

.event-subtitle {
  margin: 0 0 0.4rem;
  font-size: 0.9rem;
  font-style: italic;
  opacity: 0.75;
}

.event-meta {
  margin: 0;
  font-size: 0.9rem;
  opacity: 0.85;
}

  /* FEATURED (NEXT) EVENT */
.event-card.featured {
  grid-column: span 3;
  padding: 2rem 2.2rem;
}

.event-card.featured .event-photo {
  height: auto;
  max-height: 420px;
  object-fit: contain;
}

.event-card.featured .event-title {
  font-size: 1.6rem;
}

.event-card.featured .event-subtitle {
  font-size: 1.05rem;
}

.event-card.featured .event-meta {
  font-size: 1rem;
}

/* Responsive: featured event still looks good on smaller screens */
@media (max-width: 900px) {
  .event-card.featured {
    grid-column: span 2;
  }
}

@media (max-width: 560px) {
  .event-card.featured {
    grid-column: span 1;
  }
}
</style>
