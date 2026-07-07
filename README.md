# HELD Experience

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
index.html        # egyoldalas főoldal
adatkezeles.html  # GDPR adatkezelési tájékoztató (a jelentkezési űrlaphoz)
assets/           # hero, folyó és portré képek + held.png logó
robots.txt        # élő: keresők számára engedélyezett
sitemap.xml       # homepage
```

## Állapot
v1 — magyar nyelven, élő ([heldexperience.com](https://www.heldexperience.com)). A jelentkezési űrlap
Supabase-be menti az e-mail-címeket (anon kulcs + RLS insert-only). Nyitott: app-store linkek.
Az EN szövegek készen állnak egy nyelvváltóhoz.
