# Benzinga

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Benzinga is a Detroit-based financial media and market data company (founded 2010, acquired by Beringer Capital in 2021) that licenses its newsroom and data products through a developer-first API platform at docs.benzinga.com. Products span real-time financial news (Newsfeed, Press Releases, Why Is It Moving), quantified news sentiment, a deep corporate-events Calendar (earnings, dividends, ratings, IPOs, splits, economics, FDA, M&A, government and insider trades), delayed quotes, historical OHLCV bars, fundamentals, logos, ticker trends, and earnings-call transcripts. Delivery is REST over https://api.benzinga.com with API-key auth, plus WebSocket streams, a TCP streaming service (tcp-v1.benzinga.io:11337), and a data webhook engine. OpenAPI and AsyncAPI specs are published in the public Benzinga/benzinga-docs GitHub repo. Access is licensing-led with a developer console registration flow; no public pricing page.

**Areas:** Finance · Market Data · Stocks · News · Real-Time · Sentiment · Analyst Ratings · Earnings · Options · Streaming

## Benzinga on APIs.io

Everything profiled for Benzinga is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/benzinga/](https://apis.io/providers/benzinga/)** — or go straight to one of the APIs or properties below.

### APIs (43)

- [Benzinga Newsfeed & Why Is It Moving API](https://apis.io/apis/benzinga/benzinga-newsfeed-api/) — Structured real-time and historical financial news from the Benzinga newsroom, with channel filters, removed-news deltas, and Why Is It Moving (WIIM)…
- [Benzinga Ticker Trends API](https://apis.io/apis/benzinga/benzinga-ticker-trends-api/) — Trending-ticker rankings and per-ticker trend scores aggregated across time intervals from Benzinga audience activity.
- [Benzinga Earnings Call Transcripts API](https://apis.io/apis/benzinga/benzinga-earnings-call-transcripts-api/) — Real-time and historical conference-call transcripts, audio, AI-generated summaries, and speaker data, fetched by call ID or filtered lists.
- [Benzinga Data Webhook Engine](https://apis.io/apis/benzinga/benzinga-webhook-api/) — Push delivery of Benzinga calendar, signal, and sentiment data to customer endpoints with filterable, resilient webhooks and a test-delivery endpoint.
- [Benzinga WebSocket Streaming API](https://apis.io/apis/benzinga/benzinga-websocket-streaming-api/) — Real-time WebSocket streams over wss://api.benzinga.com for news, earnings, analyst ratings, consensus ratings, analyst insights, bulls/bears cases, and…
- [Benzinga TCP Streaming Service](https://apis.io/apis/benzinga/benzinga-tcp-streaming-service/) — Low-latency persistent TCP stream (tcp-v1.benzinga.io port 11337, optional TLS) delivering real-time news, option alerts, and market events as JSON…
- [Benzinga Analyst Insights API](https://apis.io/apis/benzinga/benzinga-analyst-insights-api/) — The Analyst Insights API from Benzinga — 1 operation(s) for analyst insights.
- [Benzinga Analyst Reports API](https://apis.io/apis/benzinga/benzinga-analyst-reports-api/) — The Analyst Reports API from Benzinga — 1 operation(s) for analyst reports.
- [Benzinga Block Trade API](https://apis.io/apis/benzinga/benzinga-block-trade-api/) — The Block Trade API from Benzinga — 1 operation(s) for block trade.
- [Benzinga Bulls Say Bears Say API](https://apis.io/apis/benzinga/benzinga-bulls-say-bears-say-api/) — The Bulls Say Bears Say API from Benzinga — 1 operation(s) for bulls say bears say.
- [Benzinga Calls API](https://apis.io/apis/benzinga/benzinga-calls-api/) — The calls API from Benzinga — 2 operation(s) for calls.
- [Benzinga Channels API](https://apis.io/apis/benzinga/benzinga-channels-api/) — The Channels API from Benzinga — 1 operation(s) for channels.
- [Benzinga Conference Calls API](https://apis.io/apis/benzinga/benzinga-conference-calls-api/) — The conference_calls API from Benzinga — 1 operation(s) for conference_calls.
- [Benzinga Consensus Ratings API](https://apis.io/apis/benzinga/benzinga-consensus-ratings-api/) — The consensus_ratings API from Benzinga — 1 operation(s) for consensus_ratings.
- [Benzinga Dividends API](https://apis.io/apis/benzinga/benzinga-dividends-api/) — The Dividends API from Benzinga — 2 operation(s) for dividends.
- [Benzinga Earnings API](https://apis.io/apis/benzinga/benzinga-earnings-api/) — The earnings API from Benzinga — 1 operation(s) for earnings.
- [Benzinga Economics API](https://apis.io/apis/benzinga/benzinga-economics-api/) — The economics API from Benzinga — 1 operation(s) for economics.
- [Benzinga ERx Gaps API](https://apis.io/apis/benzinga/benzinga-erx-gaps-api/) — The ERx Gaps API from Benzinga — 1 operation(s) for erx gaps.
- [Benzinga Events API](https://apis.io/apis/benzinga/benzinga-events-api/) — The events API from Benzinga — 1 operation(s) for events.
- [Benzinga Fda API](https://apis.io/apis/benzinga/benzinga-fda-api/) — The fda API from Benzinga — 1 operation(s) for fda.
- [Benzinga Fundamentals API](https://apis.io/apis/benzinga/benzinga-fundamentals-api/) — The Fundamentals API from Benzinga — 20 operation(s) for fundamentals.
- [Benzinga Government Trade Reports API](https://apis.io/apis/benzinga/benzinga-government-trade-reports-api/) — The Government Trade Reports API from Benzinga — 1 operation(s) for government trade reports.
- [Benzinga Government Trades API](https://apis.io/apis/benzinga/benzinga-government-trades-api/) — The Government Trades API from Benzinga — 1 operation(s) for government trades.
- [Benzinga Guidance API](https://apis.io/apis/benzinga/benzinga-guidance-api/) — The guidance API from Benzinga — 1 operation(s) for guidance.
- [Benzinga Halt Resume API](https://apis.io/apis/benzinga/benzinga-halt-resume-api/) — The Halt Resume API from Benzinga — 1 operation(s) for halt resume.
- [Benzinga Insider Transaction API](https://apis.io/apis/benzinga/benzinga-insider-transaction-api/) — The Insider Transaction API from Benzinga — 2 operation(s) for insider transaction.
- [Benzinga Ipos API](https://apis.io/apis/benzinga/benzinga-ipos-api/) — The ipos API from Benzinga — 2 operation(s) for ipos.
- [Benzinga Logos API](https://apis.io/apis/benzinga/benzinga-logos-api/) — The logos API from Benzinga — 2 operation(s) for logos.
- [Benzinga Ma API](https://apis.io/apis/benzinga/benzinga-ma-api/) — The ma API from Benzinga — 1 operation(s) for ma.
- [Benzinga Market Data API](https://apis.io/apis/benzinga/benzinga-market-data-api/) — The Market Data API from Benzinga — 3 operation(s) for market data.
- [Benzinga News Analytics API](https://apis.io/apis/benzinga/benzinga-news-analytics-api/) — The News Analytics API from Benzinga — 1 operation(s) for news analytics.
- [Benzinga Offerings API](https://apis.io/apis/benzinga/benzinga-offerings-api/) — The offerings API from Benzinga — 1 operation(s) for offerings.
- [Benzinga Option Activity API](https://apis.io/apis/benzinga/benzinga-option-activity-api/) — The Option Activity API from Benzinga — 1 operation(s) for option activity.
- [Benzinga Participants API](https://apis.io/apis/benzinga/benzinga-participants-api/) — The participants API from Benzinga — 1 operation(s) for participants.
- [Benzinga QuoteDelayed API](https://apis.io/apis/benzinga/benzinga-quotedelayed-api/) — The QuoteDelayed API from Benzinga — 2 operation(s) for quotedelayed.
- [Benzinga Ratings Analysts API](https://apis.io/apis/benzinga/benzinga-ratings-analysts-api/) — The ratings_analysts API from Benzinga — 1 operation(s) for ratings_analysts.
- [Benzinga Ratings API](https://apis.io/apis/benzinga/benzinga-ratings-api/) — The ratings API from Benzinga — 1 operation(s) for ratings.
- [Benzinga Ratings Firms API](https://apis.io/apis/benzinga/benzinga-ratings-firms-api/) — The ratings_firms API from Benzinga — 1 operation(s) for ratings_firms.
- [Benzinga Removed API](https://apis.io/apis/benzinga/benzinga-removed-api/) — The removed API from Benzinga — 1 operation(s) for removed.
- [Benzinga Splits API](https://apis.io/apis/benzinga/benzinga-splits-api/) — The splits API from Benzinga — 1 operation(s) for splits.
- [Benzinga Status API](https://apis.io/apis/benzinga/benzinga-status-api/) — The status API from Benzinga — 1 operation(s) for status.
- [Benzinga Summaries API](https://apis.io/apis/benzinga/benzinga-summaries-api/) — The summaries API from Benzinga — 2 operation(s) for summaries.
- [Benzinga Transcripts API](https://apis.io/apis/benzinga/benzinga-transcripts-api/) — The transcripts API from Benzinga — 2 operation(s) for transcripts.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (7)

Event-driven and webhook contracts.

- [Benzinga Analyst Insights WebSocket Stream](https://apis.io/asyncapis/benzinga/benzinga-analyst-insights-stream-asyncapi/)
- [Benzinga Bulls/Bears Say WebSocket Stream](https://apis.io/asyncapis/benzinga/benzinga-bulls-bears-say-stream-asyncapi/)
- [Benzinga Calendar Earnings WebSocket Stream](https://apis.io/asyncapis/benzinga/benzinga-calendar-earnings-stream-asyncapi/)
- [Benzinga Calendar Ratings WebSocket Stream](https://apis.io/asyncapis/benzinga/benzinga-calendar-ratings-stream-asyncapi/)
- [Benzinga Consensus Ratings WebSocket Stream](https://apis.io/asyncapis/benzinga/benzinga-consensus-ratings-stream-asyncapi/)
- [Benzinga News Stream API](https://apis.io/asyncapis/benzinga/benzinga-news-stream-asyncapi/)
- [Benzinga Transcripts WebSocket API](https://apis.io/asyncapis/benzinga/benzinga-transcripts-stream-asyncapi/)

#### Event channels (7)

Individual events and webhooks the provider emits.

- [stream](https://apis.io/channels/benzinga/benzinga-bulls-bears-say-websocket-stream-stream/)
- [stream](https://apis.io/channels/benzinga/benzinga-calendar-earnings-websocket-stream-stream/)
- [stream](https://apis.io/channels/benzinga/benzinga-calendar-ratings-websocket-stream-stream/)
- [stream](https://apis.io/channels/benzinga/benzinga-consensus-ratings-websocket-stream-stream/)
- [stream](https://apis.io/channels/benzinga/benzinga-news-stream-api-stream/)
- [stream](https://apis.io/channels/benzinga/benzinga-transcripts-websocket-api-stream/)
- [stream](https://apis.io/channels/benzinga/stream/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [benzinga](https://apis.io/servers/benzinga/benzinga/)

#### Collections (42)

Postman and Open Collection request collections.

- [Analyst Reports Raw Text Analyst Insights API](https://apis.io/collections/benzinga/open-benzinga-analyst-insights-api/)
- [Raw Text Analyst Insights Analyst Reports API](https://apis.io/collections/benzinga/open-benzinga-analyst-reports-api/)
- [Analyst Reports Raw Text Analyst Insights Block Trade API](https://apis.io/collections/benzinga/open-benzinga-block-trade-api/)
- [Analyst Reports Raw Text Analyst Insights Bulls Say Bears Say API](https://apis.io/collections/benzinga/open-benzinga-bulls-say-bears-say-api/)
- [Analyst Reports Raw Text Analyst Insights calls API](https://apis.io/collections/benzinga/open-benzinga-calls-api/)
- [Analyst Reports Raw Text Analyst Insights Channels API](https://apis.io/collections/benzinga/open-benzinga-channels-api/)
- [Analyst Reports Raw Text Analyst Insights conference_calls API](https://apis.io/collections/benzinga/open-benzinga-conference-calls-api/)
- [Analyst Reports Raw Text Analyst Insights consensus_ratings API](https://apis.io/collections/benzinga/open-benzinga-consensus-ratings-api/)
- [Analyst Reports Raw Text Analyst Insights Dividends API](https://apis.io/collections/benzinga/open-benzinga-dividends-api/)
- [Analyst Reports Raw Text Analyst Insights earnings API](https://apis.io/collections/benzinga/open-benzinga-earnings-api/)
- [Analyst Reports Raw Text Analyst Insights Earnings Call Transcripts API](https://apis.io/collections/benzinga/open-benzinga-earnings-call-transcripts-api/)
- [Analyst Reports Raw Text Analyst Insights economics API](https://apis.io/collections/benzinga/open-benzinga-economics-api/)
- [Analyst Reports Raw Text Analyst Insights ERx Gaps API](https://apis.io/collections/benzinga/open-benzinga-erx-gaps-api/)
- [Analyst Reports Raw Text Analyst Insights events API](https://apis.io/collections/benzinga/open-benzinga-events-api/)
- [Analyst Reports Raw Text Analyst Insights fda API](https://apis.io/collections/benzinga/open-benzinga-fda-api/)
- [Analyst Reports Raw Text Analyst Insights Fundamentals API](https://apis.io/collections/benzinga/open-benzinga-fundamentals-api/)
- [Analyst Reports Raw Text Analyst Insights Government Trade Reports API](https://apis.io/collections/benzinga/open-benzinga-government-trade-reports-api/)
- [Analyst Reports Raw Text Analyst Insights Government Trades API](https://apis.io/collections/benzinga/open-benzinga-government-trades-api/)
- [Analyst Reports Raw Text Analyst Insights guidance API](https://apis.io/collections/benzinga/open-benzinga-guidance-api/)
- [Analyst Reports Raw Text Analyst Insights Halt Resume API](https://apis.io/collections/benzinga/open-benzinga-halt-resume-api/)
- [Analyst Reports Raw Text Analyst Insights Insider Transaction API](https://apis.io/collections/benzinga/open-benzinga-insider-transaction-api/)
- [Analyst Reports Raw Text Analyst Insights ipos API](https://apis.io/collections/benzinga/open-benzinga-ipos-api/)
- [Analyst Reports Raw Text Analyst Insights logos API](https://apis.io/collections/benzinga/open-benzinga-logos-api/)
- [Analyst Reports Raw Text Analyst Insights ma API](https://apis.io/collections/benzinga/open-benzinga-ma-api/)
- [Analyst Reports Raw Text Analyst Insights Market Data API](https://apis.io/collections/benzinga/open-benzinga-market-data-api/)
- …and 17 more published on APIs.io

#### Overlays (42)

OpenAPI overlays, including conversational phrasing for each operation.

- [Benzinga Analyst Insights Api Overlay](https://apis.io/overlays/benzinga/benzinga-analyst-insights-api-overlay/)
- [Benzinga Analyst Reports Api Overlay](https://apis.io/overlays/benzinga/benzinga-analyst-reports-api-overlay/)
- [Benzinga Block Trade Api Overlay](https://apis.io/overlays/benzinga/benzinga-block-trade-api-overlay/)
- [Benzinga Bulls Say Bears Say Api Overlay](https://apis.io/overlays/benzinga/benzinga-bulls-say-bears-say-api-overlay/)
- [Benzinga Calls Api Overlay](https://apis.io/overlays/benzinga/benzinga-calls-api-overlay/)
- [Benzinga Channels Api Overlay](https://apis.io/overlays/benzinga/benzinga-channels-api-overlay/)
- [Benzinga Conference Calls Api Overlay](https://apis.io/overlays/benzinga/benzinga-conference-calls-api-overlay/)
- [Benzinga Consensus Ratings Api Overlay](https://apis.io/overlays/benzinga/benzinga-consensus-ratings-api-overlay/)
- [Benzinga Dividends Api Overlay](https://apis.io/overlays/benzinga/benzinga-dividends-api-overlay/)
- [Benzinga Earnings Api Overlay](https://apis.io/overlays/benzinga/benzinga-earnings-api-overlay/)
- [Benzinga Earnings Call Transcripts Api Overlay](https://apis.io/overlays/benzinga/benzinga-earnings-call-transcripts-api-overlay/)
- [Benzinga Economics Api Overlay](https://apis.io/overlays/benzinga/benzinga-economics-api-overlay/)
- [Benzinga Erx Gaps Api Overlay](https://apis.io/overlays/benzinga/benzinga-erx-gaps-api-overlay/)
- [Benzinga Events Api Overlay](https://apis.io/overlays/benzinga/benzinga-events-api-overlay/)
- [Benzinga Fda Api Overlay](https://apis.io/overlays/benzinga/benzinga-fda-api-overlay/)
- [Benzinga Fundamentals Api Overlay](https://apis.io/overlays/benzinga/benzinga-fundamentals-api-overlay/)
- [Benzinga Government Trade Reports Api Overlay](https://apis.io/overlays/benzinga/benzinga-government-trade-reports-api-overlay/)
- [Benzinga Government Trades Api Overlay](https://apis.io/overlays/benzinga/benzinga-government-trades-api-overlay/)
- [Benzinga Guidance Api Overlay](https://apis.io/overlays/benzinga/benzinga-guidance-api-overlay/)
- [Benzinga Halt Resume Api Overlay](https://apis.io/overlays/benzinga/benzinga-halt-resume-api-overlay/)
- [Benzinga Insider Transaction Api Overlay](https://apis.io/overlays/benzinga/benzinga-insider-transaction-api-overlay/)
- [Benzinga Ipos Api Overlay](https://apis.io/overlays/benzinga/benzinga-ipos-api-overlay/)
- [Benzinga Logos Api Overlay](https://apis.io/overlays/benzinga/benzinga-logos-api-overlay/)
- [Benzinga Ma Api Overlay](https://apis.io/overlays/benzinga/benzinga-ma-api-overlay/)
- [Benzinga Market Data Api Overlay](https://apis.io/overlays/benzinga/benzinga-market-data-api-overlay/)
- …and 17 more published on APIs.io

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Benzinga Authentication](https://apis.io/security/benzinga/benzinga-authentication/)
- [Benzinga Domain Security](https://apis.io/security/benzinga/benzinga-domain-security/)
- [Benzinga Vulnerability Disclosure](https://apis.io/security/benzinga/benzinga-vulnerability-disclosure/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.benzinga.com)
- [Documentation](https://docs.benzinga.com)
- [Getting started](https://docs.benzinga.com/introduction/introduction)
- [API reference](https://docs.benzinga.com/api-reference/introduction)
- [Sign up](https://www.benzinga.com/apis/licensing/register)
- [Support](https://help.benzinga.com/en/)
- [Changelog](https://docs.benzinga.com/changelog/overview)
- [Blog](https://www.benzinga.com/news)
- [Security](https://www.benzinga.com/.well-known/security-policy.md)
- [Terms of service](https://www.benzinga.com/terms-and-conditions)
- [Privacy policy](https://www.benzinga.com/page/privacy)
- [GitHub](https://github.com/Benzinga)
- [Status](https://status.benzinga.com)

## API Evangelist rating

**Kin Score 50.4** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 78.6 |
| Contract quality | 54.0 |
| Contract governance | 4.5 |
| Operational transparency | 52.6 |
| Developer ergonomics | 66.1 |
| Access clarity | 34.2 |

**Agent readiness 27.0** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | — |
| Event Surface Described | derived (partial credit) |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | mostly |

**Regulatory alignment 28.7** — Securities & Market Data

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/benzinga/](https://apis.io/providers/benzinga/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Benzinga: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/benzinga/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
