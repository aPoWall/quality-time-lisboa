# Quality Time · Lisboa

A calm, poster-first guide to what is worth your time in Lisbon.

**Live:** https://events.2-59-171-122.sslip.io/

This repository is the public-safe interface snapshot. It contains verified public event data and source metadata. Personal preference weights, Telegram content, private locations and write-capable integrations are deliberately excluded.

## Interface

- today, tomorrow, next three days, weekend, week and month;
- poster-first event cards;
- collapsed search, exact date, source, topic and sort controls;
- responsive phone layout;
- original-source links and evidence state;
- public source-signal score based on verification, confidence, poster availability and corroboration.

Open `index.html` through any static web server. The app first looks for a live `/api` surface and falls back to the included `data/public/*.json` snapshot.

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Privacy boundary

The public build excludes:

- personal fit scores and explanations;
- learned preference state;
- Telegram messages and private source identifiers;
- home location and route origins;
- calendar, ticketing, messaging and feedback writes.

## License

MIT
