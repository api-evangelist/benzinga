# Benzinga (benzinga)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Benzinga is a Detroit-based financial media and market data company (founded 2010, acquired by Beringer Capital in 2021) that licenses its newsroom and data products through a developer-first API platform at docs.benzinga.com. Products span real-time financial news (Newsfeed, Press Releases, Why Is It Moving), quantified news sentiment, a deep corporate-events Calendar, delayed quotes, historical OHLCV bars, fundamentals, logos, ticker trends, and earnings-call transcripts. Delivery is REST over https://api.benzinga.com with API-key auth, plus WebSocket streams, a TCP streaming service, and a data webhook engine, with official OpenAPI and AsyncAPI specs published on GitHub.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/benzinga/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/benzinga/refs/heads/main/apis.yml)

## Tags

- Financial
- Market Data
- Stocks
- News
- Real-Time
- Sentiment
- Analyst Ratings
- Earnings
- Options
- Streaming

## Timestamps

- **Created:** 2026-07-21
- **Modified:** 2026-07-21

## APIs

### Benzinga Newsfeed & Why Is It Moving API

Structured real-time and historical financial news from the Benzinga newsroom, with channel filters, removed-news deltas, and Why Is It Moving (WIIM) one-line explanations of price action, queried by tickers, date, and channels.

