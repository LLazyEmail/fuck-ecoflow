---
sidebar_position: 92
title: Monitoring exporters (research)
---

# Monitoring exporters (research)

When documenting metrics or dashboards for EcoFlow gear, start from existing open exporters rather than reinventing protocols:

- [berezhinskiy/ecoflow_exporter](https://github.com/berezhinskiy/ecoflow_exporter) — Prometheus exporter for portable power stations
- [tess1o/go-ecoflow-exporter](https://github.com/tess1o/go-ecoflow-exporter) — Go exporter via REST or MQTT
- [tess1o/go-ecoflow](https://github.com/tess1o/go-ecoflow) — Go client library

## Guidance for this repo

1. Link and attribute; do not vendor large code trees without license review.
2. Prefer documenting metric names / MQTT topics we observe in the lab.
3. Keep credentials in env vars (see [EcoFlow API credentials](./ecoflow-api-credentials.md)).
