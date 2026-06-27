# Breath Body and Soul

Integrált terápiás csoportprogram weboldala — **légzés · testmunka · pszichodráma · családállítás**.
Alapítók: Generál Péter & Fáy Viktória.

Statikus oldal: tiszta HTML/CSS/JS, build-lépés és függőség nélkül.

## Helyi futtatás
Nyisd meg az `index.html`-t böngészőben, vagy indíts egy egyszerű szervert:

```bash
python3 -m http.server 8000
# → http://localhost:8000
```

## Struktúra
```
index.html        # egyoldalas főoldal (10 szekció)
cikkek/           # cikk-oldalak (jelenleg placeholder szöveggel)
assets/           # hero, folyó és portré képek
robots.txt        # jelenleg noindex (pre-launch) — élesítéskor távolítsd el
```

## Állapot
v1 — magyar nyelven. Nyitott: valódi testimonialok, program helyszín + dátum,
app-store linkek, cikkek végleges szövege. Az EN szövegek készen állnak egy nyelvváltóhoz.
