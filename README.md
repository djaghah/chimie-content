# chimie-content

Conținutul remote al aplicației „Chimie cu Iris” (repo GitHub **public** `djaghah/chimie-content`, de creat — vezi `../docs/PLAY-CHECKLIST.md` §3).

- `bank.json` — banca de exerciții servită prin jsDelivr: `https://cdn.jsdelivr.net/gh/djaghah/chimie-content@main/bank.json`.
  Se copiază din `../web/bank.json` (generată de `app/tools/gen-bank.js`). Aplicația o folosește doar dacă: trece validarea strictă, versiunea e strict mai mare
  decât cea inclusă, toate cheile de text există în dicționarele aplicației și nu lipsește niciun exercițiu cu stele salvate.
- `privacy-policy.html` — politica de confidențialitate (8 limbi), servită prin GitHub Pages: `https://djaghah.github.io/chimie-content/privacy-policy.html`.

Publicare: commit → `git push` prin **SSH** ca djaghah → `https://purge.jsdelivr.net/gh/djaghah/chimie-content@main/bank.json`.
Nu pune aici nimic secret (repo-ul e public).
