# Sicherheitsrichtlinie

**English summary:** Please do not report security issues in public issues.
Report them privately in the affected repository: tab **Security** ->
**Report a vulnerability** (GitHub private vulnerability reporting).

## Meldeweg

Sicherheitsrelevante Befunde bitte **nicht** als öffentliches Issue melden,
sondern vertraulich im **betroffenen Repository**:

1. Im betroffenen Repository den Reiter **Security** öffnen.
2. **Report a vulnerability** wählen.
3. Beschreiben, was passiert, wie es sich nachstellen lässt und welcher Commit
   oder welche Version betroffen ist.

Direkter Link nach dem Muster
`https://github.com/marcohost33-maker/<repository>/security/advisories/new`.

Bitte nicht im `.github`-Repository melden: dort landet die Meldung beim
falschen Projekt.

## Unterstützte Versionen

Sofern ein Repository in seinem eigenen `SECURITY.md` nichts anderes festlegt,
werden Korrekturen nur auf dem aktuellen Stand des Default-Zweigs gemacht. Es
gibt keine Langzeit-Zweige.

Hat ein Repository ein eigenes `SECURITY.md`, gilt dieses.
