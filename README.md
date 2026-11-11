# lexy-data

The daily news feed of the Lexy study app, served at `https://abdulaziz-l.github.io/lexy-data/news.json`.

Every morning the daily agent (in Lexy's own, private project) reads the new documents listed by lex.uz and
the drafts listed by regulation.gov.uz, has Kimi (Moonshot AI) write a short neutral news item about each one
in Uzbek, Russian and English from the document's own text, and publishes `news.json` here. Every item links
to its official source. The summaries are written by AI, and the app says so.
