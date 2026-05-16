# ki-modell-auswahl

Interaktive Übung zur Auswahl des passenden KI-Sprachmodells für Unterrichtssettings in **AIS.chat**.

Die Übung läuft als statische Single-Page-Anwendung direkt im Browser, ohne Backend, ohne Tracking. Lehrkräfte wählen ein Unterrichtsszenario aus, woraufhin die in AIS.chat verfügbaren Modelle markiert werden, die für dieses Szenario geeignet sind.

**Live-Version:** <https://mgkurz.github.io/ki-modell-auswahl/>

## Inhalt

- Fünf Unterrichtsszenarien: Dialog und kreatives Schreiben, kurze direkte Antworten, sparsame und schnelle Antworten, Mathematik und Logik, Allround-Einsatz.
- Zehn in AIS.chat verfügbare Modelle (Stand Mai 2026): GPT-5 mini, GPT-5, GPT-5 nano, GPT-5.5, GPT-4o-mini, o3-mini, Llama-3.1-8B, Mistral Nemo Instruct, Llama-3.3-70B, GPT-4o.

## Einsatzkontext

Die Übung wurde für den Selbstlernkurs „Fit für AIS.chat" der Hessischen Lehrkräfteakademie erstellt (SchulMoodle Hessen). Sie ist als Embed oder als Link nutzbar. Sie kann ohne Anpassung in anderen Bundesländern eingesetzt werden, sofern dort dieselben Modelle über AIS.chat angeboten werden.

## Hinweise zur Pflege

Die Modellliste in AIS.chat ändert sich gelegentlich. Bei einer Aktualisierung sind drei Stellen in `index.html` anzupassen:

1. Die `<div class="model-item">`-Blöcke in der rechten Spalte (Name, Beschreibung, optional NEU-Badge oder Blatt-Symbol).
2. Das `recommendations`-Objekt im `<script>`-Block, falls sich die Empfehlungen ändern.
3. Der `<meta name="description">`-Tag und der Stand im Footer-Hinweis.

## Lizenz

Lizenziert unter der [Creative Commons Namensnennung. Weitergabe unter gleichen Bedingungen 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/deed.de).

© 2026 Martin Kurz, Hessische Lehrkräfteakademie.

Namensnennung bei Weiterverwendung: „Martin Kurz, Hessische Lehrkräfteakademie, lizenziert unter CC BY-SA 4.0". Bearbeitungen und Weitergaben unter gleicher Lizenz erwünscht.
