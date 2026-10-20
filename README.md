# KI-Coach-Baukasten für Studierende

Ein interaktiver Baukasten, mit dem Studierende in wenigen Schritten ihren eigenen KI-Coach zusammenstellen: einen **Lern-Coach**, einen **Schreib-Coach** oder einen **Recherche-Coach**. Am Ende steht ein fertiger Systemprompt, zum Beispiel für ein eigenes Modell im [KI-Chat der JGU](https://ki-chat.uni-mainz.de).

## Funktionen

- **Drei Coaches**: jeweils 7 Schritte, davon 4 gemeinsame (Studium, Persönlichkeit, Ton, Feedback) und 3 eigene pro Coach
- **Feste Leitplanken** in jedem Prompt: keine erfundenen Quellen, keine Prüfungsleistungen, ehrliches Feedback statt Gefälligkeit, Hinweise zu Datenschutz und Urheberrecht
- **Ausgabe** für den KI-Chat der JGU (Name, Beschreibung, Systemprompt, Prompt-Vorschläge) oder für andere KI-Tools
- **Vorlage für einen KI-Nutzungsnachweis**, damit die Nutzung transparent gekennzeichnet werden kann
- **Markdown-Export** des kompletten Coaches

## Nutzung

Die Datei `KI-Coach-Baukasten_Studierende.html` herunterladen und im Browser öffnen. Es ist keine Installation nötig, und die Seite lädt nichts aus dem Internet nach.

**In Moodle**: als Datei-Ressource hochladen oder per iframe einbetten. Falls der Browser das Kopieren im iframe blockiert, nutzt die Seite automatisch einen Ersatzweg.

**Anpassen**: Alle Inhalte (Schritte, Optionen, Leitplanken) stehen als Daten im `<script>`-Block (`COACHES`, `STEPS`, `COMMON_RULES`) und lassen sich ohne Programmierkenntnisse im Texteditor ändern.

## Lizenz und Urheber:innen

Dieses Projekt basiert auf dem **„Lern-Coach Baukasten“** von **Marc Lachmann & André Uthmann**, Moderatoren der Bezirksregierung Düsseldorf (Stand: Oktober 2026), lizenziert unter [CC BY-NC-SA 3.0 DE](https://creativecommons.org/licenses/by-nc-sa/3.0/de/).

**Bearbeitung:** Paul Baselt, Dezernat Hochschulentwicklung, Johannes Gutenberg-Universität Mainz (Oktober 2026)
Die Bearbeitung umfasst die Anpassung für Studierende, die Erweiterung um den Schreib- und den Recherche-Coach, eine Ausgabe für den KI-Chat der JGU sowie eine neue Gestaltung.

Die bearbeitete Fassung steht ebenfalls unter **[CC BY-NC-SA 3.0 DE](https://creativecommons.org/licenses/by-nc-sa/3.0/de/)**: Namensnennung, nicht kommerziell, Weitergabe unter gleichen Bedingungen. Wer das Projekt weiterverwendet oder verändert, muss die ursprünglichen Autoren und den Bearbeiter nennen und die eigene Fassung unter derselben Lizenz veröffentlichen.
