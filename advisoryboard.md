---
layout: default
title: "Advisory Board"
---

<h1>WiCS-Europe Advisory Board</h1>

<p>
  INTRODUCTION TO THE ADVISORY BOARD
</p>

<div class="leaders-grid">

  <div class="leader-card">
    <a class="leader-link"
       href="https://www.memoryugr.es/people/ma-teresa-bajo/"
       target="_blank"
       rel="noopener noreferrer"
       aria-label="Visit personal page of Teresa Bajo">

      <img
        src="{{ '/advisory-board-images/TeresaBajo.jpg' | relative_url }}"
        alt="Teresa Bajo"
        class="leader-card-photo"
        loading="lazy">

      <h2 class="leader-name">Teresa Bajo</h2>
      <p class="leader-pronouns">N/A</p>
      <p class="leader-affil">University of Granada, Spain</p>

    </a>
  </div>

</div>


<style>
/* GRID: 4 columns on desktop */
.leaders-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 1.5rem;
  margin-top: 2rem;
}

/* Tablet: 2 columns */
@media (max-width: 900px) {
  .leaders-grid {
    grid-template-columns: repeat(2, 1fr);
  }
}

/* Mobile: 1 column */
@media (max-width: 560px) {
  .leaders-grid {
    grid-template-columns: 1fr;
  }
}

/* Card */
.leader-card {
  border-radius: 14px;
  background: #ffffff;
  padding: 1rem 0.75rem;
  text-align: center;

  /* 🔵 */
  box-shadow:
    0 4px 12px rgba(0, 102, 204, 0.15),
    0 0 0 1px rgba(0, 102, 204, 0.08);

  transition: transform 0.15s ease, box-shadow 0.15s ease;
}

.leader-card:hover {
  transform: translateY(-2px);
  box-shadow:
    0 8px 18px rgba(0, 102, 204, 0.25),
    0 0 0 1px rgba(0, 102, 204, 0.15);
}

/* FOTO */
.leader-card-photo {
  width: 110px;   
  height: 110px;
  object-fit: cover;
  object-position: center;
  border-radius: 50%;
  display: block;
  margin: 0 auto 0.6rem;
  background: #f2f6fb;
}

/* Text */
.leader-name {
  margin: 0.2rem 0 0.15rem;
  font-size: 1.02rem;
}

.leader-pronouns {
  margin: 0 0 0.3rem;
  font-size: 0.85rem;
  font-style: italic;
  opacity: 0.75;
}

.leader-affil {
  margin: 0;
  font-size: 0.9rem;
  opacity: 0.8;
}
</style>

