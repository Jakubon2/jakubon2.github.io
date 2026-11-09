# jakubon2.github.io

Osobní portfolio Jakuba Jana Ondráčka – QA tester se zaměřením na AI a automatizaci v Deafcomu, student aplikované informatiky na VŠE a redaktor Dotekománie.

Web běží na **[jakubon2.github.io](https://jakubon2.github.io)**.

## Co tu je

- `index.html` – hlavní stránka: práce, projekty, kontakt
- `powerbi.html` – podstránka s Power BI reportem
- `style.css` – styly pro obě stránky
- `img/` – screenshoty projektů
- `cv/` – životopis v LaTeXu (`.tex`) a vygenerované PDF
- `semestralni_prace_databaze.pdf` – semestrální práce z databází

Čisté HTML a CSS bez buildu, hostované přes GitHub Pages z větve `main`.

## Lokální náhled

```bash
python3 -m http.server 4173
```

a otevřít `http://localhost:4173`.

## Úprava životopisu

Po změně `cv/jakub_jan_ondracek_cv.tex` je potřeba znovu vygenerovat PDF, např.:

```bash
cd cv && tectonic jakub_jan_ondracek_cv.tex
```

(funguje i `pdflatex` nebo Overleaf)

---

Obsah, texty a screenshoty jsou osobní. Šablona životopisu vychází z [Jake's Resume](https://github.com/jakegut/resume) (MIT).
