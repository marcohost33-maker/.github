# Sicherheitsrichtlinie

**English summary:** Please do not report security issues in public issues.
Report them privately in the affected repository: tab **Security** ->
**Report a vulnerability** (GitHub private vulnerability reporting). If that
button is missing (private reporting is not enabled for that repository), open
an issue there that only asks for a private security contact, with no details
about the vulnerability.

## Meldeweg

Sicherheitsrelevante Befunde bitte **nicht** als öffentliches Issue melden,
sondern vertraulich im **betroffenen Repository**:

1. Im betroffenen Repository den Reiter **Security** öffnen.
2. **Report a vulnerability** wählen.
3. Beschreiben, was passiert, wie es sich nachstellen lässt und welcher Commit
   oder welche Version betroffen ist.

Direkter Link nach dem Muster
`https://github.com/marcohost33-maker/<repository>/security/advisories/new`.

**Fehlt der Knopf „Report a vulnerability“** (private Meldungen sind nicht in
jedem Repository eingeschaltet), im betroffenen Repository ein Issue eröffnen,
das **nur** um einen vertraulichen Kontakt bittet, ohne Angaben zur Lücke selbst.
Der weitere Austausch läuft dann über den vereinbarten privaten Weg. (So
empfiehlt es auch GitHub: [Privately reporting a security vulnerability](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing-information-about-vulnerabilities/privately-reporting-a-security-vulnerability).)

Bitte nicht im `.github`-Repository melden: dort landet die Meldung beim
falschen Projekt.

## Unterstützte Versionen

Sofern ein Repository in seinem eigenen `SECURITY.md` nichts anderes festlegt,
werden Korrekturen nur auf dem aktuellen Stand des Default-Zweigs gemacht. Es
gibt keine Langzeit-Zweige.

Hat ein Repository ein eigenes `SECURITY.md`, gilt dieses.
