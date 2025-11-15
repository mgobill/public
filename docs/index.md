---
title: App Policies
layout: default
---

# App Launchpad

Explore the mobile apps from AeroNatics Studios and quickly jump to their
store listings, support portals, and policy pages.

<style>
.app-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 1.5rem;
  margin: 2rem 0;
  padding: 0;
  list-style: none;
}

.app-card {
  border: 1px solid #e0e0e0;
  border-radius: 12px;
  padding: 1.5rem;
  background: #fff;
  box-shadow: 0 4px 14px rgba(0, 0, 0, 0.05);
}

.app-card h2 {
  margin-top: 0;
}

.status-badge {
  display: inline-block;
  padding: 0.2rem 0.75rem;
  margin: 0.25rem 0 1rem;
  border-radius: 999px;
  font-size: 0.85rem;
  font-weight: 600;
  background: #eef2ff;
  color: #4338ca;
}

.card-section {
  margin-top: 1rem;
}

.card-section h3 {
  margin-bottom: 0.35rem;
  font-size: 1rem;
}

.card-section ul {
  margin: 0;
  padding-left: 1.25rem;
}

.coming-soon {
  font-style: italic;
  color: #6b7280;
}
</style>

<div class="app-grid">
  <div class="app-card">
    <h2>AeroNatics</h2>
    <div class="status-badge">Store listings pending review</div>
    <p>Modern flight logging and safety tooling designed for both pilots and
    aeronautic hobbyists.</p>
    <div class="card-section">
      <h3>Store Links</h3>
      <ul>
        <li>Google Play — <span class="coming-soon">Coming soon</span></li>
        <li>Apple App Store — <span class="coming-soon">Coming soon</span></li>
      </ul>
    </div>
    <div class="card-section">
      <h3>Support & Policies</h3>
      <ul>
        <li><a href="./aeronatics_support">Support Center</a></li>
        <li><a href="./aeronatics_privacy_policy">Privacy Policy</a></li>
        <li><a href="./aeronatics_csae_policy">CSAE Policy</a></li>
      </ul>
    </div>
  </div>

  <div class="app-card">
    <h2>Flight ATC</h2>
    <div class="status-badge">Live on both stores</div>
    <p>Air traffic control training drills with quick feedback loops and configurable challenges.</p>
    <div class="card-section">
      <h3>Store Links</h3>
      <ul>
        <li><a href="https://play.google.com/store/apps/details?id=com.mgobill.flightatc&pcampaignid=web_share" target="_blank" rel="noopener">Google Play</a></li>
        <li><a href="https://apps.apple.com/us/app/flight-atc/id6755204257" target="_blank" rel="noopener">Apple App Store</a></li>
      </ul>
    </div>
    <div class="card-section">
      <h3>Support & Policies</h3>
      <ul>
        <li><a href="./flightatc_support">Support Center</a></li>
        <li><a href="./flightatc_privacy_policy">Privacy Policy</a></li>
      </ul>
    </div>
  </div>
</div>
