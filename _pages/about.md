---
permalink: /
title: "Yuanjian Li"
excerpt: "AI-driven resource coordination for air-ground integrated networks; publications and academic profile"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
.academic-home {
  --home-ink: #17324d;
  --home-muted: #5f7182;
  --home-accent: #087f8c;
  --home-accent-dark: #075f68;
  --home-pale: #eef8f8;
  --home-line: #c8d8df;
  --home-card: #ffffff;
  color: var(--home-ink);
}

.academic-home * { box-sizing: border-box; }

.academic-home a { text-underline-offset: 0.16em; }

.academic-hero {
  margin: 0 0 2rem;
  padding: clamp(1.4rem, 3vw, 2rem);
  border: 1px solid #d7e4e8;
  border-radius: 1.1rem;
  background:
    radial-gradient(circle at 92% 8%, rgba(8, 127, 140, 0.16), transparent 30%),
    linear-gradient(135deg, #f8fbfc 0%, #eef7f8 100%);
}

.academic-kicker {
  margin: 0 0 0.55rem;
  color: var(--home-accent-dark);
  font-size: 0.78rem;
  font-weight: 800;
  letter-spacing: 0.09em;
  text-transform: uppercase;
}

.academic-hero h2 {
  max-width: 34ch;
  margin: 0;
  color: var(--home-ink);
  font-size: clamp(1.8rem, 3.2vw, 2.35rem);
  line-height: 1.08;
}

.academic-lead {
  max-width: 64rem;
  margin: 1rem 0 0;
  color: #334b60;
  font-size: 1.05rem;
  line-height: 1.72;
}

.academic-lead + .academic-lead { margin-top: 0.7rem; }

.academic-shortcuts {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem 1.3rem;
  margin: 0 0 1.7rem;
  padding: 0 0 1rem;
  border-bottom: 1px solid var(--home-line);
  font-size: 0.88rem;
  font-weight: 650;
}

.academic-shortcuts a { color: var(--home-accent-dark); }

.academic-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 0.65rem;
  margin-top: 1.25rem;
}

.academic-button {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  min-height: 2.6rem;
  padding: 0.65rem 1rem;
  border: 1px solid var(--home-accent);
  border-radius: 999px;
  background: var(--home-accent);
  color: #fff !important;
  font-size: 0.88rem;
  font-weight: 750;
  text-decoration: none !important;
  transition: transform 150ms ease, box-shadow 150ms ease, background 150ms ease;
}

.academic-button:hover {
  transform: translateY(-1px);
  background: var(--home-accent-dark);
  box-shadow: 0 8px 18px rgba(8, 127, 140, 0.2);
}

.academic-button--secondary {
  background: transparent;
  color: var(--home-accent-dark) !important;
}

.academic-button--secondary:hover {
  background: #fff;
}

.academic-updated {
  margin: 0.9rem 0 0;
  color: var(--home-muted);
  font-size: 0.78rem;
}

.impact-grid {
  display: grid;
  grid-template-columns: repeat(4, minmax(0, 1fr));
  gap: 0.8rem;
  margin: 0 0 2.4rem;
}

.impact-card {
  min-height: 8rem;
  padding: 1.05rem;
  border: 1px solid #dbe6ea;
  border-radius: 0.85rem;
  background: var(--home-card);
}

.impact-value {
  display: block;
  color: var(--home-accent-dark);
  font-size: clamp(1.65rem, 4vw, 2.25rem);
  font-weight: 850;
  line-height: 1;
}

.impact-label {
  display: block;
  margin-top: 0.55rem;
  color: #41576a;
  font-size: 0.84rem;
  line-height: 1.45;
}

.section-heading {
  margin: 2.4rem 0 0.35rem;
  color: var(--home-ink);
  font-size: clamp(1.35rem, 3vw, 1.85rem);
}

.section-intro {
  max-width: 62rem;
  margin: 0 0 1.3rem;
  color: var(--home-muted);
  line-height: 1.65;
}

