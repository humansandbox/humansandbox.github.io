# humansandbox

Measured economics of AI-agent software testing — a primary-evidence archive (static site for GitHub Pages).

- `index.html` — landing page and site map (English)
- `at_cost_bench.html` — AT COST BENCH: viewer over measured A/B runs (RGR branch-grained vs Direct-to-GREEN)
- `data/cost_data.js` — static snapshot of the evidence records (`window.COST_DATA`); regenerate from the
  evidence database when new runs land
- `css/site.css` — shared styles (StrictDev-derived base colors)
- `sitemap.xml` — update the base URL if the repository/owner changes

Fully static: pages load bundled data via a script tag, so they work from `file://` and on GitHub Pages
without any backend. Only files deliberately placed here are published.
