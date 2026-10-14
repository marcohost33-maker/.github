<!--
Org-weite PR-Vorlage (gepflegt im .github-Default-Repo).
Gilt fuer Node- und Python-Repos. Nicht zutreffende Zeilen einfach loeschen.
-->

## Was & warum

<!-- Eine knappe Zusammenfassung der Aenderung und der Motivation. -->

Closes #

## Art der Aenderung

- [ ] Fix (behebt ein Problem, kein Breaking-Change)
- [ ] Feature (neue Funktionalitaet, kein Breaking-Change)
- [ ] Breaking-Change (bestehendes Verhalten aendert sich)
- [ ] Doku / Infrastruktur / Tooling

## Definition of Done

- [ ] Build / CI ist gruen (belegt, nicht "sollte gehen")
- [ ] Tests bzw. Verifikation N/N PASS (Befund im PR oder in den Logs verlinkt)
- [ ] Negativ-/Edge-Faelle bedacht (leer, 0, negativ, Grenzwert)
- [ ] Keine Secrets, Tokens oder `.env`-Inhalte im Diff, in Logs oder Fixtures
- [ ] Doku / README aktualisiert, falls sich Verhalten oder Setup aendert

## Verifikation

<!--
Wie wurde die Korrektheit belegt? Befehl + Ergebnis, z.B.:
`npm ci && npm run build` -> exit 0
`python -m pytest` -> 42/42 PASS
-->

## Reviewer-Hinweise

- Dieser PR sollte als **Draft** starten und erst nach verifizierter Definition-of-Done
  auf "ready" gesetzt werden.
- Vor dem Merge erfolgt eine unabhaengige Verifikations-/Review-Runde.
- Mit KI-Assistenten erstellte PRs werden gekennzeichnet, siehe CONTRIBUTING.md.
- Merge bevorzugt per **Auto-Merge (Squash)**: `gh pr merge --auto --squash`.
