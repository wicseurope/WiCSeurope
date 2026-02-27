---
layout: default
title: "Events"
---

<h1>WiCS+Europe Events</h1>

<p>
  WiCS+Europe organizes events dedicated to equity, diversity, inclusion, and professional
  development in cognitive science.
</p>

<h2>Next events</h2>

<p>
  Upcoming events will be announced soon.
</p>

<h2 style="margin-top: 3rem;">Last Event</h2>

<div class="event-card featured">
  <a class="event-link"
     href="{{ '/pastevents-summary/Building_Inclusive_Computational_Skills.html' | relative_url }}">

    <img src="{{ '/events-images/february_2026.png' | relative_url }}"
         alt="Building Inclusive Computational Skills flyer"
         class="event-photo">

    <h2 class="event-title">Building Inclusive Computational Skills</h2>

    <p class="event-subtitle">
      Online panel · International Women’s Month
    </p>

    <p class="event-meta">
      23 February 2026 · Online
    </p>

  </a>
</div>

<h2 style="margin-top: 3rem;">Past events</h2>

<div class="events-grid">

  <div class="event-card">
    <a class="event-link"
       href="{{ '/pastevents-summary/ESCOP-2025.html' | relative_url }}">
      <h2 class="event-title">WiCS+Europe at ESCOP2025</h2>
      <p class="event-subtitle">Creating inclusive and safe academic spaces</p>
      <p class="event-meta">Sheffield, UK · 2 September 2025</p>
    </a>
  </div>

  <div class="event-card">
    <a class="event-link"
       href="{{ '/pastevents-summary/gender-based-violence-academia.html' | relative_url }}">
      <h2 class="event-title">Addressing gender-based violence in academia</h2>
      <p class="event-subtitle">Online seminar</p>
      <p class="event-meta">10 March 2025</p>
    </a>
  </div>

  <div class="event-card">
    <a class="event-link"
       href="{{ '/pastevents-summary/inclusive-anti-racist-academia.html' | relative_url }}">
      <h2 class="event-title">Creating an Inclusive and Anti-racist Academia</h2>
      <p class="event-subtitle">Online panel discussion</p>
      <p class="event-meta">28 October 2024</p>
    </a>
  </div>

  <div class="event-card">
    <a class="event-link"
       href="{{ '/pastevents-summary/promote-equality.html' | relative_url }}">
      <h2 class="event-title">How to Promote Equality?</h2>
      <p class="event-subtitle">Celebrating Women Leaders in EDI</p>
      <p class="event-meta">March 2024 · Online</p>
    </a>
  </div>

  <div class="event-card">
    <a class="event-link"
       href="{{ '/pastevents-summary/ESCOP2023.html' | relative_url }}">
      <h2 class="event-title">Transitions in Career Paths</h2>
      <p class="event-subtitle">ESCOP 2023 Panel &amp; Speed Mentoring</p>
      <p class="event-meta">Porto, Portugal · 6 September 2023</p>
    </a>
  </div>

  <div class="event-card">
    <a class="event-link"
       href="{{ '/pastevents-summary/fast-lane-to-slow-science.html' | relative_url }}">
      <h2 class="event-title">Fast Lane to Slow Science</h2>
      <p class="event-subtitle">International Women’s Day panel</p>
      <p class="event-meta">20 March 2023 · Online</p>
    </a>
  </div>

  <div class="event-card">
    <a class="event-link"
       href="{{ '/pastevents-summary/lessons-pandemic.html' | relative_url }}">
      <h2 class="event-title">Lessons to Be Learned from the Pandemic</h2>
      <p class="event-subtitle">Online panel discussion</p>
      <p class="event-meta">28 November 2022</p>
    </a>
  </div>

  <div class="event-card">
    <a class="event-link"
       href="{{ '/pastevents-summary/running-your-new-lab.html' | relative_url }}">
      <h2 class="event-title">Running Your New Lab</h2>
      <p class="event-subtitle">Tips and tricks</p>
      <p class="event-meta">10 March 2022 · Online</p>
    </a>
  </div>

  <div class="event-card">
    <a class="event-link"
       href="{{ '/pastevents-summary/making-the-invisible-visible.html' | relative_url }}">
      <h2 class="event-title">Making the Invisible Visible</h2>
      <p class="event-subtitle">Panel &amp; Speed Mentoring</p>
      <p class="event-meta">vSARMAC</p>
    </a>
  </div>

  <div class="event-card">
    <a class="event-link"
       href="{{ '/pastevents-summary/sexual-harassment-academia.html' | relative_url }}">
      <h2 class="event-title">Sexual Harassment in Academia</h2>
      <p class="event-subtitle">Keynote lecture</p>
      <p class="event-meta">ESCOP 2019 · Tenerife</p>
    </a>
  </div>

  <div class="event-card">
    <a class="event-link"
       href="{{ '/pastevents-summary/negotiating-challenges-science.html' | relative_url }}">
      <h2 class="event-title">Negotiating Challenges to Scientific Advancement</h2>
      <p class="event-subtitle">Panel &amp; Speed Mentoring</p>
      <p class="event-meta">ICPS 2019 · Paris</p>
    </a>
  </div>

  <div class="event-card">
    <a class="event-link"
       href="{{ '/pastevents-summary/evidence-based-practices-wics.html' | relative_url }}">
      <h2 class="event-title">Evidence-Based Practices for Promoting Equality &amp; Diversity</h2>
      <p class="event-subtitle">Discussion with the founders of WiCS</p>
      <p class="event-meta">6 March 2019 · Paris</p>
    </a>
  </div>

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
