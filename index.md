---
---

<h1>Taufik Fahrudin</h1>

<p>Catatan kecil dari seorang bernama Taufik Fahrudin.</p>

<style>
  .jumbo {
    margin: 26px 0 10px;
    padding: 24px 26px;
    border-radius: 14px;
    background:
      radial-gradient(120% 160% at 100% 0%, rgba(94,124,255,.35) 0%, rgba(94,124,255,0) 55%),
      linear-gradient(135deg, #101a2e 0%, #16233c 55%, #0e1626 100%);
    border: 1px solid #26364f;
    box-shadow: 0 10px 30px rgba(0,0,0,.28);
  }
  .jumbo .tag {
    display: inline-block;
    font-size: 11px;
    letter-spacing: 1.6px;
    text-transform: uppercase;
    font-weight: 700;
    color: #9fc0ff;
    background: rgba(94,124,255,.14);
    border: 1px solid rgba(94,124,255,.38);
    border-radius: 999px;
    padding: 4px 12px;
  }
  .jumbo h2 {
    margin: 13px 0 8px;
    font-size: 21px;
    line-height: 1.25;
    color: #f2f6fc;
    border: 0;
  }
  .jumbo p {
    margin: 0 0 16px;
    font-size: 13.5px;
    line-height: 1.55;
    color: #a9bacd;
  }
  .jumbo p.pills { margin: 0 0 16px; }
  .jumbo .prov {
    display: inline-block;
    font-size: 11.5px;
    font-weight: 650;
    padding: 3px 10px;
    border-radius: 999px;
    margin: 0 6px 6px 0;
  }
  .jumbo .prov.cc { background: #0f2740; color: #7fb0ff; border: 1px solid #24507e; }
  .jumbo .prov.ocg { background: #241542; color: #bc8cff; border: 1px solid #4b2c7d; }
  .jumbo .cta {
    display: inline-block;
    font-size: 14.5px;
    font-weight: 600;
    color: #08111f !important;
    background: linear-gradient(90deg, #7fb0ff, #9d8cff);
    padding: 11px 20px;
    border-radius: 9px;
    text-decoration: none !important;
    transition: transform .12s ease, filter .12s ease;
  }
  .jumbo .cta:hover { transform: translateY(-1px); filter: brightness(1.08); }
  .jumbo .meta {
    display: block;
    margin-top: 14px;
    font-size: 12px;
    color: #7f93a8;
  }
</style>

<div class="jumbo">
  <span class="tag">Benchmark</span>
  <h2>Benchmark model LLM per penyedia</h2>
  <p>125 model diukur: throughput, latensi dua tahap, dan status ketersediaan tiap rute.</p>
  <p class="pills">
    <span class="prov cc">commandcode &middot; GOAT $10</span>
    <span class="prov ocg">opencode &middot; GO PLAN $10</span>
  </p>
  <a class="cta" href="/benchmarks/">Lihat hasil benchmark &rarr;</a>
</div>
