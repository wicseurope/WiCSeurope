---
layout: default
title: "Leadership Team"
---

<h1>WiCS-Europe Leadership Team</h1>

<p>
  Meet the current WiCS+E leadership team, working to promote equity, diversity and inclusion
  in cognitive science across Europe.
</p>

<div class="leaders-grid">

  <div class="leader-card">
    <a class="leader-link"
       href="{{ '/leadershipteam-bios/Nura-Sidarus.html' | relative_url }}">
      <img
        src="{{ '/leadershipteam-images/NuraSidarus.jpg' | relative_url }}"
        alt="Nura Sidarus"
        class="leader-card-photo"
        loading="lazy">
      <h2 class="leader-name">Nura Sidarus</h2>
      <p class="leader-pronouns">N/A</p>
      <p class="leader-affil">Royal Holloway University of London, UK</p>
      <p class="leader-pos">Chair</p>
    </a>
  </div>

  <div class="leader-card">
    <a class="leader-link"
       href="{{ '/leadershipteam-bios/MJ-Maraver.html' | relative_url }}">
      <img
        src="{{ '/leadershipteam-images/MJMaraver.jpg' | relative_url }}"
        alt="María Jesús Maraver"
        class="leader-card-photo"
        loading="lazy">
      <h2 class="leader-name">María Jesús Maraver</h2>
      <p class="leader-pronouns">She/Her</p>
      <p class="leader-affil">University of Jaén, Spain</p>
      <p class="leader-pos">Co-Chair</p>
    </a>
  </div>

  <div class="leader-card">
    <a class="leader-link"
       href="{{ '/leadershipteam-bios/Matilde-Simonetti.html' | relative_url }}">
      <img
        src="{{ '/leadershipteam-images/MatildeSimonetti.jpg' | relative_url }}"
        alt="Matilde Simonetti"
        class="leader-card-photo"
        loading="lazy">
      <h2 class="leader-name">Matilde Simonetti</h2>
      <p class="leader-pronouns">She/Her</p>
      <p class="leader-affil">RWTH Aachen University, Germany</p>
      <p class="leader-pos">Communication Coordinator: Linkedin and Website</p>
    </a>
  </div>

  <div class="leader-card">
    <a class="leader-link"
       href="{{ '/leadershipteam-bios/Marta-Rivera.html' | relative_url }}">
      <img
        src="{{ '/leadershipteam-images/MartaRivera.jpg' | relative_url }}"
        alt="Marta Rivera"
        class="leader-card-photo"
        loading="lazy">
      <h2 class="leader-name">Marta Rivera</h2>
      <p class="leader-pronouns">She/Her</p>
      <p class="leader-affil">University of The Balearic Islands, Spain</p>
      <p class="leader-pos">Communication Coordinator: BlueSky and Website</p>
    </a>
  </div>

  <div class="leader-card">
    <a class="leader-link"
       href="{{ '/leadershipteam-bios/Rachelle-Ho.html' | relative_url }}">
      <img
        src="{{ '/leadershipteam-images/RachelleHo.jpeg' | relative_url }}"
        alt="Rachelle Ho"
        class="leader-card-photo"
        loading="lazy">
      <h2 class="leader-name">Rachelle Ho</h2>
      <p class="leader-pronouns">N/A</p>
      <p class="leader-affil">University of Aberdeen, Scotland</p>
    </a>
  </div>

  <div class="leader-card">
    <a class="leader-link"
       href="{{ '/leadershipteam-bios/Alicia-Luque.html' | relative_url }}">
      <img
        src="{{ '/leadershipteam-images/AliciaLuque.jpg' | relative_url }}"
        alt="Alicia Luque"
        class="leader-card-photo"
        loading="lazy">
      <h2 class="leader-name">Alicia Luque</h2>
      <p class="leader-pronouns">N/A</p>
      <p class="leader-affil">Nebrija University, Spain</p>
    </a>
  </div>

  <div class="leader-card">
    <a class="leader-link"
       href="{{ '/leadershipteam-bios/Andrea-Kiesel.html' | relative_url }}">
      <img
        src="{{ '/leadershipteam-images/AndreaKiesel.png' | relative_url }}"
        alt="Andrea Kiesel"
        class="leader-card-photo"
        loading="lazy">
      <h2 class="leader-name">Andrea Kiesel</h2>
      <p class="leader-pronouns">N/A</p>
      <p class="leader-affil">University of Freiburg, Germany</p>
    </a>
  </div>

  <div class="leader-card">
    <a class="leader-link"
       href="{{ '/leadershipteam-bios/Ronja-Mueller.html' | relative_url }}">
      <img
        src="{{ '/leadershipteam-images/RonjaMueller.JPG' | relative_url }}"
        alt="Ronja Mueller"
        class="leader-card-photo"
        loading="lazy">
      <h2 class="leader-name">Ronja Mueller</h2>
      <p class="leader-pronouns">N/A</p>
      <p class="leader-affil">Medical School Hamburg, Germany</p>
    </a>
  </div>

  <div class="leader-card">
    <a class="leader-link"
       href="{{ '/leadershipteam-bios/Zofia-Wodniecka.html' | relative_url }}">
      <img
        src="{{ '/leadershipteam-images/Zofia-Wodniecka.jpg' | relative_url }}"
        alt="Zofia Wodniecka"
        class="leader-card-photo"
        loading="lazy">
      <h2 class="leader-name">Zofia Wodniecka</h2>
      <p class="leader-pronouns">N/A</p>
      <p class="leader-affil">Jagiellonian University, Poland</p>
    </a>
  </div>

</div>

<style>
/* GRID: 3 columnas en desktop */
.leaders-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1.5rem;
  margin-top: 2rem;
}

/* Tablet */
@media (max-width: 900px) {
  .leaders-grid {
    grid-template-columns: repeat(2, 1fr);
  }
}

/* Mobile */
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

  /* ✅ color base para que el "inherit" sea estable */
  color: #222;

  /* 🔵 sombra azul */
  box-shadow:
    0 4px 12px rgba(0, 102, 204, 0.15),
    0 0 0 1px rgba(0, 102, 204, 0.08);

  transition: transform 0.15s ease, box-shadow 0.15s ease;
}

/* Hover: un pelín más marcada */
.leader-card:hover {
  transform: translateY(-2px);
  box-shadow:
    0 8px 18px rgba(0, 102, 204, 0.25),
    0 0 0 1px rgba(0, 102, 204, 0.15);
}

/* ✅ Enlace: forzar todas las pseudoclases (incluye visited) */
.leader-link,
.leader-link:link,
.leader-link:visited,
.leader-link:hover,
.leader-link:active,
.leader-link:focus {
  text-decoration: none;
  color: inherit;
  display: block;
  outline: none;
}

/* FOTO */
.leader-card-photo {
  width: 120px;
  height: 120px;
  object-fit: cover;
  object-position: center;
  border-radius: 50%;
  display: block;
  margin: 0 auto 0.6rem;
  background: #f2f6fb;
}

/* Texto */
.leader-name {
  margin: 0.2rem 0 0.15rem;
  font-size: 1.05rem;
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

.leader-pos {
  margin: 0.35rem 0 0;
  font-size: 0.9rem;
  opacity: 0.9;
}
</style>
