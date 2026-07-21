# Benzinga (benzinga)

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
