# Zum Anfassen – Startseite

Die Startseite unter https://daniel-hopium.github.io/ führt zu allen Lern-Apps:

| App | Thema |
|---|---|
| [Angular-Patterns](https://daniel-hopium.github.io/angular-patterns/) | Modernes Angular, 85 Lektionen |
| [ARIA-Kompass](https://daniel-hopium.github.io/aria-compass/) | WAI-ARIA, 22 Lektionen |
| [HTML-Atlas](https://daniel-hopium.github.io/html-atlas/) | HTML-Elemente und Attribute, 110 Einträge |
| [CSS-Atlas](https://daniel-hopium.github.io/css-atlas/) | CSS-Eigenschaften und Selektoren, 105 Einträge |
| [Daumenregel](https://daniel-hopium.github.io/pattern-library/) | UI-Regeln, 29 Lektionen |
| [Schiri-Trainer Volleyball](https://daniel-hopium.github.io/volleyball-referee-trainer/) | Schiedsrichterprüfung, 130 Fragen |

## Starten

`index.html` ist die ganze Seite: kein Build, keine Abhängigkeiten. Die Kartenlinks und
Symbole zeigen auf `/<repo>/`, darum braucht es lokal einen Server, der den Ordner *über*
den Repos ausliefert (z. B. `D:\Repositories`), und dann `/daniel-hopium.github.io/`.

## Bedienung

- **Suche** (`/`): filtert nach Name, Beschreibung und Stichwörtern; Enter öffnet den
  ersten Treffer, Pfeil nach unten springt in die Karten.
- **Themen-Chips**: Web-Grundlagen, Angular, UI-Design, Sport.
- **Tasten 1–6** öffnen die Apps direkt, Pfeiltasten wandern durch die Karten.
- **Sonne/Mond** schaltet helles und dunkles Design, **English/Deutsch** die Sprache –
  beides wie in den Apps, über `?lang=` und `localStorage` (Präfix `portal:`).

## Neue App aufnehmen

Eintrag im Array `APPS` in `index.html` ergänzen (Name, Kategorie, Markenfarbe hell/dunkel,
Texte, Zahl), dazu die Zeile in der Tabelle oben und im `<noscript>`-Block. Hat die App
kein `favicon.svg`, ein Symbol als `icon` mitgeben.