.selected-list {
  margin: 0 0 2.1rem;
  padding: 0;
  list-style: none;
  border-top: 1px solid var(--home-line);
}

.selected-list li {
  padding: 0.9rem 0;
  border-bottom: 1px solid var(--home-line);
  color: #405769;
  font-size: 0.9rem;
  line-height: 1.55;
}

.selected-list strong { color: var(--home-ink); }

.selected-list a { white-space: nowrap; }

.section-more {
  margin: -1.25rem 0 2rem;
  font-size: 0.88rem;
}

.academic-timeline {
  margin: 1.4rem 0 2.5rem;
  border-top: 1px solid var(--home-line);
}

.timeline-item {
  display: grid;
  grid-template-columns: 5.5rem minmax(0, 1fr);
  gap: 1.4rem;
  padding: 1.35rem 0;
  border-bottom: 1px solid var(--home-line);
}

.timeline-year {
  align-self: start;
  margin: 0;
  padding-top: 0.1rem;
  color: var(--home-accent-dark);
  font-size: 1.15rem;
  font-weight: 850;
  letter-spacing: 0.02em;
}

.timeline-card {
  min-width: 0;
}

.timeline-card ol {
  margin: 0;
  padding-left: 1.3rem;
}

.timeline-card li {
  margin: 0 0 0.48rem;
  color: #43586a;
  font-size: 0.87rem;
  line-height: 1.56;
}

.timeline-card li:last-child { margin-bottom: 0; }

.publication-list li::marker { color: var(--home-accent-dark); }

