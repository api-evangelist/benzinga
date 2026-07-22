---
name: Research earnings with calendar, transcripts, and summaries
description: Pull upcoming/actual earnings from the calendar, then fetch the matching earnings-call transcripts, audio, and AI summaries.
api: openapi/benzinga-earnings-api-openapi.yml
operations: [get-earnings, get-earnings-call-transcripts, get-earnings-call-transcript-audio-files, get-summaries, get-summary-by-call-id]
generated: '2026-07-22'
method: generated
---

# Research earnings end-to-end

Authenticate with `Authorization: token <YOUR_API_KEY>` (or `?token=`).

1. **Earnings calendar** — `get-earnings` (`GET /api/v2.1/calendar/earnings`) with `parameters[tickers]` and a date range: actual vs estimated EPS/revenue and surprises.
2. **Transcripts** — `get-earnings-call-transcripts` (`GET /api/v1/earnings-call-transcripts`) filtered by ticker/date for full call text; `get-earnings-call-transcript-audio-files` (`GET /api/v1/earnings-call-transcripts/audio`) for the audio.
3. **AI summaries** — `get-summaries` (`GET /api/v1/transcripts/summaries`, paginated; COMPLETED calls by default) and `get-summary-by-call-id` (`GET /api/v1/transcripts/summaries/{call_id}`) for a specific call.

Notes: transcripts/delivery endpoints live under the licensing-gated Delivery API — a 403 means the product is not in your plan (contact licensing). Use offset pagination (`page`/`pageSize`). Real-time equivalents exist as WebSocket streams (`asyncapi/benzinga-transcripts-stream-asyncapi.yml`).