- **Human URL:** [https://docs.benzinga.com/api-reference/news-api/overview](https://docs.benzinga.com/api-reference/news-api/overview)
- **Base URL:** `https://api.benzinga.com`

#### Properties

- [Documentation](https://docs.benzinga.com/api-reference/news-api/overview)
- [API Reference](https://docs.benzinga.com/api-reference/news-api/get-news-items)
- [OpenAPI](openapi/benzinga-news-api-openapi.yml)

### Benzinga Press Releases API

Structured corporate press release content with ticker, date, and channel filtering plus updatedSince delta queries.

- **Human URL:** [https://docs.benzinga.com/api-reference/news-api/press-releases/overview](https://docs.benzinga.com/api-reference/news-api/press-releases/overview)
- **Base URL:** `https://api.benzinga.com`

#### Properties

- [Documentation](https://docs.benzinga.com/api-reference/news-api/press-releases/overview)
- [API Reference](https://docs.benzinga.com/api-reference/news-api/press-releases/get-press-releases)
- [OpenAPI](openapi/benzinga-press-releases-api-openapi.yml)

### Benzinga NewsQuantified API

Quantified news analytics with sentiment scores, relevance metrics, trending scores, and ticker-level market impact indicators for quantitative strategies.

- **Human URL:** [https://docs.benzinga.com/api-reference/newsquantified-api/overview](https://docs.benzinga.com/api-reference/newsquantified-api/overview)
- **Base URL:** `https://api.benzinga.com`

#### Properties

- [Documentation](https://docs.benzinga.com/api-reference/newsquantified-api/overview)
- [API Reference](https://docs.benzinga.com/api-reference/newsquantified-api/get-newsquantified-data)
- [OpenAPI](openapi/benzinga-newsquantified-api-openapi.yml)

### Benzinga Calendar API

Corporate events and reference data across earnings, dividends, analyst ratings and consensus, IPOs, splits, offerings, M&A, economics, FDA milestones, conference calls, guidance, halts/resumes, block trades, unusual options activity, government trades, and SEC Form 4 insider transactions.

- **Human URL:** [https://docs.benzinga.com/api-reference/calendar-api/overview](https://docs.benzinga.com/api-reference/calendar-api/overview)
- **Base URL:** `https://api.benzinga.com`

#### Properties

- [Documentation](https://docs.benzinga.com/api-reference/calendar-api/overview)
- [API Reference](https://docs.benzinga.com/api-reference/calendar-api/get-earnings)
- [OpenAPI](openapi/benzinga-calendar-api-openapi.yml)

### Benzinga Historical Bars API

Historical OHLCV price bars for multiple tickers at configurable intervals with relative date range support, served from the /api/v2/bars endpoint.

- **Human URL:** [https://docs.benzinga.com/api-reference/bars/overview](https://docs.benzinga.com/api-reference/bars/overview)
- **Base URL:** `https://api.benzinga.com`

#### Properties

- [Documentation](https://docs.benzinga.com/api-reference/bars/overview)
- [API Reference](https://docs.benzinga.com/api-reference/bars/get-bars)
- [OpenAPI](openapi/benzinga-data-api-proxy-openapi.yml)

### Benzinga Delayed Quotes API

Delayed price quotes for lists of symbols via /api/v1 and /api/v2 quoteDelayed endpoints.

- **Human URL:** [https://docs.benzinga.com/api-reference/quotedelayed/overview](https://docs.benzinga.com/api-reference/quotedelayed/overview)
- **Base URL:** `https://api.benzinga.com`

#### Properties

- [Documentation](https://docs.benzinga.com/api-reference/quotedelayed/overview)
- [API Reference](https://docs.benzinga.com/api-reference/quotedelayed/get-delayed-quotes)
- [OpenAPI](openapi/benzinga-data-api-proxy-openapi.yml)

### Benzinga Market Movers & Short Interest API

Market movers by session and time range with screener-style filtering, plus FINRA-sourced short interest data including days to cover and short interest ratios.

- **Human URL:** [https://docs.benzinga.com/api-reference/market-data/overview](https://docs.benzinga.com/api-reference/market-data/overview)
- **Base URL:** `https://api.benzinga.com`

#### Properties

- [Documentation](https://docs.benzinga.com/api-reference/market-data/overview)
- [API Reference](https://docs.benzinga.com/api-reference/market-data/get-market-movers)
- [OpenAPI](openapi/benzinga-data-api-proxy-openapi.yml)

### Benzinga Company Fundamentals API

Company fundamentals across v2.1 and v3 endpoints - balance sheets, income statements, cash flow, earnings reports, company profiles, share classes, asset classification, alpha/beta, and derived, valuation, operation, and earning ratios.

- **Human URL:** [https://docs.benzinga.com/api-reference/fundamentals/overview](https://docs.benzinga.com/api-reference/fundamentals/overview)
- **Base URL:** `https://api.benzinga.com`

#### Properties

- [Documentation](https://docs.benzinga.com/api-reference/fundamentals/overview)
- [API Reference](https://docs.benzinga.com/api-reference/fundamentals/get-fundamentals)
- [OpenAPI](openapi/benzinga-data-api-proxy-openapi.yml)

### Benzinga Logos API

Company, fund, and crypto logo search and bulk sync by ticker and other identifiers, with updated_since paging for full-dataset walks.

- **Human URL:** [https://docs.benzinga.com/api-reference/logos-api/overview](https://docs.benzinga.com/api-reference/logos-api/overview)
- **Base URL:** `https://api.benzinga.com`

#### Properties

- [Documentation](https://docs.benzinga.com/api-reference/logos-api/overview)
- [API Reference](https://docs.benzinga.com/api-reference/logos-api/get-search-logos)
- [OpenAPI](openapi/benzinga-logo-api-openapi.yml)

### Benzinga Ticker Trends API

Trending-ticker rankings and per-ticker trend scores aggregated across time intervals from Benzinga audience activity.

- **Human URL:** [https://docs.benzinga.com/api-reference/ticker-trends-api/overview](https://docs.benzinga.com/api-reference/ticker-trends-api/overview)
- **Base URL:** `https://api.benzinga.com`

#### Properties

- [Documentation](https://docs.benzinga.com/api-reference/ticker-trends-api/overview)
- [API Reference](https://docs.benzinga.com/api-reference/ticker-trends-api/get-ticker-trend-data)
- [OpenAPI](openapi/benzinga-ticker-trends-api-openapi.yml)

### Benzinga Earnings Call Transcripts API

Real-time and historical conference-call transcripts, audio, AI-generated summaries, and speaker data, fetched by call ID or filtered lists.

- **Human URL:** [https://docs.benzinga.com/api-reference/delivery-api/overview](https://docs.benzinga.com/api-reference/delivery-api/overview)
- **Base URL:** `https://api.benzinga.com`

#### Properties

- [Documentation](https://docs.benzinga.com/api-reference/delivery-api/overview)
- [API Reference](https://docs.benzinga.com/api-reference/delivery-api/calls/fetch-all-calls)
- [OpenAPI](openapi/benzinga-delivery-api-openapi.yml)
- [OpenAPI](openapi/benzinga-earnings-call-transcripts-api-openapi.yml)

### Benzinga Analyst Reports Raw Text API

Raw text of analyst research reports, published as an OpenAPI spec in the Benzinga docs repository.

- **Human URL:** [https://docs.benzinga.com/api-reference/introduction](https://docs.benzinga.com/api-reference/introduction)
- **Base URL:** `https://api.benzinga.com`

#### Properties

- [OpenAPI](openapi/benzinga-analyst-reports-raw-text-api-openapi.yml)

### Benzinga Data Webhook Engine

Push delivery of Benzinga calendar, signal, and sentiment data to customer endpoints with filterable, resilient webhooks and a test-delivery endpoint.

- **Human URL:** [https://docs.benzinga.com/webhook-reference/overview](https://docs.benzinga.com/webhook-reference/overview)
- **Base URL:** `https://api.benzinga.com`

#### Properties

- [Documentation](https://docs.benzinga.com/webhook-reference/overview)
- [API Reference](https://docs.benzinga.com/api-reference/webhook-api/test-webhook-delivery)
- [OpenAPI](openapi/benzinga-webhook-api-openapi.yml)

### Benzinga WebSocket Streaming API

Real-time WebSocket streams over wss://api.benzinga.com for news, earnings, analyst ratings, consensus ratings, analyst insights, bulls/bears cases, and sentence-by-sentence earnings-call transcripts, with session replay actions and token auth.

- **Human URL:** [https://docs.benzinga.com/ws-reference/overview](https://docs.benzinga.com/ws-reference/overview)
- **Base URL:** `wss://api.benzinga.com`

#### Properties

- [Documentation](https://docs.benzinga.com/ws-reference/overview)
- [API Reference](https://docs.benzinga.com/ws-reference/data-websocket/get-news-stream)
- [AsyncAPI](asyncapi/benzinga-news-stream-asyncapi.yml)
- [AsyncAPI](asyncapi/benzinga-calendar-earnings-stream-asyncapi.yml)
- [AsyncAPI](asyncapi/benzinga-calendar-ratings-stream-asyncapi.yml)
- [AsyncAPI](asyncapi/benzinga-consensus-ratings-stream-asyncapi.yml)
- [AsyncAPI](asyncapi/benzinga-analyst-insights-stream-asyncapi.yml)
- [AsyncAPI](asyncapi/benzinga-bulls-bears-say-stream-asyncapi.yml)
- [AsyncAPI](asyncapi/benzinga-transcripts-stream-asyncapi.yml)

### Benzinga TCP Streaming Service

Low-latency persistent TCP stream (tcp-v1.benzinga.io port 11337, optional TLS) delivering real-time news, option alerts, and market events as JSON messages, authenticated with username plus API key, with official Go and Python client libraries.

- **Human URL:** [https://docs.benzinga.com/tcp-reference/introduction](https://docs.benzinga.com/tcp-reference/introduction)
- **Base URL:** `tcp://tcp-v1.benzinga.io:11337`

#### Properties

- [Documentation](https://docs.benzinga.com/tcp-reference/introduction)
- [API Reference](https://docs.benzinga.com/tcp-reference/connection)
- [Go Client](https://docs.benzinga.com/tcp-reference/go-client)

## Common Properties

- [Website](https://www.benzinga.com)
- [Portal](https://www.benzinga.com/apis/)
- [Documentation](https://docs.benzinga.com)
- [GitHub Organization](https://github.com/Benzinga)
- [LinkedIn](https://www.linkedin.com/company/benzinga)
- [Blog](https://www.benzinga.com/news)
- [Sign Up](https://www.benzinga.com/apis/licensing/register)
- [Terms of Service](https://www.benzinga.com/terms-and-conditions)
- [Privacy Policy](https://www.benzinga.com/page/privacy)
- [Status Page](https://status.benzinga.com)
- [Change Log](https://docs.benzinga.com/changelog/overview)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