.publication-title { color: #243f57; font-weight: 650; }

.publication-meta { color: var(--home-muted); }

.publication-role {
  display: inline-block;
  margin: 0.15rem 0.25rem 0.15rem 0;
  padding: 0.12rem 0.45rem;
  border-radius: 0.3rem;
  background: #e5f3f2;
  color: #075f68;
  font-size: 0.75rem;
  font-weight: 700;
  line-height: 1.45;
  vertical-align: baseline;
}

.timeline-card a { white-space: nowrap; }

.current-work {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 0.9rem;
  margin-bottom: 2.2rem;
}

.current-panel {
  padding: 1.2rem;
  border: 1px solid #d6e5e8;
  border-radius: 0.85rem;
  background: var(--home-pale);
}

.current-panel h3 {
  margin: 0 0 0.55rem;
  color: var(--home-ink);
  font-size: 1rem;
}

.current-panel p,
.current-panel li {
  color: #405769;
  font-size: 0.88rem;
  line-height: 1.58;
}

.current-panel ul {
  margin: 0;
  padding-left: 1.1rem;
}

.teaching-detail {
  margin: 1rem 0 2rem;
  border-top: 1px solid var(--home-line);
}

.teaching-block {
  padding: 1.25rem 0;
  border-bottom: 1px solid var(--home-line);
}

.teaching-block h3 {
  margin: 0 0 0.5rem;
  color: var(--home-ink);
  font-size: 1.05rem;
}

.teaching-block p,
.teaching-block li {
  color: #405769;
  font-size: 0.88rem;
  line-height: 1.62;
}

.teaching-block p { margin: 0.45rem 0; }

.teaching-block ul {
  margin: 0;
  padding-left: 1.25rem;
}

.teaching-block li { margin-bottom: 0.65rem; }
.teaching-block li:last-child { margin-bottom: 0; }
.teaching-block strong { color: var(--home-ink); }

.academic-note {
  margin: 2.4rem 0 0;
  padding: 1.15rem 1.25rem;
  border-left: 4px solid var(--home-accent);
  border-radius: 0 0.75rem 0.75rem 0;
  background: #f4f8f9;
  color: #3e5568;
  font-size: 0.88rem;
  line-height: 1.6;
}

@media (max-width: 800px) {
  .impact-grid { grid-template-columns: repeat(2, minmax(0, 1fr)); }
  .current-work { grid-template-columns: 1fr; }
}

@media (max-width: 520px) {
  .academic-hero { padding: 1.2rem; }
  .impact-grid { grid-template-columns: 1fr 1fr; gap: 0.55rem; }
  .impact-card { min-height: 7.2rem; padding: 0.85rem; }
  .timeline-item { display: block; }
  .timeline-year { display: block; margin-bottom: 0.45rem; font-size: 1rem; }
}
</style>

<div class="academic-home">
<section class="academic-hero">
<h2>AI-Driven Resource Coordination for Air-Ground Integrated Networks</h2>
<div class="academic-actions" aria-label="Profile links">
<a class="academic-button" href="/cv/">Academic CV</a>
<a class="academic-button academic-button--secondary" href="https://scholar.google.com/citations?hl=en&amp;user=x0KLyqgAAAAJ" target="_blank" rel="noopener">Google Scholar</a>
<a class="academic-button academic-button--secondary" href="https://orcid.org/0000-0001-8663-1644" target="_blank" rel="noopener">ORCID</a>
<a class="academic-button academic-button--secondary" href="mailto:yuanjian.li@xjtlu.edu.cn">Email</a>
</div>
</section>
<nav class="academic-shortcuts" aria-label="On this page">
<a href="#research">Current research</a>
<a href="#selected-publications">Featured papers</a>
<a href="#academic-record">All publications</a>
<a href="#funding-recognition">Funding &amp; recognition</a>
<a href="#teaching-service">Teaching &amp; supervision</a>
</nav>
<section class="impact-grid" aria-label="Research track record at a glance">
<article class="impact-card">
<span class="impact-value">33</span>
<span class="impact-label">published journal and conference papers</span>
</article>
<article class="impact-card">
<span class="impact-value">14</span>
<span class="impact-label">first-author papers in leading IEEE venues</span>
</article>
<article class="impact-card">
<span class="impact-value">6</span>
<span class="impact-label">journal papers as first and corresponding author</span>
</article>
<article class="impact-card">
<span class="impact-value">2</span>
<span class="impact-label">research grants as Principal Investigator</span>
</article>
</section>
<h2 class="section-heading" id="research">Current research focus</h2>
<p class="section-intro">My primary research programme is <strong>AI-Driven Resource Coordination for Air-Ground Integrated Networks</strong>. It brings together multi-UAV networking, mobile edge computing, and distributed learning to jointly optimize radio resources, computation offloading, and flight trajectories. The current projects target energy-efficient operation and timely IoT data collection.</p>
<h2 class="section-heading" id="selected-publications">Featured papers in this research area</h2>
<ul class="selected-list">
<li><strong>Energy-Efficient UAV-Driven Multi-Access Edge Computing: A Distributed Many-Agent Perspective.</strong> <em>IEEE Transactions on Communications</em>, 2025. <span class="publication-role">First and corresponding author</span> <a href="https://doi.org/10.1109/TCOMM.2025.3552746">DOI</a></li>
<li><strong>Radio Resource Management for Cellular-Connected UAV: A Learning Approach.</strong> <em>IEEE Transactions on Communications</em>, 2023. <span class="publication-role">First and corresponding author</span> <a href="https://doi.org/10.1109/TCOMM.2023.3262826">DOI</a></li>
<li><strong>Path Planning for Cellular-Connected UAV: A DRL Solution With Quantum-Inspired Experience Replay.</strong> <em>IEEE Transactions on Wireless Communications</em>, 2022. <span class="publication-role">First and corresponding author</span> <a href="https://doi.org/10.1109/TWC.2022.3162749">DOI</a></li>
<li><strong>Intelligent Trajectory Planning in UAV-Mounted Wireless Networks: A Quantum-Inspired Reinforcement Learning Perspective.</strong> <em>IEEE Wireless Communications Letters</em>, 2021. <span class="publication-role">First and corresponding author</span> <a href="https://doi.org/10.1109/LWC.2021.3089876">DOI</a></li>
</ul>
<p class="section-more"><a href="#academic-record">See the complete publication list ↓</a></p>
<h2 class="section-heading" id="academic-record">Complete publication list</h2>
<p class="section-intro">All 33 published papers (18 journal articles and 15 conference papers), in reverse chronological order. The full publication record also includes complementary and collaborative work in THz communications and wireless security, which can be found in my <a href="/cv/">CV</a>.</p>
<section class="academic-timeline" aria-label="Published papers by year">
<article class="timeline-item">
<h3 class="timeline-year">2026</h3>
<div class="timeline-card">
<ol class="publication-list">
<li><span class="publication-title">Wideband Hybrid-Field THz UM-MIMO Channel Estimation: A Dual-Attention-Aided Deep-Unfolded Bayesian Learning Approach.</span> <span class="publication-meta">IEEE Transactions on Communications.</span> <span class="publication-role">First and corresponding author</span> <a href="https://doi.org/10.1109/TCOMM.2026.3675428">DOI</a></li>
<li><span class="publication-title">Near-Field User Localization and Beamforming in Covert Communication.</span> <span class="publication-meta">IEEE Transactions on Vehicular Technology.</span> <a href="https://doi.org/10.1109/TVT.2026.3651431">DOI</a></li>
<li><span class="publication-title">AoI and Energy Co-Optimization for UAV-IoT Systems: A Temporal-Critical DRL Solution.</span> <span class="publication-meta">Information and Communication Technology Conference (ICTC).</span> <a href="https://doi.org/10.1109/ICTC70246.2026.11650205">DOI</a></li>
</ol>
</div>
</article>
<article class="timeline-item">
<h3 class="timeline-year">2025</h3>
<div class="timeline-card">
<ol class="publication-list">
<li><span class="publication-title">Energy-Efficient UAV-Driven Multi-Access Edge Computing: A Distributed Many-Agent Perspective.</span> <span class="publication-meta">IEEE Transactions on Communications.</span> <span class="publication-role">First and corresponding author</span> <a href="https://doi.org/10.1109/TCOMM.2025.3552746">DOI</a></li>
<li><span class="publication-title">Hybrid Near- and Far-Field THz UM-MIMO Channel Estimation: A Sparsifying Matrix Learning-Aided Bayesian Approach.</span> <span class="publication-meta">IEEE Transactions on Wireless Communications.</span> <span class="publication-role">First and corresponding author</span> <a href="https://doi.org/10.1109/TWC.2024.3514141">DOI</a></li>
<li><span class="publication-title">Performance Analysis for MmWave Cell-Free Access Network Based on Terahertz Backhaul.</span> <span class="publication-meta">IEEE Communications Letters.</span> <span class="publication-role">Corresponding author</span> <a href="https://doi.org/10.1109/LCOMM.2025.3555748">DOI</a></li>
<li><span class="publication-title">IRS-User Matching and Beamforming Design for Multi-Active-IRS-and-UAV-Aided Secure Directional Modulation Networks.</span> <span class="publication-meta">Chinese Journal of Aeronautics.</span> <a href="https://doi.org/10.1016/j.cja.2025.103422">DOI</a></li>
<li><span class="publication-title">Model-Driven Deep Learning-Aided Wideband Hybrid-Field THz UM-MIMO Channel Estimation.</span> <span class="publication-meta">IEEE GLOBECOM.</span> <span class="publication-role">First author</span> <a href="https://doi.org/10.1109/GLOBECOM59602.2025.11432618">DOI</a></li>
<li><span class="publication-title">Joint Optimization of Security and Energy Efficiency in UAV-Assisted Mobile Edge Computing Systems Using Deep Reinforcement Learning.</span> <span class="publication-meta">International Conference on Intelligent Communication, Sensing and Electromagnetics (ICSE).</span> <a href="https://doi.org/10.1109/ICSE68658.2025.11407655">DOI</a></li>
<li><span class="publication-title">Anti-Jamming Design for RIS-Assisted Multi-Cluster Wireless Powered Communication Networks.</span> <span class="publication-meta">International Conference on Ubiquitous Communication (UCom) · Best Paper Award.</span> <a href="https://doi.org/10.1109/UCOM67224.2025.11336892">DOI</a></li>
<li><span class="publication-title">RAIL: An Accurate and Fast Angle-Inferred Localization Algorithm for UAV-WSN Systems.</span> <span class="publication-meta">IEEE/CIC ICCC Workshops.</span> <a href="https://doi.org/10.1109/ICCCWorkshops67136.2025.11148147">DOI</a></li>
<li><span class="publication-title">Beam Squint Assisted Near-Field Covert Communication.</span> <span class="publication-meta">IEEE/CIC ICCC.</span> <a href="https://doi.org/10.1109/ICCC65529.2025.11149334">DOI</a></li>
</ol>
</div>
</article>
<article class="timeline-item">
<h3 class="timeline-year">2024</h3>
<div class="timeline-card">
<ol class="publication-list">
<li><span class="publication-title">Energy-Efficient UAV-Aided Computation Offloading on THz Band: A MADRL Solution.</span> <span class="publication-meta">IEEE GLOBECOM.</span> <span class="publication-role">First author</span> <a href="https://doi.org/10.1109/GLOBECOM52923.2024.10901463">DOI</a></li>
</ol>
</div>
</article>
<article class="timeline-item">
<h3 class="timeline-year">2023</h3>
<div class="timeline-card">
<ol class="publication-list">
<li><span class="publication-title">Radio Resource Management for Cellular-Connected UAV: A Learning Approach.</span> <span class="publication-meta">IEEE Transactions on Communications.</span> <span class="publication-role">First and corresponding author</span> <a href="https://doi.org/10.1109/TCOMM.2023.3262826">DOI</a></li>
<li><span class="publication-title">DRL-Aided Joint Resource Block and Beamforming Management for Cellular-Connected UAVs.</span> <span class="publication-meta">IEEE GLOBECOM.</span> <span class="publication-role">First author</span> <a href="https://doi.org/10.1109/GLOBECOM54140.2023.10437176">DOI</a></li>
<li><span class="publication-title">Secrecy Performance Analysis on UAV Down-Link Broadcasting With a Full Duplex Receiver.</span> <span class="publication-meta">IEEE PIMRC.</span> <span class="publication-role">First author</span> <a href="https://doi.org/10.1109/PIMRC56721.2023.10293850">DOI</a></li>
</ol>
</div>
</article>
<article class="timeline-item">
<h3 class="timeline-year">2022</h3>
<div class="timeline-card">
<ol class="publication-list">
<li><span class="publication-title">Path Planning for Cellular-Connected UAV: A DRL Solution With Quantum-Inspired Experience Replay.</span> <span class="publication-meta">IEEE Transactions on Wireless Communications.</span> <span class="publication-role">First and corresponding author</span> <a href="https://doi.org/10.1109/TWC.2022.3162749">DOI</a></li>
<li><span class="publication-title">Covertness-Aware Trajectory Design for UAV: A Multi-Step TD3-PER Solution.</span> <span class="publication-meta">IEEE ICC.</span> <span class="publication-role">First author</span> <a href="https://doi.org/10.1109/ICC45855.2022.9839093">DOI</a></li>
<li><span class="publication-title">Intelligent UAV Navigation: A DRL-QiER Solution.</span> <span class="publication-meta">IEEE ICC.</span> <span class="publication-role">First author</span> <a href="https://doi.org/10.1109/ICC45855.2022.9838566">DOI</a></li>
</ol>
</div>
</article>
<article class="timeline-item">
<h3 class="timeline-year">2021</h3>
<div class="timeline-card">
<ol class="publication-list">
<li><span class="publication-title">Intelligent Trajectory Planning in UAV-Mounted Wireless Networks: A Quantum-Inspired Reinforcement Learning Perspective.</span> <span class="publication-meta">IEEE Wireless Communications Letters.</span> <span class="publication-role">First and corresponding author</span> <a href="https://doi.org/10.1109/LWC.2021.3089876">DOI</a></li>
<li><span class="publication-title">Antenna Selection in Energy Harvesting Relaying Networks Using Q-Learning Algorithms.</span> <span class="publication-meta">China Communications.</span> <a href="https://doi.org/10.23919/JCC.2021.04.005">DOI</a></li>
</ol>
</div>
</article>
<article class="timeline-item">
<h3 class="timeline-year">2020</h3>
<div class="timeline-card">
<ol class="publication-list">
<li><span class="publication-title">Harvest-and-Opportunistically-Relay: Analyses on Transmission Outage and Covertness.</span> <span class="publication-meta">IEEE Transactions on Wireless Communications.</span> <span class="publication-role">First author</span> <a href="https://doi.org/10.1109/TWC.2020.3015816">DOI</a></li>
<li><span class="publication-title">Analysis and Optimization of Wireless Powered Untrusted Relay System With Multiple Destinations.</span> <span class="publication-meta">Physical Communication.</span> <a href="https://doi.org/10.1016/j.phycom.2020.101161">DOI</a></li>
</ol>
</div>
</article>
<article class="timeline-item">
<h3 class="timeline-year">2019</h3>
<div class="timeline-card">
<ol class="publication-list">
<li><span class="publication-title">Ergodic Secrecy Performance Analysis of Multiuser Diversity in Energy-Constrained Untrusted Relay Systems.</span> <span class="publication-meta">Journal of Signal Processing.</span> <a href="https://doi.org/10.16798/j.issn.1003-0530.2019.02.016">DOI</a></li>
<li><span class="publication-title">Security Performance Analysis of Full Duplex Relay System With Wireless Energy Harvesting.</span> <span class="publication-meta">Journal of Huaqiao University (Natural Science).</span> <a href="https://doi.org/10.11830/ISSN.1000-5013.201801066">DOI</a></li>
<li><span class="publication-title">Wireless Energy Harvesting Relaying Networks Combined With Antenna Selection.</span> <span class="publication-meta">IEEE WPMC.</span> <a href="https://doi.org/10.1109/WPMC48795.2019.9096212">DOI</a></li>
</ol>
</div>
</article>
<article class="timeline-item">
<h3 class="timeline-year">2018</h3>
<div class="timeline-card">
<ol class="publication-list">
<li><span class="publication-title">Artificial Noise Aided Precoding With Imperfect CSI in Full-Duplex Relaying Secure Communications.</span> <span class="publication-meta">IEEE Access.</span> <span class="publication-role">First author</span> <a href="https://doi.org/10.1109/ACCESS.2018.2851598">DOI</a></li>
<li><span class="publication-title">Antenna Mode Switching for Full-Duplex Destination-Based Jamming Secure Transmission.</span> <span class="publication-meta">IEEE Access.</span> <span class="publication-role">First author</span> <a href="https://doi.org/10.1109/ACCESS.2018.2791638">DOI</a></li>
<li><span class="publication-title">Antenna Mode Switching in Full-Duplex Destination-Jamming Secure Transmission Systems.</span> <span class="publication-meta">Journal of Signal Processing.</span> <span class="publication-role">First author</span> <a href="https://doi.org/10.16798/j.issn.1003-0530.2018.04.009">DOI</a></li>
<li><span class="publication-title">Study of Full-Duplex Relay Secure Networks Based on Wireless Energy Harvesting Technology.</span> <span class="publication-meta">Communications Technology.</span></li>
</ol>
</div>
</article>
<article class="timeline-item">
<h3 class="timeline-year">2017</h3>
<div class="timeline-card">
<ol class="publication-list">
<li><span class="publication-title">Secrecy Performance Analysis of Artificial Noise Aided Precoding in Full-Duplex Relay Systems.</span> <span class="publication-meta">IEEE GLOBECOM.</span> <span class="publication-role">First author</span> <a href="https://doi.org/10.1109/GLOCOM.2017.8254504">DOI</a></li>
<li><span class="publication-title">Large-Scale Antennas Analysis of Untrusted Relay System With Cooperative Jamming.</span> <span class="publication-meta">International Conference on Network and Service Management (CNSM).</span> <a href="https://doi.org/10.23919/CNSM.2017.8256012">DOI</a></li>
<li><span class="publication-title">A Full-Duplex SWIPT Relaying Protocol Based on Discrete Energy State.</span> <span class="publication-meta">IEEE WPMC.</span> <a href="https://doi.org/10.1109/WPMC.2017.8301864">DOI</a></li>
</ol>
</div>
</article>
</section>
<h2 class="section-heading" id="funding-recognition">Research funding and recognition</h2>
<section class="current-work" aria-label="Selected research funding and recognition">
<article class="current-panel">
<h3>Principal Investigator funding</h3>
<ul>
<li>Jiangsu Higher Education Natural Science Foundation General Programme: <em>DRL-Powered Distributed Resource Coordination for UAV-Aided IoT</em> (2025–2027; CNY 30,000).</li>
<li>XJTLU Research Development Fund: <em>AI-Native Decentralized Resource Scheduling for Space-Air-Ground Integrated IoT</em> (2026–2028; CNY 100,000).</li>
</ul>
</article>
<article class="current-panel">
<h3>Selected recognition</h3>
<ul>
<li>Best Paper Award, International Conference on Ubiquitous Communication (UCom), 2025 (coauthored paper).</li>
<li>Exemplary Reviewer, IEEE Communications Society, 2025.</li>
</ul>
</article>
</section>
<h2 class="section-heading" id="teaching-service">Teaching and supervision</h2>
<p class="section-intro">Teaching at XJTLU in an English-medium environment, postgraduate and undergraduate supervision, and earlier graduate teaching-assistant work at King's College London.</p>
<section class="teaching-detail" aria-label="Detailed teaching and supervision record">
<article class="teaching-block">
<h3>XJTLU teaching</h3>
<ul>
<li><strong>Module Leader, COS202 Continuous and Discrete Time Signals and Systems</strong> — 2026/27, Semester 1; more than 610 Year 3 undergraduate students.</li>
<li><strong>Module Leader, CAN210 Digital Signal Processing</strong> — 2025/26, Semester 2; 159 Year 3 undergraduate students.</li>
<li><strong>Co-Module Leader, CAN207 Continuous and Discrete Time Signals and Systems</strong> — 2025/26, Semester 1; more than 530 Year 3 undergraduate students.</li>
<li><strong>Co-Module Leader, SAT005 Introduction to Emerging Technologies</strong> — 2024/25, Semester 2.</li>
</ul>
</article>
<article class="teaching-block">
<h3>Postgraduate research supervision — primary supervisor</h3>
<ul>
<li><strong>Shen Liu, PhD</strong> (Autumn 2026 entry; previously MSc, University of Nottingham): <em>Quantum Deep Reinforcement Learning-Aided Resource Coordination for Energy-Efficient 6G Networks</em> (SFXJTU2506).</li>
<li><strong>Yuanyuan Chen, MRes</strong> (Autumn 2025 entry; previously BSc, Shanghai Institute of Technology): <em>Federated AI-Driven Information Freshness Optimization for 6G-Aided IoT Data Collection Systems</em>.</li>
<li><strong>Yang Yu, MSc</strong> (Autumn 2025 entry; previously BSc, Shandong University of Science and Technology): <em>DRL-Aided Age-of-Information Minimization in Air-Ground Integrated Networks</em>.</li>
<li><strong>Guangyi Zhang, MSc</strong> (Autumn 2025 entry; previously BSc, Shandong University of Science and Technology): <em>Reinforcement Learning-Aided Resource Coordination for Drone-Assisted Edge Computing in Industrial IoT</em>.</li>
<li><strong>Zhouxiang Tao, MSc</strong> (Autumn 2026 entry; previously BSc, Guizhou University): <em>Agentic AI for Air-Ground Integrated Networks</em>.</li>
<li><strong>Yawen Ji, MSc</strong> (Autumn 2026 entry; previously BSc, Nanjing University of Posts and Telecommunications): <em>Agentic AI for Air-Ground Integrated Networks</em>.</li>
</ul>
</article>
<article class="teaching-block">
<h3>Undergraduate research and final-year projects — primary supervisor</h3>
<ul>
<li><strong>2026 XJTLU Summer Undergraduate Research Fellowship</strong> (SURF-2026-0240; CNY 6,000): <em>AI-Driven Multi-Dimensional Resource Scheduling for UAV-Enabled Multi-Access Edge Computing</em>. Students: Xiaotian Jia and Yutian Cui (Information and Computing Science); Weiyue Zhang and Shengran Ding (Telecommunications Engineering). <a href="https://github.com/YuanjianLi/UAV-MEC-MADRL" target="_blank" rel="noopener">Open-source code</a> · <a href="/files/pdf/SURF2026poster.pdf">Project poster</a>.</li>
<li><strong>Final-year project (FYP) supervision at XJTLU, AY2025/26</strong> — seven students: Pengkun Ou, Yichun Xu, Shutong Yuan, Guanxu Bai, Ruineng Tang, Ancheng Li, and Yuxuan Chen. Project themes: deep-reinforcement-learning-enabled UAV communications, edge computing, IoT information freshness, and wireless security.</li>
<li><strong>FYP supervision at Nanyang Technological University (NTU) Singapore, AY2024/25</strong> — one student: Tiew Yen Huei. Project title: DRL-Powered Resource Coordination for UAV-THz Computation Offloading. In this case, the primary supervisor is my postdoc mentor, Prof. A S Madhukumar. <a href="https://hdl.handle.net/10356/184238">FYP Dissertation Link</a></li>
</ul>
</article>
<article class="teaching-block">
<h3>Doctoral supervision and recruitment projects</h3>
<ul>
<li><strong>Primary PhD Supervisor</strong> — XJTLU Postgraduate Research Scholarship project FOSA2506034, <em>DRL-Enabled Resource Coordination for Covertness-Aware and Energy-Efficient UAV-Aided IoT</em> (since July 2025; CNY 297,000). Position available. </li>
<li><strong>Primary PhD Supervisor</strong> — XJTLU–Xi'an Jiaotong University–University of Liverpool joint doctoral project SFXJTU2506, <em>Quantum Deep Reinforcement Learning-Aided Resource Coordination for Energy-Efficient 6G Networks</em> (since October 2025). Position has been filled. </li>
<li><strong>Second PhD Supervisor</strong> — XJTLU Postgraduate Research Scholarship project FOSLG250407, <em>Adaptive Digital Twin Modelling and Optimization for V2X Networks in Large-Scale Traffic Scenarios</em> (since July 2025; CNY 297,000).</li>
</ul>
</article>
<article class="teaching-block">
<h3>Graduate teaching assistant, King's College London</h3>
<ul>
<li><strong>7CCEMDCO Digital Communications</strong> — 2022/23, Semester 1.</li>
<li><strong>5CCE2MCT Mechatronics</strong> — 2021/22, Semester 2.</li>
<li><strong>7CCSMMPC Mobile and Personal Communications</strong> — 2020/21, Semester 2.</li>
</ul>
</article>
</section>
<p class="academic-note">I welcome enquiries from prospective research students and collaborators working on AI-driven resource coordination for air-ground integrated networks. Please <a href="mailto:yuanjian.li@xjtlu.edu.cn">email me</a> with a brief description of your background and research interests.</p>
</div>
