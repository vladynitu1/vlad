# vladynitu1.github.io

Structura site-ului (fiecare pagină are folderul ei):

```
index.html                 pagina principală (Acasă)
404.html                   redirecționează adresele vechi (am.html -> am/ etc.)

assets/js/                 scripturi comune tuturor paginilor
  theme.js  sticky.js  status.js  luni.js  nume-auto.js

am/            index.html  am.json (se creează din editor: Acasă › 🚂 Rame)
bani/          index.html  bani.json
cs2/           index.html  data.json  media/
fisalucru/     index.html
fisapontaj/    index.html
intarzieri/    index.html  intarzieri.json
salariu/       index.html
test/          index.html
turnus/        index.html  turnusuri.json

data/                      date comune (admin.json, theme.json, mecanici/, conductori/,
                           turnusuri-partajate.json, date.json)
```

Adrese: `/am/`, `/fisalucru/`, `/turnus/` etc.
Scripturile comune se încarcă din `assets/js/` (în pagini: `../assets/js/…`).
