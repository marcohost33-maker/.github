# Beitragen

**English summary:** Contributions are welcome. Open pull requests as drafts,
show how you verified the change (command and result), and never commit
secrets. A repository's own `CONTRIBUTING.md` takes precedence over this file.

## Ablauf

1. **Issue zuerst** bei grösseren Änderungen, damit Richtung und Umfang vorab
   geklärt sind. Kleine Korrekturen (Tippfehler, Links) gehen direkt als Pull
   Request.
2. **Pull Request als Draft öffnen.** Erst auf "Ready for review" setzen, wenn
   die Definition of Done aus der PR-Vorlage erfüllt ist.
3. **Verifikation belegen.** Im PR steht, wie die Korrektheit gezeigt wurde:
   Befehl und Ergebnis, zum Beispiel `python -m pytest` -> `42/42 passed`.
   "Sollte gehen" reicht nicht.
4. **Negativ- und Grenzfälle bedenken:** leere Eingabe, 0, negative Werte,
   Grenzwerte.
5. **Unabhängige Prüfung vor dem Merge.** Jeder PR wird vor dem Merge von einer
   zweiten Stelle geprüft, die ihn nicht geschrieben hat.

## Was nicht in ein Repository gehört

- Secrets, Tokens, Passwörter, `.env`-Inhalte, auch nicht in Logs oder Fixtures.
- Personenbezogene Daten.
- Lokale Pfade und interne Ablage-Verweise, die Aussenstehende nicht öffnen
  können.

## KI-gestützte Beiträge

Ein Teil der Arbeit in diesen Repositories entsteht mit KI-Assistenten. Solche
Pull Requests werden mit einem Label gekennzeichnet (`agent:claude`,
`agent:codex` oder `agent:bot`), soweit das Repository diese Labels führt. Für
sie gelten dieselben Regeln wie für alle anderen Beiträge.

## Lizenz

Jedes Repository steht unter seiner eigenen Lizenz, siehe dessen `LICENSE`.

## Verhalten

Es gilt der [Verhaltenskodex](CODE_OF_CONDUCT.md).
