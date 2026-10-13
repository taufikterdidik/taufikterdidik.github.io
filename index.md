---
---

<h1>Taufik Fahrudin</h1>

<p>Catatan kecil dari seorang bernama Taufik Fahrudin.</p>

<style>
  .jumbo {
    margin: 26px 0 10px;
    padding: 30px 32px;
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
    margin: 14px 0 8px;
    font-size: 25px;
    line-height: 1.25;
    color: #f2f6fc;
    border: 0;
  }
  .jumbo p {
    margin: 0 0 18px;
    font-size: 14.5px;
    line-height: 1.6;
    color: #a9bacd;
  }
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
  <h2>Benchmark model LLM di gateway OmniRoute</h2>
  <p>
    Hasil pengukuran <strong>125 model</strong> pada dua prefix penyedia &mdash; <strong>command-code</strong>
    (87 model) dan <strong>opencode-go</strong> (38 model): throughput, latensi dua tahap, dan status
    ketersediaan tiap rute.
  </p>
  <a class="cta" href="/benchmarks/">Lihat hasil benchmark &rarr;</a>
  <span class="meta">Diukur 9 Oktober 2026 &middot; streaming, median 3 run &middot; 58 rute command-code terukur</span>
</div>
