---
name: Build an analyst-ratings brief for a ticker
description: Combine analyst ratings actions, consensus price targets, analyst/firm reference data, insights, and bull/bear cases into one research brief.
api: openapi/benzinga-ratings-api-openapi.yml
operations: [get-ratings, get-consensus-ratings-v1, get-ratings-analysts, get-ratings-firms, get-analyst-insights-v1, get-bulls-say-bears-say-v1]
generated: '2026-07-22'
method: generated
---

# Build an analyst-ratings brief

Authenticate with `Authorization: token <YOUR_API_KEY>` (or `?token=`).

1. **Ratings actions** — `get-ratings` (`GET /api/v2.1/calendar/ratings`): upgrades/downgrades/initiations with current and prior price targets.
2. **Consensus** — `get-consensus-ratings-v1` (`GET /api/v1/consensus-ratings`): aggregated consensus price target, ratings distribution, analyst counts.
3. **Who is rating** — `get-ratings-analysts` (`GET /api/v2.1/calendar/ratings/analysts`) and `get-ratings-firms` (`GET /api/v2.1/calendar/ratings/firms`) for analyst/firm reference data and accuracy metrics.
4. **Narrative** — `get-analyst-insights-v1` (`GET /api/v1/analyst/insights`) for research perspectives; `get-bulls-say-bears-say-v1` (`GET /api/v1/bulls_bears_say`) for the current bull and bear cases.

Assemble: lead with the consensus, list recent actions chronologically, then attach insights and the bull/bear framing. 403 on any endpoint means it is outside your license tier; 429 means back off (Kong-gateway rate limiting).
