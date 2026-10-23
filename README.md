# KI-Coach-Baukasten (Demo)

> **Hinweis:** Beide Baukästen sind **Demos** bzw. Prototypen zur Veranschaulichung. Sie sind kein offiziell freigegebenes Angebot der Universität, und die erzeugten Prompts ersetzen weder Rechtsauskunft noch die geltenden Regelungen zu Prüfungen, KI-Nutzung, Datenschutz und IT-Sicherheit.

Interaktive Baukästen, mit denen man in wenigen Schritten einen eigenen KI-Coach zusammenstellt. Am Ende steht ein fertiger Systemprompt, zum Beispiel für ein eigenes Modell im [KI-Chat der JGU](https://ki-chat.uni-mainz.de).

| Datei | Zielgruppe | Coaches |
| --- | --- | --- |
| `KI-Coach-Baukasten_Studierende.html` | Studierende | Lern-Coach, Schreib-Coach, Recherche-Coach |
| `KI-Coach-Baukasten_Verwaltung.html` | Beschäftigte der Hochschulverwaltung | Korrespondenz-Coach, Regelwerk-Coach, Organisations-Coach |

## Für Studierende

- **Drei Coaches**: jeweils 7 Schritte, davon 4 gemeinsame (Studium, Persönlichkeit, Ton, Feedback) und 3 eigene pro Coach
- **Feste Leitplanken** in jedem Prompt: keine erfundenen Quellen, keine Prüfungsleistungen, ehrliches Feedback statt Gefälligkeit, Hinweise zu Datenschutz und Urheberrecht
- **Ausgabe** für den KI-Chat der JGU (Name, Beschreibung, Systemprompt, Prompt-Vorschläge) oder für andere KI-Tools
- **Vorlage für einen KI-Nutzungsnachweis**, damit die Nutzung transparent gekennzeichnet werden kann
- **Markdown-Export** des kompletten Coaches

## Für die Verwaltung

- **Drei Coaches**: jeweils 7 Schritte, davon 4 gemeinsame (Arbeitsbereich, Persönlichkeit, Ton, Feedback) und 3 eigene pro Coach
  - **Korrespondenz-Coach**: E-Mails, Schreiben, Vermerke und Infotexte verständlich formulieren (Zielgruppe, Textart, wie weit der Coach mitschreibt)
  - **Regelwerk-Coach**: Ordnungen, Richtlinien und Vorschriften verstehen und Fälle einordnen (Regelungsbereich, Aufgabe, wie streng er sich an Quellen hält)
  - **Organisations-Coach**: Besprechungen, Abläufe, Projekte und Prioritäten (Schwerpunkt, Ergebnisformat, Vorgehen)
- **Feste Leitplanken** in jedem Prompt: keine erfundenen Fakten, Fristen oder Paragraphen, keine verbindliche Rechtsauskunft, Platzhalter statt Annahmen, Hinweise zu Datenschutz und Vertraulichkeit, Verantwortung und Entscheidungen bleiben beim Menschen
- **Du oder Sie**: Die Oberfläche siezt; ob der Coach duzt oder siezt, wird im Schritt „Ton“ gewählt
- **Ausgabe** für den KI-Chat der JGU oder für andere KI-Tools
- **Prüfliste „Vor dem Versand prüfen“** für KI-unterstützte Arbeitsergebnisse (Fakten, Platzhalter, Datenschutz, Vier-Augen-Prinzip)
- **Markdown-Export** des kompletten Coaches

## Nutzung

Die gewünschte HTML-Datei herunterladen und im Browser öffnen. Es ist keine Installation nötig, und die Seiten laden nichts aus dem Internet nach.

**In Moodle oder im Intranet**: als Datei-Ressource hochladen oder per iframe einbetten. Falls der Browser das Kopieren im iframe blockiert, nutzt die Seite automatisch einen Ersatzweg.

**Anpassen**: Alle Inhalte (Schritte, Optionen, Leitplanken) stehen als Daten im `<script>`-Block (`COACHES`, `STEPS`, `COMMON_RULES`) und lassen sich ohne Programmierkenntnisse im Texteditor ändern.

## Lizenz und Urheber:innen

Dieses Projekt basiert auf dem **„Lern-Coach Baukasten“** von **Marc Lachmann & André Uthmann**, Moderatoren der Bezirksregierung Düsseldorf (Stand: Oktober 2026), lizenziert unter [CC BY-NC-SA 3.0 DE](https://creativecommons.org/licenses/by-nc-sa/3.0/de/).

**Bearbeitung:** Paul Baselt, Dezernat Hochschulentwicklung, Johannes Gutenberg-Universität Mainz (Oktober 2026)
Die Bearbeitung umfasst die Anpassung für Studierende, die Erweiterung um den Schreib- und den Recherche-Coach, die Übertragung auf die Hochschulverwaltung (Korrespondenz-, Regelwerk- und Organisations-Coach), eine Ausgabe für den KI-Chat der JGU sowie eine neue Gestaltung.

Die bearbeitete Fassung steht ebenfalls unter **[CC BY-NC-SA 3.0 DE](https://creativecommons.org/licenses/by-nc-sa/3.0/de/)**: Namensnennung, nicht kommerziell, Weitergabe unter gleichen Bedingungen. Wer das Projekt weiterverwendet oder verändert, muss die ursprünglichen Autoren und den Bearbeiter nennen und die eigene Fassung unter derselben Lizenz veröffentlichen.
