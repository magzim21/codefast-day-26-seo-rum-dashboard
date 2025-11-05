# Codefast Day 26 · SEO + RUM Dashboard

## Mission
- Ship a unified dashboard combining SEO metrics and Datadog RUM insights with anomaly detection.

## Implementation Checklist
1. Ingest rank, crawl, and Lighthouse data alongside RUM telemetry.
2. Build visualizations that correlate UX regressions with search performance.
3. Implement anomaly detection and alert routing with severity labels.
4. Generate executive summary PDFs weekly and email to stakeholders.

## Telemetry & QA
- Validate data refresh jobs, heartbeat monitors, and chart rendering in CI.
- Unit test data transforms and guard against missing metrics.

## Deliverables
- README detailing data connectors, dashboard usage, and alert governance.
- Template for weekly executive summaries with required talking points.
