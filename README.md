# swing-4h-data

Dati pubblici (solo statistiche, **nessuna credenziale**) della dashboard del bot **Smart Swing Trader 4H**.

- `dashboard_data.json` — rigenerato dal bot ogni ~5 min, pubblicato qui da una GitHub Action ogni 30 min.
- `trading_bot_4h.html` — la dashboard (da mettere sul sito; legge il JSON via raw URL).

URL dati: `https://raw.githubusercontent.com/ivanx519/swing-4h-data/master/dashboard_data.json`

Secret richiesto: `VPS_PASSWORD` (password root VPS, per lo `scp` in sola lettura).
