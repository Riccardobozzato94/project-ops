# ProjectOps

Demo interattiva di **report settimanale da foglio di calcolo**. KPI calcolati, narrativa AI, firma del PM, storico completo di ogni valore.

**Live demo:** https://riccardobozzato94.github.io/project-ops/

## Cosa dimostra
- Ogni modifica del foglio resta tracciata (chi, cosa, quando) = audit log nativo.
- **Output AI reale** catturato il 18/11/2026 (`Qwen3.6-27B`): narrativa corretta e flag qualità dati, ma JSON troncato dal limite di token → **corretto a mano** prima della firma. Il tool segnala, non corregge al posto del PM.
- Dati finti dichiarati; nessun risultato commerciale dichiarato.

## Stack
HTML/CSS/JS statico, GitHub Pages. In produzione: Cloudflare Workers + D1 con storicizzazione, Gemini free tier, Make free.

Parte del portfolio AI Operations di Riccardo Bozzato, PMP®.
